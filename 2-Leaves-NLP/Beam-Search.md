# Beam Search

### One-Liner:
*   **What it is:** A decoding algorithm that keeps multiple potential sequences (beams) at each step during text generation, leading to higher quality and more coherent outputs.

### The Big Picture:
Beam Search is the **quality control** for text generation. Instead of just picking the most likely next word (greedy search), it explores several possibilities simultaneously, avoiding dead ends and finding better overall sequences.

### How it Works (The Core Idea):
At each generation step, beam search:
1.  Keeps the top `k` most likely sequences (the "beam width")
2.  Expands each by considering the next possible words
3.  Keeps the best `k` new sequences
4.  Repeats until sequences are complete

### Why it Matters:
It significantly improves the fluency and coherence of generated text compared to greedy approaches, especially for longer sequences.

### A Simple Analogy:
**Planning a road trip with multiple route options.**
*   **Greedy Search:** Always take the road that looks best *right now* (might hit a dead end).
*   **Beam Search:** Keep 3 alternative routes in mind, and at each intersection, re-evaluate which 3 paths look most promising overall.

### Real-World Examples:
*   Used in **machine translation** to generate fluent sentences.
*   **Text summarization** models use it for coherent summaries.
*   **Chatbots** employ it for more natural conversations.

---
*🌳 **Parent Branch:** [[Natural Language Processing]]
*🎯 **A Decoding Strategy:** For [[Large Language Models]] text generation.
*⚖️ **Trade-off:** Better quality vs. more computation.
*🔗 **Alternative To:** Greedy decoding.
