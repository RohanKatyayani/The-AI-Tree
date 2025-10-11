# Parameter-Efficient Fine-Tuning (PEFT)

### One-Liner:
*   **What it is:** A set of techniques that fine-tune only a small subset of a model's parameters, making adaptation much more efficient while maintaining performance.

### The Big Picture:
PEFT is the **surgical precision** of model adaptation. Instead of updating all millions/billions of parameters, it strategically modifies only a tiny fraction, achieving similar results with dramatically reduced computational cost.

### How it Works (The Core Idea):
PEFT methods include:
- **LoRA (Low-Rank Adaptation):** Adds small, trainable matrices to attention layers
- **Adapter Layers:** Inserts small bottleneck layers between existing layers
- **Prompt Tuning:** Learns soft prompts instead of modifying model weights
- **BitFit:** Only trains the bias parameters

### Why it Matters:
It makes fine-tuning massive models practical for individuals and organizations with limited resources, democratizing access to state-of-the-art AI.

### A Simple Analogy:
**Customizing a car with smart modifications.**
*   **Full Fine-Tuning:** Rebuilding the entire engine and chassis
*   **PEFT:** Adding a performance chip, better tires, and a spoiler
*   You get significant performance improvements by modifying only key components, not rebuilding everything!
*   Much faster, cheaper, and preserves the original engineering.

### Real-World Examples:
*   **LoRA for LLMs:** Adapting 7B parameter models on consumer GPUs
*   **Adapter layers in multilingual models:** Adding language-specific adapters
*   **Prompt tuning for classification:** Learning task-specific prompts instead of full fine-tuning

---
*🌳 **Parent Concept:** An advanced approach to [[Fine-Tuning]].
*⚡ **The Innovation:** **Extreme parameter efficiency** (often <1% of parameters).
*🚀 **The Impact:** **Democratizes fine-tuning** of large models.
*🔧 **The Methods:** **LoRA**, **Adapters**, **Prompt Tuning**, **BitFit**.
