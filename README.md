# MATH4267: Deep Learning and Artificial Intelligence (2024–25)
## Assignment – Paper Summary and Image Classification/Generation Tasks

This repository contains my solutions to the MATH4267 assignment, which consists of two main components:

---

## 🧠 Part 1: Research Paper Summary

### Paper:
**"Beyond the edge of stability via two-step gradient updates"**  
*Chen L, Bruna J. ICML 2023*

### Summary:
This section includes:
- An accessible overview of the paper’s context and contributions, with an emphasis on the phenomenon of gradient descent convergence in unstable regimes.
- A novel real-world application proposal of the two-step update method, formulated with a specific measurable quantity.
- A use case analysis of Theorem 1, identifying its assumptions and demonstrating its implications with concrete examples.
- Critical insights into key results (Proposition 2, Observation 1, Figure 3), their relevance to the paper’s argument, and their potential usefulness for researchers or practitioners.

📄 See `write-up.pdf` for the full summary and analysis (pages 1–4).

---

## 🔍 Part 2: Predictive Modelling and Image Generation

### Task A: Image Classification
- Developed a supervised learning model to predict handwritten character labels (A–F) from 28×28 grayscale images.
- Used a convolutional neural network (CNN) with dropout and early stopping to prevent overfitting.
- Input: `x_test.csv`  
- Output: `predictions.csv` — contains predicted character labels for 10,000 unlabelled images.

### Task B: Image Generation
- Implemented a generative model to produce synthetic images resembling the nonsense characters A–F.
- Used a Conditional Variational Autoencoder (CVAE) to generate 3000 images (1000 per class).
- Output: `new.csv` — each row contains a label and corresponding 784-pixel grayscale image.

### Task C: Methodology Report
Describes:
- Design choices and justifications for both classification and generation models.
- Preprocessing, model architecture, training strategy, and regularisation.
- Reflections on performance, model comparisons, and lessons learned.

📄 See `write-up.pdf` for the full technical report (pages 5–7).

---

## 📁 Files in this Repository

- `write-up.pdf`: Combined report for Parts 1 & 2 (max 7 pages).
- `predictions.csv`: Classification results for the test set (Task A).
- `new.csv`: Generated images for each character class (Task B).
- `xy_train.csv`, `x_test.csv`: Input datasets used in training and evaluation.

---

## 🛠 Technologies Used

- Language: R with Keras and TensorFlow
- Models: CNN (for classification), CVAE (for generation)
- Tools: GitHub Codespaces, Ultra (dataset access), ggplot2 (for visualisation)

---

## 🔁 Reproducibility

While code is not required for submission, all results are reproducible using standard R packages and configurations described in the report.

---

## 📅 Submission Deadline

**Submitted:** 9 May 2025 (before 5 PM)

---

## 📬 Contact

If you have any questions or issues running the models or interpreting the outputs, feel free to reach out via the repository’s issue tracker or email.

