# Object Detection

### One-Liner:
*   **What it is:** A computer vision task that involves both locating (where is it?) and identifying (what is it?) multiple objects within an image or video.

### The Big Picture:
Object Detection is a major **leaf** on the **Computer Vision** branch. It goes beyond simple image classification (which just labels the whole image) to provide a much richer understanding of a scene by drawing boxes around objects and naming them.

### How it Works (The Core Idea):
An object detection model, often based on a CNN, scans an image and predicts two things for each object it finds:
1.  **Bounding Box:** The (x, y) coordinates of a rectangle that tightly surrounds the object.
2.  **Class Label:** What the object inside the box is (e.g., "person", "car", "dog").

### Why it Matters:
It's crucial for any application where a machine needs to interact with or understand a complex visual environment. It's the eyes for robots, self-driving cars, and automated systems.

### A Simple Analogy:
Imagine you're looking at a family photo.
*   **Image Classification** would just say: "This is a photo of a family."
*   **Object Detection** would say: "There is a *woman* at position (x1, y1), a *man* at (x2, y2), a *baby* at (x3, y3), and a *dog* at (x4, y4)." It gives a detailed breakdown.

### Real-World Examples:
*   **Self-driving cars** detecting pedestrians, other cars, and traffic signs in real-time.
*   **Security systems** identifying intruders or suspicious packages.
*   **Retail stores** tracking inventory by counting products on shelves.

---
*🌳 **Parent Branch:** [[Computer Vision]]
*🔧 **Built Using:** Architectures like [[Convolutional-Neural-Networks]] and techniques like [[Transfer Learning]].
*👁️ **The Simpler Task:** Compared to [[Image Classification]] which only identifies, not locates.
*🧠 **The More Complex Task:** A step towards [[Image Segmentation]] which finds exact outlines, not just boxes.
