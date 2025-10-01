# Top-p Sampling (Nucleus Sampling)

### One-Liner:
*   **What it is:** A decoding method that dynamically selects the smallest set of most likely words whose cumulative probability exceeds a threshold `p`.

### The Big Picture:
Top-p Sampling is the **adaptive filter** for text generation. Unlike top-k's fixed number, it adjusts the candidate pool size based on the probability distribution, making it more flexible and context-aware.

### How it Works (The Core Idea):
At each generation step:
1.  Sort all words by descending probability
2.  Start from the top, adding words until the cumulative probability > `p`
3.  Sample only from this "nucleus" of words
4.  Discard all other low-probability words

### Why it Matters:
It's more dynamic than top-k—when the model is confident, the nucleus is small; when uncertain, it considers more options. This leads to more natural and context-appropriate variations.

### A Simple Analogy:
**Shopping with a budget vs. a shopping list.**
*   **Top-k:** Buy exactly 5 items from your list, regardless of price.
*   **Top-p:** Spend up to $100, buying as many items as fit within your budget. If items are cheap, you get more variety; if expensive, you get fewer but high-quality picks.

### Real-World Examples:
*   **GPT-3** often uses top-p with p=0.9 as default.
*   **Creative writing** where you want adaptive creativity based on context.
*   **Dialogue systems** for more natural, less repetitive conversations.

---
*🌳 **Parent Branch:** [[Natural Language Processing]]
*🎯 **A Decoding Strategy:** More adaptive than [[Top-k Sampling]].
*⚡ **The Advantage:** **Dynamic candidate pool** based on confidence.
*🔗 **Often Used With:** [[Temperature]] for fine-grained control.
