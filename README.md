# Machine-Learning-Tutorial

# Understanding Support Vector Machine Kernels Through Visualisation

## 📌 Project Overview

This repository presents an educational tutorial and practical implementation of **Support Vector Machines (SVMs)** and their kernel functions using Python and Jupyter Notebook.

The project focuses on understanding how different kernel functions influence classification performance and decision boundaries through visualisation and experimentation on a non-linearly separable dataset.

The tutorial combines:

* theoretical understanding of SVMs
* practical machine learning implementation
* visual comparison of kernels
* experimental evaluation and analysis

---

## 🎯 Aim of the Project

The main aim of this project is to explore how kernel functions allow Support Vector Machines to solve non-linear classification problems.

The project demonstrates:

* Linear Kernel
* Polynomial Kernel
* Radial Basis Function (RBF) Kernel

and compares their performance visually and quantitatively.

---

## 🧠 Learning Objectives

This tutorial helps users understand:

* the fundamentals of Support Vector Machines
* linear vs non-linear classification
* the kernel trick
* hyperparameter effects
* decision boundary visualisation
* model evaluation and comparison

---

## 📂 Repository Contents

| File                                                             | Description                              |
| ---------------------------------------------------------------- | ---------------------------------------- |
| `Shravani_Mukkarigaris_24073262_Machine_Learning_Tutorial.ipynb` | Complete Jupyter Notebook implementation |
| `Tutorial_Report.pdf`                                            | Academic-style tutorial/report           |
| `README.md`                                                      | Project documentation                    |
| `LICENSE`                                                        | Open-source license information          |

---

## 🧪 Dataset Used

This project uses a **synthetic two-moons dataset** generated using `scikit-learn`.

The dataset is intentionally non-linearly separable, making it highly suitable for demonstrating:

* limitations of linear classifiers
* advantages of kernel-based learning
* complex decision boundaries

Dataset generation is performed directly inside the notebook.

Example:

```python id="9m93ka"
from sklearn.datasets import make_moons
```

---

## ⚙️ Technologies and Libraries Used

### Programming Language

* Python 3.x

### Libraries

* NumPy
* Matplotlib
* scikit-learn
* Jupyter Notebook

---

## 🛠️ Installation

Install the required dependencies using:

```bash id="xjlwm3"
pip install numpy matplotlib scikit-learn notebook
```

---

## ▶️ Running the Project

### Step 1 — Clone the Repository

```bash id="itxg7m"
git clone https://github.com/your-username/Machine-Learning-Tutorial.git
```

### Step 2 — Navigate to the Project Folder

```bash id="l9q2a4"
cd Machine-Learning-Tutorial
```

### Step 3 — Launch Jupyter Notebook

```bash id="6wrr6t"
jupyter notebook
```

### Step 4 — Open the Notebook

Open:

```text id="gr0j73"
Shravani_Mukkarigaris_24073262_Machine_Learning_Tutorial.ipynb
```

Run all cells sequentially to reproduce the results and visualisations.

---

## 📊 Project Workflow

The notebook follows these steps:

1. Import libraries
2. Generate synthetic dataset
3. Visualise dataset distribution
4. Split training and testing data
5. Train SVM models using:

   * Linear Kernel
   * Polynomial Kernel
   * RBF Kernel
6. Plot decision boundaries
7. Evaluate model performance
8. Compare kernel behaviour
9. Analyse hyperparameter effects

---

## 📈 Results Summary

| Kernel Type       | Approx. Accuracy | Observation                     |
| ----------------- | ---------------- | ------------------------------- |
| Linear Kernel     | ~85%             | Underfits non-linear data       |
| Polynomial Kernel | ~87%             | Captures moderate complexity    |
| RBF Kernel        | ~96–97%          | Best classification performance |

### Key Findings

* Linear kernels struggle with non-linear patterns.
* Polynomial kernels improve flexibility.
* RBF kernels provide the most effective non-linear separation.
* Kernel choice significantly impacts model performance.

---

## 📷 Visualisations Included

The notebook contains several visual outputs, including:

* scatter plots of the dataset
* SVM decision boundary visualisations
* kernel comparison plots
* classification region analysis

These visualisations help explain how kernels transform feature spaces and improve classification.

---

## 📖 Viewing the Notebook

If the notebook does not render properly on GitHub, open it using:

* Google Colab
* Jupyter Notebook

GitHub occasionally fails to preview `.ipynb` files due to notebook rendering limitations.

---

## 📚 References

### Research Papers

* Cortes, C. & Vapnik, V. (1995).
  *Support-Vector Networks*. Machine Learning.

* Scholkopf, B. & Smola, A. (2002).
  *Learning with Kernels*.

---

### Documentation and Learning Resources

* Scikit-learn Documentation
  https://scikit-learn.org/

* Support Vector Machines — Scikit-learn User Guide
  https://scikit-learn.org/stable/modules/svm.html

* Matplotlib Documentation
  https://matplotlib.org/

* NumPy Documentation
  https://numpy.org/

---

## ⚖️ Ethical Considerations

Although this project uses synthetic data, real-world machine learning systems may introduce ethical concerns such as:

* bias in datasets
* unfair decision-making
* lack of explainability
* overfitting and poor generalisation

Understanding these considerations is important when applying machine learning models in domains such as:

* healthcare
* recruitment
* finance
* education

---

## 🚀 Future Improvements

Potential future extensions of this project include:

* cross-validation
* GridSearchCV hyperparameter optimisation
* real-world datasets
* multi-class classification
* comparison with neural networks
* interactive visualisations

---

## 👩‍💻 Author

M Shravani
MSc Data Science
University of Hertfordshire

---

## 📜 License

This project is licensed under the MIT License.

You are free to use, modify, and distribute this work with proper attribution.
