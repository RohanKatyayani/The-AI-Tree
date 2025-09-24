# Kubernetes (K8s)

### One-Liner:
*   **What it is:** An open-source system for automating the deployment, scaling, and management of containerized applications.

### The Big Picture:
Kubernetes is the **autopilot and traffic controller** for a fleet of Docker containers. If Docker is the shipping container, Kubernetes is the fully automated port system that manages thousands of ships, cranes, and trucks to ensure goods are delivered efficiently and reliably.

### How it Works (The Core Idea):
You define a desired state for your application (e.g., "I want 3 instances of my model API running at all times"). Kubernetes constantly monitors the system and automatically works to maintain that state. If a container crashes, it restarts it. If traffic increases, it can scale up the number of containers.

### Why it Matters:
It's the industry standard for deploying complex, scalable applications, including ML model services. It handles the complexity of managing many microservices, making systems resilient and efficient.

### A Simple Analogy:
**A self-healing, scalable delivery fleet.**
*   **Docker Containers** are the individual delivery trucks.
*   **Kubernetes** is the central logistics brain. It:
    *   Assigns packages to trucks.
    *   Sends out new trucks if one breaks down.
    *   Adds more trucks during holiday rush hours.
    *   Optimizes routes for the fastest delivery.
All automatically, without human intervention.

### Real-World Examples:
*   Automatically scaling up the number of model inference servers during peak website traffic.
*   Rolling out a new version of a model to a small percentage of users without causing downtime (canary deployment).
*   Managing a complex application with dozens of microservices (model service, feature store, monitoring).

---
*🌳 **Parent Branch:** [[MLOps Overview]]
*⚙️ **The Function:** **Container Orchestration**.
*📈 **Key Features:** **Auto-scaling**, **Self-healing**, **Rolling updates**.
*🔗 **The Perfect Partner:** Manages fleets of [[Docker]] containers.
*☁️ **The Standard:** Runs on all major cloud platforms (GKE, EKS, AKS).
