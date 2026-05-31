Machine-Learning-Tutorial-
Understanding Support Vector Machine Kernels Through Visualisation
This repository provides an educational and experimental exploration of Support Vector Machines (SVMs) and the effect of different kernel functions on classification performance and decision boundaries. The project combines a Jupyter Notebook implementation with an accompanying academic-style PDF report to build both practical intuition and theoretical understanding.

Project Overview
Support Vector Machines are powerful supervised learning algorithms widely used for classification tasks. A key strength of SVMs lies in their use of kernel functions, which allow models to learn non-linear decision boundaries.

This project:

Demonstrates Linear, Polynomial, and Radial Basis Function (RBF) kernels
Uses a non-linearly separable two-moons dataset
Visualises decision boundaries for intuitive comparison
Explores hyperparameter effects, including the bias–variance trade-off
Discusses ethical and practical considerations of kernel-based models
Repository Contents
*.ipynb — Jupyter Notebook implementing:
Dataset generation
Model training
Decision boundary visualisation
Kernel comparison and evaluation
*.pdf — Detailed written report explaining:
SVM theory
Kernel trick intuition
Experimental results
Ethical and practical implications
README.md — Project documentation
LICENSE — Open-source license information
Dataset
The project uses a synthetic two-moons dataset generated via scikit-learn.
This dataset is intentionally non-linearly separable, making it ideal for demonstrating the limitations of linear classifiers and the strengths of kernel-based SVMs.

Key Results
Kernel Type	Approx. Test Accuracy	Notes
Linear	~85%	Underfits non-linear data
Polynomial (degree 3)	~87%	Improved flexibility
RBF	~96–97%	Best performance
Requirements
Python 3.x
NumPy
Matplotlib
scikit-learn
Jupyter Notebook
Install dependencies using:

pip install numpy matplotlib scikit-learn notebook
Viewing the Notebook
If the notebook does not render properly on GitHub, open it using:

Google Colab
Jupyter Notebook
GitHub occasionally fails to preview .ipynb files due to notebook rendering limitations.

License
This project is released under the MIT License.
