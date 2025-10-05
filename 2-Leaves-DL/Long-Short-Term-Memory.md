# Long Short-Term Memory (LSTM)

### One-Liner:
*   **What it is:** A special type of recurrent neural network (RNN) capable of learning long-term dependencies in sequential data.

### The Big Picture:
LSTMs were the **memory masters** of deep learning before the Transformer era. They solved the critical "vanishing gradient" problem of basic RNNs, allowing them to remember information over much longer sequences.

### How it Works (The Core Idea):
LSTMs introduce a "cell state" that runs through the entire sequence, acting like a conveyor belt of memory. They use three specialized gates to control information flow:
1.  **Forget Gate:** Decides what information to throw away from the cell state.
2.  **Input Gate:** Decides what new information to store in the cell state.
3.  **Output Gate:** Decides what information to output based on the cell state.

### Why it Matters:
They enabled practical applications of RNNs for tasks requiring long-term context, like machine translation, speech recognition, and time series prediction.

### A Simple Analogy:
**A manager making decisions with a notebook.**
*   The **Cell State** is the notebook where important information is written.
*   The **Forget Gate** is deciding which old notes to cross out.
*   The **Input Gate** is deciding what new information to write down.
*   The **Output Gate** is deciding which notes to share in the current meeting.
*   This system allows the manager to maintain relevant context over long periods.

### Real-World Examples:
*   **Early Google Translate** used LSTMs for sequence-to-sequence translation.
*   **Speech-to-text systems** that need context across many words.
*   **Stock price prediction** using historical time series data.
*   **Music generation** that maintains musical themes over time.

---
*🌳 **Parent Branch:** [[Deep Learning]]
*🧠 **The Innovation:** **Gated mechanisms** for long-term memory.
*📈 **Solves:** The **vanishing gradient problem** in RNNs.
*🔗 **Predecessor To:** The [[Transformers]] architecture.
