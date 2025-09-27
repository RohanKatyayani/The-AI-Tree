# ReAct Framework (Reasoning + Acting)

### One-Liner:
*   **What it is:** A popular framework for building AI agents that interleaves *chain-of-thought reasoning* with *actions* to solve complex tasks.

### The Big Picture:
ReAct is a foundational **leaf** on the **AI Agents** branch. It provides a structured way to combine an LLM's reasoning capabilities with the ability to use tools, creating a transparent and effective problem-solving loop.

### How it Works (The Core Idea):
The model is prompted to generate steps that alternate between two types:
1.  **Reasoning (Thought):** The agent thinks out loud about the current situation, what it knows, and what it should do next. This is like internal monologue.
2.  **Acting (Action):** The agent takes a concrete step by using a tool (e.g., `SearchWeb(question)`, `Calculate(expression)`).

### Why it Matters:
It makes the agent's decision-making process transparent and reliable. By forcing the agent to "think step-by-step" before acting, it reduces hallucinations and improves the ability to handle complex, multi-step problems.

### A Simple Analogy:
**A detective solving a case.**
*   **Reasoning (Thought):** "The victim was found in the library. I should look for fingerprints near the desk and check the logbook to see who entered last."
*   **Acting (Action):** The detective *dusts for fingerprints* (uses a tool) and *checks the logbook* (uses another tool).
*   The detective then *reasons* about the new evidence and takes the next *action*.

### Real-World Examples:
*   An agent answering, "What was the weather in Tokyo on the day the last Olympics opened?"
    *   **Thought:** "I need to find the opening date of the last Olympics, then get the weather for Tokyo on that date."
    *   **Action:** `SearchWeb("When did the last Olympics open?")`
    *   **Observation:** "July 23, 2021."
    *   **Thought:** "Now I need the weather in Tokyo on July 23, 2021."
    *   **Action:** `GetWeather("Tokyo", "2021-07-23")`
*   **Coding agents** that reason about a bug before writing the fix.

---
*🌳 **Parent Branch:** [[AI Agents Overview]]
*🧠 **The Core Idea:** **Interleaving** reasoning traces with actions.
*🔧 **Implements:** The core **Plan-Act-Observe** loop.
*👁️ **Key Benefit:** **Transparency** - you can see the agent's "thought process."
