# Inference

### One-Liner:
*   **What it is:** The process of using a trained machine learning model to make predictions on new, unseen data.

### The Big Picture:
Inference is the **final goal** of the entire ML process. Training is like studying for a final exam; inference is like actually taking the exam and using your knowledge to solve problems.

### How it Works (The Core Idea):
Once a model is fully trained (its parameters are fixed), it is deployed into an application. When you give it new input (e.g., a new photo, a question, a sensor reading), it runs a **forward pass** through its network to generate an output (a prediction, an answer, a classification). This is usually much faster than training.

### Why it Matters:
This is the step that provides value. Every time you ask ChatGPT a question, use a face unlock feature, or get a recommendation on Netflix, you are seeing a model performing inference in real-time.

### A Simple Analogy:
A trained chef (the model) standing in a restaurant kitchen. 
*   **Training** was their years of culinary school and practice.
*   **Inference** is what happens when you, a customer, order a dish. The chef uses their frozen knowledge (the trained model) to quickly prepare your specific meal (the prediction).

### Real-World Examples:
*   **ChatGPT** generating a response to your message.
*   **Your phone's camera** recognizing a face in the viewfinder.
*   **A self-driving car** identifying a stop sign in real-time.

---
*🌳 **Core Concept:** The essential final step of the [[Machine Learning]] workflow.
*🔄 **The Other Half:** The process that comes before inference is [[Training]].
