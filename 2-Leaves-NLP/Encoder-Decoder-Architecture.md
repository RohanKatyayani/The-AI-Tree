# Encoder-Decoder Architecture

### One-Liner:
*   **What it is:** A fundamental neural network design where one component (the encoder) processes the input into a condensed representation, and a second component (the decoder) uses that representation to generate the output.

### The Big Picture:
The Encoder-Decoder is a versatile and powerful **architectural pattern** that is the backbone for sequence-to-sequence tasks. It's the foundation for models that *transform* one piece of data into another, like translation or summarization.

### How it Works (The Core Idea):
1.  **Encoder:** Takes the input sequence (e.g., an English sentence) and processes it into a context-rich, fixed-size internal representation (often called a "context vector").
2.  **Decoder:** Takes this context vector and generates the output sequence (e.g., the French translation) step-by-step.

### Why it Matters:
It elegantly solves the problem of mapping sequences of different lengths. It was the dominant architecture for tasks like machine translation before the rise of the "encoder-only" (e.g., BERT) and "decoder-only" (e.g., GPT) models, and it's still crucial for many applications.

### A Simple Analogy:
**A human translator working with notes.**
*   The **Encoder** is like the translator reading the entire original English paragraph and jotting down the core ideas and meaning in their own concise notes (the context vector).
*   The **Decoder** is like the translator then using those notes to reconstruct the full meaning in French, ensuring the essence is preserved without a word-for-word translation.

### Real-World Examples:
*   **Machine Translation:** Google Translate's original sequence-to-sequence models.
*   **Text Summarization:** Taking a long article and generating a short summary.
*   **Question Answering:** Processing a question and a context passage to generate an answer.

---
*🌳 **Parent Branch:** [[Natural Language Processing]]
*🧩 **A Foundational Pattern:** Pre-dates and inspires the [[Transformers]] architecture.
*🔀 **For Sequence-to-Sequence Tasks:** Maps an input sequence to an output sequence.
*📚 **Famous Models:** The original **Transformer** model is an encoder-decoder architecture. **T5** and **BART** are modern examples.
