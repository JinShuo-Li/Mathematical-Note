# Mathematics And Axiomatization

![LaTeX](https://img.shields.io/badge/Language-LaTeX-008080.svg)
![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)
![Status](https://img.shields.io/badge/Status-Work%20in%20Progress-orange.svg)

## 📖 Introduction

This repository contains my personal lecture notes and study summaries on **Mathematics and Axiomatization**. The project is typeset in $\LaTeX$ and covers a rigorous restructuring of mathematical foundations, ranging from logic and set theory to advanced analysis and algebra.

The goal of this project is to build a cohesive mathematical framework starting from the most basic axioms.

## 🗂️ Table of Contents

The notes are organized into the following chapters:

* **Preface**
* **Chapter 0: Basic Knowledge and Notations**
    * Propositional Logic
    * Predicate Logic
* **Chapter 1: The Axioms of ALL**
    * The Naive Set Theory
    * The Axiomatic Set Theory (ZFC)
    * Extensions of Axiomatic Set Theory
* **Chapter 2: Mathematical Analysis: Part I**
    * Extension of the Number System
    * Sequence Limit and the Properties of Real Numbers
    * Derivatives and Related Theorem
    * Integration and Improper Integrals
* **Chapter 3: Linear Algebra**
    * Linear Equations and Matrices
    * Determinants
    * Vectors in $\mathbb{R}^n$
    * Linear Transformations
    * Abstract Linear Spaces and Subspaces
* **Chapter 4: Abstract Algebra**
    * Operations and Algebraic Structures
    * Groups, Rings, and Fields
    * Galois Theory
    * Modules
* **Chapter 5: Mathematical Analysis II**
    * Series
    * Limits and Continuity in Euclidean Space
    * Differential Calculus of Multivariable Functions
    * Multiple Integrals
* **Chapter 6: Topology**
    * From Metric Spaces to Topological Spaces
    * Topological Spaces, Bases, and Subbases
    * Closed Sets, Connectedness, and Compactness
* **Chapter 7: Complex Analysis**
    * Complex Numbers and the Complex Plane
    * Complex Differentiability and Cauchy-Riemann Equations
    * Complex Integration and Cauchy's Theorem
    * Power Series, Singularities, and Residues
* **Chapter 8: Applied Mathematics: Graph Theory**
    * Introduction to Graph Theory
    * Paths and Circuits
    * Trees and Forests
    * Random Graphs
* **Chapter 9: Applied Mathematics: Probability Theory**
    * Classical Probability and Counting
    * Conditional Probability and Independence
    * Discrete and Continuous Random Variables
    * The Measure-Theoretic Foundation
    * Limit Theorems and Stochastic Processes
* **More**: More content will be coming soon.

## 📦 Versions & Layout

This repository keeps multiple versions of the notes:

- `code/splited_version/code/` is the main working directory (split files).
- `code/original_vertion/` stores the archived single-file source.
- `code/beutified_version/` stores the archived beautified build.
- `code/Mathematics and Axiomatization.docx` is a Word export.

## 🛠️ Usage & Compilation

This project has been split into multiple files for faster compilation. The main entry point is located at `code/splited_version/code/main.tex`.

### File Structure
```text
.
├── code/
│   ├── beutified_version/
│   │   ├── M&A.tex
│   │   └── M&A.pdf
│   ├── original_vertion/
│   │   ├── code_of_Mathematics_and_Axiomatization.tex
│   │   └── code_of_Mathematics_and_Axiomatization.pdf
│   ├── splited_version/
│   │   └── code/
│   │       ├── main.tex
│   │       ├── main.pdf
│   │       ├── assets/
│   │       └── chapters/
│   │           ├── preface.tex
│   │           ├── chapter0.tex
│   │           ├── chapter1.tex
│   │           └── ...
│   └── Mathematics and Axiomatization.docx
├── LICENSE
└── README.md
```

### How to Compile

You need a standard TeX distribution (TeX Live, MiKTeX, or MacTeX).

1. Clone the repository:
```bash
git clone https://github.com/JinShuo-Li/Mathematical-Note
```
2. Compile using `xelatex` (run twice to update the TOC):
```bash
cd code/splited_version/code
xelatex main.tex
xelatex main.tex
```



## ⚠️ License & Disclaimer (Important)

**Please read carefully before using these notes.**

### Copyright

© 2026 Jinshuo Li. All Rights Reserved.

### License

This work is licensed under a **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

To view a copy of this license, visit [http://creativecommons.org/licenses/by-nc-sa/4.0/](http://creativecommons.org/licenses/by-nc-sa/4.0/).

### Terms of Use

1. **Personal & Educational Use Only**: You are free to download, read, and modify these notes for your own personal study or research.
2. **No Commercial Use**: You strictly **MAY NOT** use this material for any commercial purposes. This includes, but is not limited to:
* Selling the PDF or source code.
* Using the content in paid courses, books, or training materials.
* Hosting the files on a website that charges for access or generates revenue from ads.


3. **Attribution**: If you share or adapt this material for non-commercial educational purposes, you must give appropriate credit to the original author.
