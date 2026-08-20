# 🌀 Spiral Classification: Neural Network Depth & Decision Boundary Visualizer

An interactive and dynamic visualization tool built with **PyTorch** and **Matplotlib** that demonstrates the impact of Neural Network depth (1 to 6 hidden layers) on learning non-linear decision boundaries using noisy spiral datasets.

---

## 📌 Highlights

- **Custom Dataset:** Generates a high-complexity, highly noisy double spiral dataset ($N=2000$, $\text{noise}=0.35$).
- **Multi-Architecture Comparison:** Trains 6 different Neural Network architectures ($1$ to $6$ hidden layers with $64$ neurons each).
- **Dual Visualizations:**
  - **Decision Boundary Evolution:** Smooth probability contour surfaces mapped dynamically alongside training data points.
  - **Validation Loss Curves:** Real-time tracking of BCE (Binary Cross Entropy) loss per epoch ($200$ total epochs).
- **Automated Animation Export:** Automatically exports the full interactive evaluation to high-quality `.mp4` and `.gif` formats.

---

## 🧠 Why the Spiral Dataset?

Standard linear and shallow models often struggle or fail entirely on complex, interleaved spiral distributions due to their severe non-linearity. This repository visually answers a fundamental Deep Learning question:

> **How does adding network depth fundamentally alter a model's capacity to fit complex, non-linear boundaries under high noise?**

---
