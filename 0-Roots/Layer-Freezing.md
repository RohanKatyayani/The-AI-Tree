# Layer Freezing

### One-Liner:
*   **What it is:** A technique in transfer learning where certain layers of a neural network are kept fixed (not updated) during training, while other layers are allowed to learn.

### The Big Picture:
Layer Freezing is the **stability anchor** of fine-tuning. It prevents the model from "forgetting" useful pre-trained features while adapting to new data, making the fine-tuning process more controlled and efficient.

### How it Works (The Core Idea):
In a typical transfer learning scenario:
- **Early layers** (closer to input) are often frozen - they learn general features (edges, textures, basic patterns)
- **Later layers** (closer to output) are unfrozen - they learn task-specific features
- Sometimes only the **final classification layer** is trained from scratch

### Why it Matters:
It reduces overfitting, speeds up training, requires less data, and preserves valuable pre-trained knowledge that would be expensive to relearn.

### A Simple Analogy:
**Renovating a house vs. building from scratch.**
*   **Frozen layers:** The solid foundation and structure you keep
*   **Unfrozen layers:** The interior design, paint, and fixtures you update
*   **From scratch:** Demolishing and rebuilding everything (expensive and unnecessary!)
*   You get a updated house while keeping what already works well.

### Real-World Examples:
*   **Computer Vision:** Freezing early CNN layers that detect basic shapes, unfreezing later layers for specific object recognition
*   **NLP:** Freezing early transformer layers that understand grammar, unfreezing later layers for domain-specific vocabulary
*   **Speech Recognition:** Freezing feature extraction layers, training only the acoustic model layers

---
*🌳 **Parent Concept:** A technique used in [[Fine-Tuning]] and [[Transfer Learning]].
*🧊 **The Strategy:** **Selective training** - some layers fixed, some adaptive.
*⚡ **The Benefits:** **Faster training**, **less overfitting**, **stable learning**.
*🎯 **The Practice:** Typically **freeze early layers**, **train later layers**.
