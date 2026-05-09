# Practical Linear Algebra for Data Science — Code Reproduction and Notes

This repository was created as a structured code reproduction and conceptual explanation project based on **Practical Linear Algebra for Data Science: From Core Concepts to Applications Using Python** by **Mike X. Cohen**.

> The book cover is not embedded. Add a legal/official image manually if required.

---

## Project Description

The repository contains executed Jupyter notebooks for all 16 chapters. The notebooks are written in English and combine conceptual explanation, adapted original code examples, output interpretation, and chapter-level summaries.

Each notebook includes:

- learning objectives,
- theoretical explanation,
- code reproduction using original/adapted examples,
- output interpretation,
- extended study notes,
- chapter summary,
- key takeaways.

All examples are designed to run locally without external datasets.

---

## Book Information

- **Title:** Practical Linear Algebra for Data Science
- **Subtitle:** From Core Concepts to Applications Using Python
- **Author:** Mike X. Cohen
- **Publisher:** O'Reilly Media
- **Main Topics:** vectors, matrices, rank, inverse, QR, LU, least squares, eigendecomposition, SVD, PCA, and Python implementation.

---

## Repository Structure

```text
.
├── README.md
├── requirements.txt
└── notebooks/
    ├── Chapter_01_Introduction.ipynb
    ├── Chapter_02_Vectors_Part_1.ipynb
    ├── Chapter_03_Vectors_Part_2.ipynb
    ├── Chapter_04_Vector_Applications.ipynb
    ├── Chapter_05_Matrices_Part_1.ipynb
    ├── Chapter_06_Matrices_Part_2.ipynb
    ├── Chapter_07_Matrix_Applications.ipynb
    ├── Chapter_08_Matrix_Inverse.ipynb
    ├── Chapter_09_Orthogonal_Matrices_and_QR_Decomposition.ipynb
    ├── Chapter_10_Row_Reduction_and_LU_Decomposition.ipynb
    ├── Chapter_11_General_Linear_Models_and_Least_Squares.ipynb
    ├── Chapter_12_Least_Squares_Applications.ipynb
    ├── Chapter_13_Eigendecomposition.ipynb
    ├── Chapter_14_Singular_Value_Decomposition.ipynb
    ├── Chapter_15_Eigendecomposition_and_SVD_Applications.ipynb
    └── Chapter_16_Python_Tutorial.ipynb
```

---

## Chapter Overview

1. **Introduction** — why linear algebra matters for computational data science.
2. **Vectors, Part 1** — vector operations, dot product, norm, unit vectors, orthogonal decomposition.
3. **Vectors, Part 2** — vector sets, linear combinations, independence, subspace, span, basis.
4. **Vector Applications** — correlation, cosine similarity, filtering, k-means.
5. **Matrices, Part 1** — matrix creation, special matrices, arithmetic, multiplication, symmetry.
6. **Matrices, Part 2** — norms, trace, spaces, rank, determinant, characteristic polynomial.
7. **Matrix Applications** — covariance, geometric transformation, image-like filtering.
8. **Matrix Inverse** — inverse, one-sided inverse, pseudoinverse, numerical stability.
9. **Orthogonal Matrices and QR** — orthogonality, QR decomposition, reconstruction.
10. **Row Reduction and LU** — systems of equations, row reduction, LU decomposition.
11. **GLM and Least Squares** — design matrices, residuals, least-squares solutions, QR solving.
12. **Least Squares Applications** — polynomial regression, multicollinearity, regularization.
13. **Eigendecomposition** — eigenvalues, eigenvectors, diagonalization, definiteness.
14. **SVD** — singular values, rank, low-rank approximation, pseudoinverse.
15. **Eigendecomposition and SVD Applications** — PCA, low-rank approximation, denoising.
16. **Python Tutorial** — NumPy, indexing, functions, visualization, translating formulas to code.

---

## Installation

```bash
python -m venv venv
```

Windows:

```bash
.\venv\Scripts\activate
```

macOS/Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## How to Run

```bash
jupyter notebook
```

Open the `notebooks/` folder and run the desired chapter notebook. The submitted notebooks are already executed, so outputs and plots are visible directly.

---

## Dependencies

```text
numpy
pandas
matplotlib
scipy
scikit-learn
jupyter
nbformat
nbclient
```

---

## Academic Integrity

This repository is an academic learning project. The explanations are written in original wording, and the code examples are adapted into original runnable demonstrations. The work is intended to support understanding, not to replace the original book.

---

## Completion Status

- [x] Chapter 1 through Chapter 16 completed
- [x] All notebooks executed
- [x] README created
- [x] requirements.txt created
