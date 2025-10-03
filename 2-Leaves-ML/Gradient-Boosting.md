# Gradient Boosting

### One-Liner:
*   **What it is:** An ensemble technique that builds models sequentially, where each new model corrects the errors made by the previous ones.

### The Big Picture:
Gradient Boosting is the **persistent learner** of ensemble methods. Instead of independent models voting, it creates a team where each new member specializes in fixing the specific mistakes the team has been making so far.

### How it Works (The Core Idea):
1.  **Start Simple:** Train a weak model (like a shallow decision tree).
2.  **Calculate Errors:** See where this model makes mistakes.
3.  **Build Corrector:** Train a new model specifically to predict these errors.
4.  **Combine:** Add the corrector to the ensemble.
5.  **Repeat:** Keep adding models that fix the remaining errors.

### Why it Matters:
It often achieves state-of-the-art performance on tabular data and is the foundation for popular libraries like XGBoost, LightGBM, and CatBoost.

### A Simple Analogy:
**A student studying for an exam by focusing on weaknesses.**
*   **Week 1:** Takes a practice test, does okay but makes some errors.
*   **Week 2:** Studies specifically the topics they got wrong.
*   **Week 3:** Takes another test, focuses on the new errors.
*   **Final:** After many rounds of targeted improvement, they ace the exam!
*   Each study session (model) specifically addresses previous weaknesses (errors).

### Real-World Examples:
*   **XGBoost** winning numerous Kaggle competitions.
*   **Search engine ranking** algorithms that learn from user clicks.
*   **Fraud detection** systems that continuously adapt to new patterns.

---
*🌳 **Parent Concept:** A specific [[Ensemble Methods]] technique.
*📈 **The Strategy:** **Sequential learning** from errors.
*🎯 **The Focus:** Each model corrects **residual errors** from previous ones.
*🚀 **The Result:** Often achieves **very high accuracy** on structured data.
