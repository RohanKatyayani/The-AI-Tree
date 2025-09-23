# Few-Shot Learning

### One-Liner:
*   **What it is:** A technique where a large language model is given a few examples of a new task within its prompt, enabling it to understand and perform the task without any additional training.

### The Big Picture:
Few-Shot Learning is a powerful **leaf** on the **NLP** branch that demonstrates the remarkable "meta-learning" ability of LLMs. It allows us to teach the model new tricks on the fly, simply by showing it a few examples.

### How it Works (The Core Idea):
Instead of fine-tuning the model's weights, you provide a few input-output pairs (the "shots") as part of the prompt. The model recognizes the pattern from these examples and generalizes it to complete a new, similar input.

### Why it Matters:
It makes LLMs incredibly flexible and adaptable. It drastically reduces the need for collecting large datasets and performing computationally expensive fine-tuning for every new task.

### A Simple Analogy:
**Giving someone a new board game.**
*   **Zero-Shot:** You just tell them the goal: "Get your pieces to the other side." They have to guess the rules.
*   **Few-Shot:** You play two complete example turns, showing them what a move looks like. After seeing the examples, they can understand the pattern and play the game correctly.
*   The person (the LLM) learns the rules from the examples in the prompt.

### Real-World Examples:
*   **Teaching a new format:** 
    *   *Example 1 Input:* "I loved the movie! -> Sentiment: Positive"
    *   *Example 2 Input:* "It was boring. -> Sentiment: Negative"
    *   *New Input:* "The acting was great but the plot was weak. ->" (The model infers it should output "Sentiment: Neutral/Mixed")
*   **Translating between rare languages:** Providing a few example sentences.
*   **Classifying text:** Giving examples of emails labeled as "Spam" or "Not Spam".

---
*🌳 **Parent Branch:** [[Natural Language Processing]]
*🤖 **A Technique For:** Rapidly adapting [[Large Language Models]] to new tasks.
*🎯 **The Key:** Providing **examples in the prompt**.
*🚀 **An Alternative To:** Full [[Fine-Tuning]] for simple tasks.
*🔢 **Variants:** **One-Shot Learning** (one example) and **Zero-Shot Learning** (no examples, just instructions).
