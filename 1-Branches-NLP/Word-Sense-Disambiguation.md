# Word Sense Disambiguation (WSD)

### One-Liner:
*   **What it is:** The ability of an NLP model to identify which meaning of a word is being used in a sentence, based on the context.

### The Big Picture:
Word Sense Disambiguation is a fundamental **leaf** on the **NLP** branch that deals with the ambiguity of language. It's a key step towards true language understanding, as words can have multiple meanings (polysemy).

### How it Works (The Core Idea):
The model analyzes the surrounding words in a sentence to determine the correct sense of an ambiguous word. Modern systems often use the context from large language models or knowledge graphs to make this decision.

### Why it Matters:
Without WSD, machines would struggle with the nuances of human language. For example, a search for "apple fruit" might return results about Apple Inc. if the word "apple" isn't disambiguated correctly.

### A Simple Analogy:
**Understanding puns or jokes.**
*   The word "bank" can mean a financial institution or the side of a river.
*   In the sentence "I went to the bank to get money," a human easily understands it's the financial institution.
*   WSD is the process of teaching a machine to make that same distinction based on the words "get money."

### Real-World Examples:
*   **Search Engines:** Providing relevant results by understanding if a query for "python" is about the snake or the programming language.
*   **Machine Translation:** Choosing the correct translation for a word. The English word "light" could be translated differently in "light weight" (léger) vs. "light bulb" (lumière) in French.
*   **Voice Assistants:** Understanding commands like "play me a light song" (not heavy) vs. "turn on the light" (lamp).

---
*🌳 **Parent Branch:** [[Natural Language Processing]]
*🔤 **Deals With:** The problem of [[Ambiguity]] in language.
*🧠 **Relies On:** Understanding [[Context]] in a sentence.
*🤖 **Solved By:** Modern [[Large Language Models]] are very good at this implicitly.
