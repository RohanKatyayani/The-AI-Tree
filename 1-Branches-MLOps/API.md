# API (Application Programming Interface)

### One-Liner:
*   **What it is:** A set of rules and protocols that allows different software applications to communicate with each other.

### The Big Picture:
In MLOps, an API is the **waitstaff** of a restaurant. It's the interface that takes orders from customers (other applications or users), relays them to the kitchen (your ML model), and then delivers the finished meal (the prediction) back to the customer.

### How it Works (The Core Idea):
For ML, a **Web API** (often a REST API) is created around a trained model. Other programs send a request to a specific URL (an "endpoint") containing input data. The API passes this data to the model, gets the prediction, and sends it back as a response (usually in JSON format).

### Why it Matters:
It's the standard way to integrate an ML model into any application—a website, a mobile app, or another service. It abstracts away the complexity of the model, allowing any system that can send an HTTP request to use its intelligence.

### A Simple Analogy:
**A restaurant's ordering system.**
*   The **Menu** is the API documentation, listing what you can order (the available endpoints).
*   You (the client application) give your **order** (a request) to the **waiter** (the API).
*   The waiter takes it to the **kitchen** (the ML model).
*   The kitchen prepares the food (the prediction) and gives it to the waiter.
*   The waiter brings the **finished dish** (the response) back to you.

### Real-World Examples:
*   A weather app sending your location to a weather prediction model's API and receiving the forecast.
*   A website using a sentiment analysis API to filter out toxic comments.
*   A mobile bank app using a fraud detection API to check a transaction in real-time.

---
*🌳 **Parent Branch:** [[MLOps Overview]]
*🌐 **The Standard:** **REST API** is the most common type for web services.
*🚪 **The Gateway:** How the outside world accesses a deployed model for [[Inference]].
*🔌 **Enables Integration:** Connects ML models to websites, apps, and other services.
