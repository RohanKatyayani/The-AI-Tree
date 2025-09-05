# Recurrent Neural Networks (RNNs)

### One-Liner:
*   **What it is:** A type of neural network designed to work with sequences of data (like text or time series) by having a "memory" of previous inputs.

### The Big Picture:
RNNs were the king of NLP before the Transformer architecture was invented. They were the first major step towards models that could understand the context and order of words in a sentence.

### How it Works (The Core Idea):
An RNN processes data one step at a time and maintains a "hidden state" that acts as its memory of what it has seen so far in the sequence. The output for the next word depends on the current input *and* this hidden state from the previous word.

### Why it Matters:
They were groundbreaking for tasks like machine translation, text generation, and speech recognition because they could handle inputs and outputs of varying lengths and understand order.

### A Simple Analogy:
Reading a book. You don't understand a sentence on page 10 by itself; you understand it based on your memory of what happened on pages 1-9. An RNN tries to do the same thing, building understanding word-by-word.

### Real-World Examples:
*   The original Google Translate used a type of RNN.
*   Early chatbots and text autocompleters.

---
*🌳 **Parent Branch:** [[Natural Language Processing]]*
*🔍 **See Next:** The architecture that largely replaced RNNs for most tasks: the [[Transformers|Transformer]].*
