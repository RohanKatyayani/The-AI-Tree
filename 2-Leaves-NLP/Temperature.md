# Temperature

### One-Liner:
*   **What it is:** A parameter that controls the randomness and creativity of a language model's outputs by adjusting how it samples from predicted probabilities.

### The Big Picture:
Temperature is the **creativity dial** for LLMs. It determines whether the model plays it safe with predictable responses or takes risks with more diverse and creative ones.

### How it Works (The Core Idea):
Temperature scales the model's output probabilities before sampling:
*   **Low Temperature (<1.0):** Amplifies high-probability words, making outputs more deterministic and focused.
*   **High Temperature (>1.0):** Flattens the probability distribution, making low-probability words more likely and outputs more random/creative.

### Why it Matters:
It's essential for tuning model behavior for different use cases—factual responses need low temp, creative writing needs high temp.

### A Simple Analogy:
**A chef following a recipe vs. improvising.**
*   **Low Temp (0.2):** Follows the recipe exactly—predictable, consistent results.
*   **Medium Temp (0.7):** Adds personal touches—balanced creativity.
*   **High Temp (1.5):** Throws out the recipe and experiments—wildly creative but risky.

### Real-World Examples:
*   **Code Generation:** Low temperature for reliable, working code.
*   **Creative Writing:** High temperature for novel story ideas.
*   **Chatbots:** Medium temperature for natural but coherent conversation.

---
*🌳 **Parent Branch:** [[Natural Language Processing]]
*🎛️ **A Key Parameter:** For controlling [[Large Language Models]] output.
*⚖️ **The Trade-off:** **Consistency** vs. **Creativity**.
*🔧 **Practical Range:** Typically 0.1 to 1.5.
