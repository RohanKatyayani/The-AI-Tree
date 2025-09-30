# Context Window

### One-Liner:
*   **What it is:** The fixed amount of text (measured in tokens) that a large language model can process and remember in a single interaction.

### The Big Picture:
The Context Window is the **working memory** or "short-term memory" of an LLM. It defines the boundaries within which [[In-Context Learning]] happens. Everything outside this window is forgotten by the model.

### How it Works (The Core Idea):
When you send a prompt to an LLM, the model can only "see" and process the most recent tokens up to its context limit. This includes:
*   Your system instructions
*   Few-shot examples
*   Conversation history
*   The current query
Once the context window is full, older tokens are "forgotten" to make room for new ones.

### Why it Matters:
The size of the context window determines how much information you can provide to guide the model and how long a conversation can continue coherently. It's a fundamental constraint in LLM design and usage.

### A Simple Analogy:
**A whiteboard in a meeting room.**
*   The **context window** is the physical size of the whiteboard.
*   **In-Context Learning** is the discussion that happens based on what's written on the whiteboard.
*   When the whiteboard fills up, you have to erase older notes to make space for new ideas. The meeting can only reference what's currently visible on the board.

### Real-World Examples:
*   **GPT-4** originally had a 8k token context window (~6,000 words), later expanded to 32k and 128k in newer models.
*   When having a long conversation with ChatGPT, it might "forget" what you discussed at the very beginning if the conversation exceeds its context window.
*   Processing long documents requires splitting them into chunks that fit within the context window.

---
*🌳 **Parent Branch:** [[Natural Language Processing]]
*🧠 **The Constraint:** Limits the scope of [[In-Context Learning]].
*📏 **Measured In:** **Tokens** (not words or characters).
*⚡ **A Key Spec:** When choosing an LLM for a task.
*🔗 **Related Challenge:** [[Context Management]] for long conversations.
