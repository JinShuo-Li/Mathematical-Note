# Mathematics And Axiomatization

![LaTeX](https://img.shields.io/badge/Language-LaTeX-008080.svg)
![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)
![Status](https://img.shields.io/badge/Status-Work%20in%20Progress-orange.svg)

## 📖 Introduction

This repository contains my personal lecture notes and study summaries on **Mathematics and Axiomatization**. The English edition is typeset in $\LaTeX$ and covers a rigorous restructuring of mathematical foundations, ranging from logic and set theory to advanced analysis and algebra.

The goal of this project is to build a cohesive mathematical framework starting from the most basic axioms.

## 🗂️ Table of Contents

The English notes are organized into the following chapters:

* **Preface**
* **Chapter 0: Fundamentals**
    * Propositional Logic
    * Predicate Logic
* **Chapter 1: The Axioms of ALL**
    * The Naive Set Theory
    * The Axiomatic Set Theory (ZFC)
    * Extensions of Axiomatic Set Theory
* **Chapter 2: Mathematical Analysis I**
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

## 📦 Layout

The current workspace keeps the English edition in `code_en/`:

- `code_en/main.tex` is the main entry point.
- `code_en/assets/` contains figures and other static assets.
- `code_en/chapters/` contains the chapter source files.
- `code_en/main.pdf` is the compiled English PDF.
- `docs/index.html` provides a simple web preview.

## 🛠️ Compilation

You need a standard TeX distribution such as TeX Live, MiKTeX, or MacTeX.

To compile the English edition:

```bash
cd code_en
xelatex main.tex
xelatex main.tex
```

Run XeLaTeX twice so the table of contents and references are updated.

## 📝 Chinese Version

We also provide a Chinese edition of the notes, which can be found in the `code_cn/` directory. The structure is similar to the English version, and it is typeset in $\LaTeX$ as well.

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

## Release Notes

### v1.2.0 (2026-07-03)

This time, we are releasing v1.2.0 of the note.

The main update is a substantial extension and revision of Chapters 4, 6, 7, and 9 in the English version. These chapters focus on abstract algebra, point-set topology, complex analysis, and probability theory.

A considerable amount of new material has been added, including more complete definitions, proofs, examples, counterexamples, and explanations of the motivations behind important concepts. The organization and writing style of these chapters have also been revised to make them more consistent with the earlier and more developed parts of the note.

In addition, a new afterword has been added to reflect on the process of studying, organizing, and writing mathematics.

Please note that Chapters 0, 1, 2, 3, 5, and 8 remain unchanged in this release.

If you find any errors in the note, whether mathematical, typographical, or related to formatting, you can open an issue or simply @ me in the discussion section.

Hope you like it!