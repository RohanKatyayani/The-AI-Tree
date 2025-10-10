# Hierarchical Clustering

### One-Liner:
*   **What it is:** A clustering approach that builds a tree of clusters, showing relationships at multiple levels of granularity.

### The Big Picture:
Hierarchical Clustering is the **family tree builder** of clustering algorithms. Instead of creating flat groups, it creates a dendrogram (tree diagram) that shows how clusters merge and split at different similarity levels.

### How it Works (The Core Idea):
There are two main approaches:
1.  **Agglomerative (Bottom-up):** Start with each point as its own cluster, then repeatedly merge the closest clusters.
2.  **Divisive (Top-down):** Start with all points in one cluster, then recursively split them.

### Why it Matters:
It doesn't require specifying the number of clusters in advance and provides a rich, multi-scale view of the data structure.

### A Simple Analogy:
**Building a corporate organization chart.**
*   **Individual employees** are at the bottom
*   They form **teams** (small clusters)
*   Teams form **departments** (larger clusters)
*   Departments form **divisions** (even larger clusters)
*   The CEO is at the very top (one big cluster)
*   You can choose to view the organization at any level of detail!

### Real-World Examples:
*   **Biology:** Building phylogenetic trees of species evolution.
*   **Document analysis:** Creating topic hierarchies from large text corpora.
*   **Social networks:** Discovering community structures at different scales.

---
*🌳 **Parent Concept:** A specific [[Clustering]] technique.
*🌳 **The Structure:** **Tree-like hierarchy** of clusters (dendrogram).
*🔍 **The Advantage:** **No need to specify K** - view clusters at multiple levels.
*📊 **The Result:** **Rich visual representation** of data relationships.
