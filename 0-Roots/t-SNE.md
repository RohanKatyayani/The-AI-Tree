# t-SNE (t-Distributed Stochastic Neighbor Embedding)

### One-Liner:
*   **What it is:** A nonlinear dimensionality reduction technique particularly well-suited for visualizing high-dimensional data by preserving local neighborhoods and clusters.

### The Big Picture:
t-SNE is the **neighborhood preserver** of dimensionality reduction. While PCA focuses on global variance, t-SNE excels at keeping similar data points close together in the lower-dimensional representation, making clusters and patterns visually apparent.

### How it Works (The Core Idea):
t-SNE works in two main steps:
1.  **High-dimensional space:** Computes probabilities that represent pairwise similarities between points.
2.  **Low-dimensional space:** Tries to recreate these similarity probabilities using a Student-t distribution (which has heavier tails, helping to separate clusters).

### Why it Matters:
It produces stunning visualizations that reveal natural clusters and patterns in complex data that other methods might miss. It's revolutionized how we explore high-dimensional datasets.

### A Simple Analogy:
**Mapping a social network for a party.**
*   **High Dimension:** Everyone's complex relationships and interactions.
*   **t-SNE:** Arranging people in a room so that:
    - Close friends stand near each other (local neighborhoods preserved)
    - Different friend groups form visible clusters
    - The overall layout might not preserve exact distances between groups, but within-group relationships are perfect.
*   You can instantly see who belongs together!

### Real-World Examples:
*   **MNIST digit visualization:** Seeing how handwritten digits naturally cluster by number.
*   **Word embeddings:** Visualizing how similar words cluster in semantic space.
*   **Single-cell RNA sequencing:** Identifying cell types from gene expression patterns.

---
*🌳 **Parent Concept:** A specific [[Dimensionality Reduction]] technique.
*🏘️ **The Focus:** **Local neighborhood preservation**.
*🎨 **The Strength:** **Beautiful cluster visualizations**.
*⚠️ **The Caveat:** **Global structure** may not be preserved.
