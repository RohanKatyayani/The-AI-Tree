# Multi-Head Attention

### One-Liner:
*   **What it is:** An enhancement to self-attention that allows a model to simultaneously focus on different aspects of the input sequence, like different types of relationships.

### The Big Picture:
Multi-Head Attention is the **power-up** for self-attention. Instead of having just one set of attention weights, it has multiple "heads" that operate in parallel, each learning to focus on different kinds of information.

### How it Works (The Core Idea):
The input is projected into multiple different representation subspaces. Each head performs self-attention independently in its own subspace, focusing on different types of patterns:
*   One head might focus on **syntactic** relationships (grammar).
*   Another might focus on **semantic** relationships (meaning).
*   Another might track **entity** connections (who did what to whom).

The outputs of all heads are then combined to form the final representation.

### Why it Matters:
It makes the attention mechanism more powerful and expressive. It's like having a team of specialists analyzing a document, each looking for different clues, rather than one generalist trying to notice everything.

### A Simple Analogy:
**A team of detectives analyzing a crime scene.**
*   **Single-Head Attention:** One detective trying to notice everything at once.
*   **Multi-Head Attention:** A team where:
    *   **Detective 1 (Head 1)** focuses on forensic evidence (fingerprints, DNA).
    *   **Detective 2 (Head 2)** analyzes the timeline and alibis.
    *   **Detective 3 (Head 3)** studies the motives and relationships between suspects.
*   They all work on the same case (input) simultaneously but from different angles, and then combine their findings for a complete picture.

### Real-World Examples:
*   In machine translation, one head might align nouns while another aligns verbs.
*   In a sentence, one head might link pronouns to their antecedents ("it" -> "cat"), while another captures the overall sentiment.

---
*🌳 **Parent Concept:** An enhancement to [[Self-Attention]].
*🧠 **The Core Idea:** **Parallel attention heads** focusing on different representation subspaces.
*🚀 **The Benefit:** Increases the model's **representational power** and ability to capture diverse relationships.
*🤖 **A Key Component:** Of the [[Transformers]] architecture.
