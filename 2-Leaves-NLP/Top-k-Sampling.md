# Top-k Sampling

### One-Liner:
*   **What it is:** A decoding method that restricts the model's next-word choices to the top `k` most likely options, filtering out low-probability nonsense.

### The Big Picture:
Top-k Sampling is the **quality filter** for text generation. It prevents the model from considering extremely unlikely words, making outputs more coherent and sensible.

### How it Works (The Core Idea):
At each generation step:
1.  The model predicts probabilities for all possible next words
2.  Only the top `k` highest-probability words are kept
3.  The model samples from this filtered set
4.  This eliminates irrelevant or nonsensical options

### Why it Matters:
It strikes a balance between creativity (like high temperature) and coherence, preventing the model from going completely off-track.

### A Simple Analogy:
**A talent show with pre-screening.**
*   **Without Top-k:** Anyone can audition—you might get brilliant performers but also complete disasters.
*   **With Top-k:** Only the top 50 best applicants get to audition—quality is guaranteed to be decent, with some surprise potential.

### Real-World Examples:
*   **GPT-3** uses top-k sampling with k=40 by default.
*   **Creative writing assistants** use it to stay on-topic while allowing variation.
*   **Chatbots** employ it to avoid irrelevant or inappropriate responses.

---
*🌳 **Parent Branch:** [[Natural Language Processing]]
*🎯 **A Decoding Strategy:** Works with [[Temperature]] for controlled generation.
*⚖️ **The Balance:** Allows diversity while maintaining quality.
*🔗 **Related To:** [[Beam Search]] and [[Top-p Sampling]].
