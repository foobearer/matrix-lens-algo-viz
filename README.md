# matrix-lens-algo-viz

A Python program for exploring and visualizing core linear algebra concepts on
matrices, vectors, linear transformations, and eigenvectors, through clean
implementations and interactive plots.

Built for learners who want to see the math come alive in code.

## Topics Covered

- **Matrices & Vectors** — creation, shapes, and properties
- **Basic Operations** — addition, subtraction, matrix multiplication
- **Determinant** — for square matrices
- **Transpose** — for any matrix shape
- **Inverse** — for square, non-singular matrices
- **Linear Transformations** — computing and visualizing A @ v
- **Eigenvectors & Eigenvalues** — detection, proof, and visual exploration

## The `Value` Class

A reusable wrapper around NumPy arrays with clean linear algebra methods:

| Method | Description |
|---|---|
| `a + b` | Addition |
| `a - b` | Subtraction |
| `a @ b` | Matrix multiplication |
| `a.det()` | Determinant |
| `a.T` | Transpose |
| `a.inv()` | Inverse |
| `v.transform_vector(A)` | Linear transformation A @ v |
| `v.is_eigenvector(A)` | Returns `(True, λ)` or `(False, None)` |
| `v.plot_vectors(A)` | Plots v and Av with eigenvector annotation |

## Notebooks

| Notebook | Description |
|---|---|
| `Linear-Algebra.ipynb` | Matrices, vectors, operations, and visualizations |
| `Eigenvectors-Eigenvalues.ipynb` | Linear transformations and eigenvector detection |

## Requirements

```bash
pip install numpy matplotlib
```

## Usage

Open either notebook in Jupyter or VS Code and run cells top to bottom.
Each section is self-contained with explanations and working examples.

## Background

Built as part of MIT's AI & Data Science Course in Linear Algebra studies.
Aimed at making linear algebra intuitive through code and visualization.
