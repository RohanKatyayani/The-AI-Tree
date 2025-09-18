# Evaluation Metrics

### One-Liner:
*   **What it is:** Standard measures used to evaluate the performance and quality of a trained machine learning model on unseen data.

### The Big Picture:
Evaluation Metrics are the **final exam** for a model. While a Loss Function is used *during* training to guide the algorithm, evaluation metrics are used *after* training to objectively score how well the model actually performs its task.

### How it Works (The Core Idea):
After a model is trained, it is tested on a holdout dataset it has never seen before (the test set). Evaluation metrics are calculated by comparing the model's predictions on this test set to the known, true values.

### Why it Matters:
They provide an unbiased estimate of how the model will perform in the real world. They help compare different models and ensure they meet the required performance standards before deployment.

### A Simple Analogy:
**Grading a student's knowledge.**
*   **Training/Loss Function:** is like the student doing practice problems and getting immediate feedback from a tutor (gradient descent).
*   **Evaluation Metrics:** are like the final proctored exam. The practice scores don't matter; only the exam grade (e.g., 95% correct) objectively measures their understanding.

### Common Metrics & Examples:
*   **For Regression:** 
    *   **Mean Absolute Error (MAE):** The average absolute difference between predictions and true values.
    *   **R-squared (R²):** The proportion of variance in the target explained by the model.
*   **For Classification:**
    *   **Accuracy:** The percentage of correct predictions.
    *   **Precision & Recall:** Crucial for imbalanced datasets (e.g., fraud detection).

---
*🌳 **The Report Card:** Used after [[Training]] to assess model quality.
*🧪 **Requires:** A held-out [[Test Set]] of data.
*📈 **Related To:** The [[Loss Function]] is used during training, while metrics are used after.
