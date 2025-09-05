# Tokenization

### One-Liner:
*   **What it is:** The very first step in NLP: breaking down text into smaller pieces, like words or subwords, called "tokens."

### The Big Picture:
Tokenization is the **foundation** of all NLP. Before a computer can understand text, it must break it into pieces it can process. It's the first thing that happens to any text you give to an LLM.

### How it Works (The Core Idea):
A tokenizer goes through a string of text and splits it. This can be as simple as splitting by spaces ("hello world" -> ["hello", "world"]) or more complex, handling punctuation and rare words by breaking them into subwords ("unhappily" -> ["un", "happi", "ly"]).

### Why it Matters:
Computers don't understand words; they understand numbers. Tokenization converts words into tokens, which are then converted into numbers (IDs) that the model can use. It's like translating a book into a language the computer knows.

### A Simple Analogy:
Imagine you have a long Lego model (a sentence). Tokenization is the process of carefully breaking it back down into individual Lego blocks (tokens) so you can analyze and reassemble it.

### Real-World Examples:
*   The first thing ChatGPT does when you send a message.
*   How a search engine processes your query.
*   How your phone's keyboard suggests the next word.

---
*🌳 **Parent Branch:** [[Natural Language Processing]]*
