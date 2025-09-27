# Agent Memory

### One-Liner:
*   **What it is:** The component of an AI agent that allows it to retain and recall information across interactions, enabling long-term context and learning.

### The Big Picture:
Agent Memory is the **long-term memory** of an AI agent. It's what transforms a single-turn helper into a persistent, personalized assistant that learns from past interactions and maintains context over long conversations or tasks.

### How it Works (The Core Idea):
Memory can be implemented in different ways:
*   **Short-term Memory:** The context window of the LLM, which remembers the immediate conversation.
*   **Long-term Memory:** An external database (often a vector database) that stores summaries or key facts from past interactions. The agent can query this database for relevant information when starting a new task.

### Why it Matters:
Without memory, every interaction with an agent starts from scratch. With memory, an agent can build a relationship with a user, remember their preferences, and learn from past mistakes, making it vastly more efficient and helpful.

### A Simple Analogy:
**A new employee vs. a seasoned veteran.**
*   An agent **without memory** is like a new employee on their first day. They need to be told everything about the company, the project, and your preferences every single time you talk to them.
*   An agent **with memory** is like a veteran employee who has worked with you for years. They remember how you like reports formatted, the history of past projects, and the lessons learned from previous successes and failures.

### Real-World Examples:
*   A **personal AI assistant** that remembers you prefer morning meetings and that you're allergic to shellfish when making restaurant reservations.
*   A **coding agent** that remembers the architecture decisions and bug fixes from a long-running software project.
*   A **customer service agent** that recalls a user's previous support tickets and their resolution.

---
*🌳 **Parent Branch:** [[AI Agents Overview]]
*💾 **The Mechanism:** Often uses **vector databases** to store and retrieve information efficiently.
*📚 **Types of Memory:** Includes **Conversation Memory**, **Entity Memory** (remembering facts about people/things), and **Procedural Memory** (remembering how to do tasks).
*🧠 **Enables:** **Continuous learning** and **personalization**.
