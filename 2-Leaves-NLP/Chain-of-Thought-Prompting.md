# Chain-of-Thought (CoT) Prompting

### One-Liner:
*   **What it is:** A prompting technique that encourages an LLM to solve a complex problem by breaking it down into a sequence of intermediate reasoning steps, just like a person would.

### The Big Picture:
Chain-of-Thought is a powerful **leaf** on the **NLP** branch that unlocks more advanced reasoning in Large Language Models. It doesn't change the model itself; it changes how we *talk* to it to get better answers.

### How it Works (The Core Idea):
Instead of asking the model for a direct answer, you prompt it to "think step by step." This forces the model to articulate its internal reasoning process, which often leads to more accurate final answers, especially for arithmetic, logic, or commonsense problems.

### Why it Matters:
It significantly improves an LLM's ability to perform complex reasoning tasks. By externalizing the thought process, it also makes the model's "thinking" more transparent and easier to debug.

### A Simple Analogy:
**Asking a student to show their work on a math test.**
*   **Direct Prompting:** "What is 154 * 23?" The student might guess or make a calculation error.
*   **Chain-of-Thought Prompting:** "What is 154 * 23? Let's think step by step: First, 150 * 20 = 3000. Then, 150 * 3 = 450. Then 4 * 23 = 92. Now add them up: 3000 + 450 = 3450, plus 92 is 3542."
Showing the steps reduces mistakes and reveals the student's understanding.

### Real-World Examples:
*   **Solving word problems:** "If a farmer has 15 chickens and each chicken lays 4 eggs a week, how many eggs does he get in 3 weeks?" (CoT forces the model to calculate 15*4=60 eggs/week, then 60*3=180 eggs).
*   **Complex planning:** Breaking down a recipe into a sequence of steps.
*   **Logical puzzles:** Solving riddles by reasoning through possibilities.

---
*🌳 **Parent Branch:** [[Natural Language Processing]]
*🤖 **A Technique For:** Enhancing the reasoning of [[Large Language Models]].
*🗣️ **A Type Of:** Advanced [[Prompt Engineering]].
*➡️ **An Extension:** Can be combined with **Few-Shot Learning** by providing examples of reasoning steps.
