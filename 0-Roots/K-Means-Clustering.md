# K-Means Clustering

### One-Liner:
*   **What it is:** A centroid-based clustering algorithm that partitions data into K distinct clusters based on distance to cluster centers.

### The Big Picture:
K-Means is the **prototype finder** of clustering algorithms. It works by iteratively refining cluster centers (centroids) until they best represent the natural groupings in the data.

### How it Works (The Core Idea):
The algorithm follows a simple iterative process:
1.  **Initialize:** Randomly place K centroids in the data space
2.  **Assign:** Assign each point to its nearest centroid
3.  **Update:** Move centroids to the mean of their assigned points
4.  **Repeat** steps 2-3 until convergence

### Why it Matters:
It's simple, fast, and intuitive. While it has limitations, it's often the first algorithm people learn for clustering and works well for many practical applications.

### A Simple Analogy:
**Organizing conference attendees into discussion groups.**
*   You start with empty tables (centroids) around the room
*   People sit at the nearest table (assignment)
*   You move tables to the center of each group (update)
*   Some people change tables as tables move
*   Eventually, tables settle and natural discussion groups form!

### Real-World Examples:
*   **Market Segmentation:** Grouping customers by purchasing patterns
*   **Image Compression:** Reducing colors by clustering similar pixels
*   **Document Clustering:** Grouping articles by topic similarity

---
*🌳 **Parent Concept:** A specific [[Clustering]] technique.
*🎯 **The Approach:** **Centroid-based** partitioning.
*⚡ **The Advantage:** **Simple** and **fast** for large datasets.
*⚠️ **The Limitation:** Requires specifying **K** and assumes **spherical clusters**.
