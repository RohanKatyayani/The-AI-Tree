# Convolutional Neural Networks (CNNs / ConvNets)

### One-Liner:
*   **What it is:** A special type of neural network that is incredibly powerful for processing images by looking for patterns in small sections at a time.

### The Big Picture:
CNNs are the **Transformers of the visual world.** They are the foundational architecture for almost all modern computer vision tasks, just like Transformers are for language. They are the first major branch on the Computer Vision limb of the AI tree.

### How it Works (The Core Idea):
Instead of looking at an entire image all at once (which would be overwhelming), a CNN uses tiny sliding windows called "filters" or "kernels" to scan the image piece-by-piece. Each filter is designed to detect a specific pattern, like an edge, a corner, or a texture. The results from these filters are combined in deeper layers to detect more complex patterns like eyes, noses, and eventually entire faces.

### Why it Matters:
They revolutionized computer vision by automatically learning the best features to look for in an image, eliminating the need for humans to manually define what things like "edges" or "curves" are. They are highly efficient and accurate.

### A Simple Analogy:
Imagine you're identifying a dog in a photo. You don't just glance at the whole picture and know it's a dog. Your brain might first subconsciously notice:
*   **Layer 1:** Fuzzy textures, vertical lines (like legs), round shapes.
*   **Layer 2:** Paw shapes, snout shapes, fur patterns.
*   **Final Layer:** Combines all these to say "Ah, that's a dog!"
A CNN works the same way, in layers.

### Real-World Examples:
*   **Facebook's photo auto-tagging.**
*   **Self-driving cars** identifying pedestrians and street signs.
*   **Medical AI** analyzing X-rays and MRI scans for diseases.

---
*🌳 **Parent Branch:** [[Computer Vision]]*
*🔍 **See Also:** The equivalent architecture for language is the [[Transformers|Transformer]].
