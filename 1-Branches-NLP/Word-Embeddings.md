# Word Embeddings

### One-Liner:
*   **What it is:** A technique to represent words as lists of numbers (vectors) in a way that captures their meaning and relationships.

### The Big Picture:
Word Embeddings are how we give words **meaning** for computers. They are a fundamental building block that allows models to understand that "king" is to "queen" as "man" is to "woman."

### How it Works (The Core Idea):
Words are mapped to high-dimensional vectors (e.g., a list of 300 numbers). The position of this vector in space is learned from lots of text. Words with similar meanings end up close to each other in this vector space.

### Why it Matters:
They allow neural networks to work with language by providing a numerical representation that contains semantic information, not just a random ID.

### A Simple Analogy:
Imagine plotting words on a map. The *meaning* of the word is its GPS coordinate. Words like "puppy" and "kitten" would be plotted very close together, while "puppy" and "skyscraper" would be far apart. Word embeddings create this "map of meaning."

### Real-World Examples:
*   The underlying reason autocorrect knows "happy" is more like "joyful" than "sad."
*   How recommendation systems understand that "laptop" and "computer" are similar terms.

---
*🌳 **Parent Branch:** [[Natural Language Processing]]*
*🔍 **See Next:** This concept is used in models like [[Recurrent Neural Networks]] and [[Transformers]].*
