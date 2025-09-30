# One-Shot Learning

### One-Liner:
*   **What it is:** A technique where a model learns to perform a new task after being shown only *a single example* within its prompt.

### The Big Picture:
One-Shot Learning sits perfectly between **Zero-Shot** and **Few-Shot** learning. It provides just enough context to guide the model's understanding while remaining extremely efficient with examples.

### How it Works (The Core Idea):
You structure your prompt with:
1.  **Task Description:** What you want the model to do.
2.  **One Example:** A single input-output pair demonstrating the task.
3.  **Test Input:** The actual question or input you want an answer for.

The model uses this single example to understand the pattern and apply it to the new input.

### Why it Matters:
It's often the sweet spot where you get significant improvement over zero-shot with minimal example overhead. Many practical applications use one-shot learning when you have very limited labeled data.

### A Simple Analogy:
**Showing someone one example of a completed form.**
*   You show them: 
    - Input: "Name: John Doe, Age: 30" → Output: "Applicant: John Doe (30 years old)"
*   Then you give: "Name: Jane Smith, Age: 25"
*   Using **one-shot learning**, they can now output: "Applicant: Jane Smith (25 years old)"

### Real-World Examples:
*   **Data Formatting:** Showing one example of how to convert dates from "MM/DD/YYYY" to "YYYY-MM-DD" format.
*   **Text Rewriting:** Providing one example of formalizing informal text, then having the model formalize new text.
*   **Code Translation:** Showing one example of converting Python to JavaScript, then asking for another conversion.

---
*🌳 **Parent Branch:** [[Natural Language Processing]]
*🎯 **Position:** Between [[Zero-Shot Learning]] (0 examples) and [[Few-Shot Learning]] (2+ examples).
*💡 **The Sweet Spot:** Often provides the biggest improvement for the least examples.
*🤖 **Leverages:** The model's strong pattern recognition from pre-training.
