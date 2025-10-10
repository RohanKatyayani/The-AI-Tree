# DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

### One-Liner:
*   **What it is:** A density-based clustering algorithm that groups together closely packed points and marks outliers in low-density regions.

### The Big Picture:
DBSCAN is the **shape detector** of clustering algorithms. Instead of assuming spherical clusters like K-Means, it finds clusters of arbitrary shapes based on data density.

### How it Works (The Core Idea):
DBSCAN uses two parameters:
1.  **eps (ε):** The maximum distance between two points to be considered neighbors
2.  **min_samples:** The minimum number of points to form a dense region
It classifies points as:
- **Core points:** Have enough neighbors within eps distance
- **Border points:** Within eps of a core point but lack enough neighbors
- **Noise points:** Neither core nor border points

### Why it Matters:
It can find complex cluster shapes, doesn't require specifying the number of clusters, and naturally handles outliers as noise.

### A Simple Analogy:
**Finding star constellations in the night sky.**
*   **Stars close together** form constellations (clusters)
*   **Isolated stars** are noise or background
*   **Constellations** can have any shape - animals, objects, patterns
*   You don't need to know how many constellations there are in advance!
*   DBSCAN naturally finds these dense star groupings.

### Real-World Examples:
*   **Geography:** Identifying urban areas vs. rural areas based on population density.
*   **Astronomy:** Finding star clusters and galaxies in spatial data.
*   **Anomaly Detection:** Identifying fraudulent transactions as noise points.

---
*🌳 **Parent Concept:** A specific [[Clustering]] technique.
*🎯 **The Approach:** **Density-based** clustering.
*🌟 **The Advantage:** Finds **arbitrary shapes** and handles **noise**.
*⚙️ **The Parameters:** **eps** and **min_samples** control density sensitivity.
