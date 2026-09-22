# Comparative Study of Generative Models on ArtBench-10 🎨🤖

[![Dataset: ArtBench-10](https://img.shields.io/badge/Dataset-ArtBench--10-blue)](#)
[![Domain: Deep Learning](https://img.shields.io/badge/Domain-Deep%20Learning%20%2F%20Generative%20AI-orange)](#)

## 📌 Abstract & Overview

This project provides a rigorous empirical evaluation of generative modeling techniques applied to the **ArtBench-10** benchmark dataset, aiming to synthesize realistic artwork across multiple artistic styles. 

The study evaluates and compares three primary paradigms of deep generative models:
1. **Autoencoders & Variational Autoencoders (VAEs / $\beta$-VAEs)**: Investigating the trade-off between image reconstruction fidelity and latent space regularization.
2. **Generative Adversarial Networks (DCGAN)**: Assessing adversarial minimax dynamics and stability in stylized visual synthesis.
3. **Diffusion-Based Models**: Evaluating sample realism, iterative denoising quality, and diversity.

---

## 🔬 Experimental Methodology & Evaluation

- **Rapid Prototyping:** Hyperparameter exploration and model validation were initially carried out on a reduced subset before full-scale training.
- **Latent Regularization:** Detailed analysis of the $\beta$ parameter impact in VAE architectures.
- **Quantitative Metrics:** 
  - **FID** (*Fréchet Inception Distance*)
  - **KID** (*Kernel Inception Distance*)
- **Statistical Rigor:** All quantitative results were evaluated across multiple random seeds to ensure statistical significance.

---
## 🛠️ Tech Stack & Requirements

* **Language:** Python 3.9+
* **Frameworks:** PyTorch / torchvision, NumPy, Matplotlib, SciPy
* **Dependencies:** Strictly defined in `requirements.txt`
* **Hardware:** CUDA-compatible GPU (strongly recommended)

---

## 🚀 Getting Started

Follow the instructions below to clone the repository, configure the local execution environment, and install dependencies.

### 1. Clone the Repository

```bash
git clone [https://github.com/MartimAntunes04/artbench10-generative-models.git](https://github.com/MartimAntunes04/artbench10-generative-models.git)
cd artbench10-generative-models
