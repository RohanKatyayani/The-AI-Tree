# Quantization

### One-Liner:
*   **What it is:** A model compression technique that reduces the precision of the numbers used in a model's calculations, making it smaller and faster.

### The Big Picture:
Quantization is one of the most effective **leaves** on the **Model Compression** branch. It's a key reason why complex AI can run on your phone or smartwatch, by drastically reducing the memory and computation required.

### How it Works (The Core Idea):
Neural networks typically use 32-bit floating-point numbers (high precision) for calculations. Quantization converts these numbers to lower-precision formats, like 8-bit integers (INT8). This simple change:
*   **Reduces Model Size:** 8-bit numbers take 4x less memory than 32-bit.
*   **Speeds Up Inference:** Integer arithmetic is much faster on most hardware.

### Why it Matters:
It provides a massive boost in efficiency with often a very small drop in accuracy. It's often the first and most impactful compression technique applied before deploying a model.

### A Simple Analogy:
**Switching from a detailed map to a simpler sketch.**
*   A **32-bit model** is like a highly detailed topographic map with elevation lines for every meter. It's precise but bulky and slow to read.
*   An **8-bit quantized model** is like a simplified road map. It doesn't show every hill and valley, but it still perfectly shows the roads and cities you need to navigate. It's much smaller and you can find your route almost instantly.

### Real-World Examples:
*   Converting a **vision model** from FP32 to INT8 to run real-time object detection on a smartphone camera.
*   Quantizing a **language model** to reduce its memory footprint so it can fit on a single GPU for faster chatbot responses.
*   Enabling **always-on speech recognition** on smart home devices with limited power.

---
*🌳 **Parent Concept:** A key technique for [[Model Compression]].
*⚙️ **The Mechanism:** Reducing numerical precision (e.g., FP32 -> INT8).
*🚀 **The Benefit:** Drastically improves speed and reduces memory usage.
*🎯 **The Trade-off:** Potential for a small, often acceptable, loss in accuracy.
