# Mathematics And Axiomatization

![LaTeX](https://img.shields.io/badge/Language-LaTeX-008080.svg)
![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

## 📖 Introduction

This repository contains my personal lecture notes and study summaries on **Mathematics and Axiomatization**. The project is written in $\LaTeX$ and now contains two synchronized editions:

- `code_en/`: the English edition.
- `code_cn/`: the Chinese edition, maintained as the translated counterpart of the English edition.

The notes attempt to build a coherent mathematical framework starting from basic logical and set-theoretic foundations, then moving through analysis, linear algebra, algebra, topology, complex analysis, graph theory, and probability theory.

The project is not intended to be a replacement for standard textbooks. It is closer to a structured personal reference: it emphasizes conceptual organization, definitions, theorem statements, proof sketches, worked examples, and connections between different areas of undergraduate mathematics.

## 🗂️ Current Structure

The current edition is organized using the standard book structure:

- **Front matter**
  - Preface
  - Reader's Guide
- **Main matter**
  - Four thematic parts
  - Chapters 0--9
  - Chapter-level practice supplements
- **Back matter**
  - Afterword

### Part I: Optional Foundations

- **Chapter 0: Fundamentals**
  - Propositional logic
  - Predicate logic
  - Basic proof language
- **Chapter 1: The Axioms of ALL**
  - Naive set theory
  - Axiomatic set theory
  - ZFC and related foundational viewpoints

### Part II: Core Undergraduate Mathematics

- **Chapter 2: Mathematical Analysis I**
  - Number systems
  - Limits and real numbers
  - Derivatives and related theorems
  - Integration and improper integrals
- **Chapter 3: Linear Algebra**
  - Linear equations and matrices
  - Determinants
  - Vectors in $\mathbb{R}^n$
  - Linear transformations
  - Abstract vector spaces and subspaces
- **Chapter 4: Abstract Algebra**
  - Operations and algebraic structures
  - Groups, rings, and fields
  - Galois theory
  - Modules
- **Chapter 5: Mathematical Analysis II**
  - Series
  - Limits and continuity in Euclidean space
  - Multivariable differential calculus
  - Multiple integrals

### Part III: Spaces and Complex Structure

- **Chapter 6: Topology**
  - Metric spaces and topological spaces
  - Bases and subbases
  - Closed sets, connectedness, and compactness
- **Chapter 7: Complex Analysis**
  - Complex numbers and the complex plane
  - Complex differentiability
  - Cauchy-Riemann equations
  - Complex integration
  - Power series, singularities, and residues

### Part IV: Discrete and Probabilistic Models

- **Chapter 8: Applied Mathematics: Graph Theory**
  - Basic graph terminology
  - Paths and circuits
  - Trees and forests
  - Random graphs
- **Chapter 9: Applied Mathematics: Probability Theory**
  - Classical probability and counting
  - Conditional probability and independence
  - Discrete and continuous random variables
  - Measure-theoretic foundations
  - Limit theorems and stochastic processes

## 📦 Repository Layout

```text
.
├── code_en/
│   ├── main.tex
│   ├── main.pdf
│   ├── assets/
│   └── chapters/
│       ├── preface.tex
│       ├── readers_guide.tex
│       ├── chapter0.tex
│       ├── chapter1.tex
│       ├── chapter2.tex
│       ├── chapter3.tex
│       ├── chapter4_revised.tex
│       ├── chapter5_revised.tex
│       ├── chapter6_revised.tex
│       ├── chapter7_revised.tex
│       ├── chapter8.tex
│       ├── chapter9_revised.tex
│       ├── afterword.tex
│       └── supplements/
│           ├── chapter0_practice.tex
│           ├── ...
│           └── chapter9_practice.tex
├── code_cn/
│   ├── main.tex
│   ├── main.pdf
│   ├── assets/
│   └── chapters/
│       ├── preface_cn.tex
│       ├── readers_guide_cn.tex
│       ├── chapter0_cn.tex
│       ├── chapter1_cn.tex
│       ├── chapter2_cn.tex
│       ├── chapter3_cn.tex
│       ├── chapter4_revised_cn.tex
│       ├── chapter5_revised_cn.tex
│       ├── chapter6_revised_cn.tex
│       ├── chapter7_revised_cn.tex
│       ├── chapter8_cn.tex
│       ├── chapter9_revised_cn.tex
│       ├── afterword_cn.tex
│       └── supplements/
│           ├── chapter0_practice_cn.tex
│           ├── ...
│           └── chapter9_practice_cn.tex
└── docs/
    └── index.html
```

### Notes on Source Files

Some older chapter files are still kept in the repository for reference, but the current build uses the files included by `main.tex`. In particular, several later chapters are now built from their revised versions, such as:

- `chapter4_revised.tex`
- `chapter5_revised.tex`
- `chapter6_revised.tex`
- `chapter7_revised.tex`
- `chapter9_revised.tex`

The Chinese edition follows the same structure with corresponding `_cn` filenames.

## 🛠️ Compilation

You need a standard TeX distribution such as TeX Live, MiKTeX, or MacTeX.

Both editions should be compiled with **XeLaTeX**.

### Compile the English Edition

```bash
cd code_en
xelatex main.tex
xelatex main.tex
```

### Compile the Chinese Edition

```bash
cd code_cn
xelatex main.tex
xelatex main.tex
```

Running XeLaTeX twice is recommended so that the table of contents, PDF bookmarks, and cross-references are updated correctly.

### Font Notes for the Chinese Edition

The Chinese edition uses `ctexbook` and requires Chinese fonts available to XeLaTeX. On Windows, common choices include:

```tex
\setCJKmainfont[AutoFakeBold=2, AutoFakeSlant=0.2]{SimSun}
\setCJKsansfont[AutoFakeBold=2, AutoFakeSlant=0.2]{SimHei}
\setCJKmonofont{SimSun}
\setmainfont{Times New Roman}
\setsansfont{Arial}
\setmonofont{Consolas}
```

On Linux, Noto CJK fonts are often a convenient alternative. If compilation fails because a font is missing, adjust the font settings in `code_cn/main.tex` rather than changing the chapter files.

## 📝 Chinese Edition

The Chinese edition in `code_cn/` is designed to correspond to the English edition in `code_en/` as closely as possible. It includes:

- the translated preface;
- the translated reader's guide;
- the translated main chapters;
- revised Chinese versions of the chapters that use revised English sources;
- translated chapter-level practice supplements;
- the translated afterword.

The Chinese edition is not merely a separate summary. It is intended to be a full translated counterpart of the English edition.

## 🧭 Project Status

This project is still under active revision. Current priorities include:

- improving consistency across chapters;
- expanding explanations where the exposition is too compressed;
- adding more examples, exercises, and proof details;
- keeping the Chinese edition synchronized with the English edition;
- refining the overall book structure and navigation.

If you find mathematical errors, typographical problems, broken references, or formatting issues, feel free to open an issue or start a discussion.

## ⚠️ License & Disclaimer

**Please read carefully before using these notes.**

### Copyright

© 2026 Jinshuo Li. All Rights Reserved.

### License

This work is licensed under a **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

To view a copy of this license, visit [http://creativecommons.org/licenses/by-nc-sa/4.0/](http://creativecommons.org/licenses/by-nc-sa/4.0/).

### Terms of Use

1. **Personal and Educational Use Only**  
   You are free to download, read, and modify these notes for your own personal study or research.

2. **No Commercial Use**  
   You strictly **MAY NOT** use this material for any commercial purposes. This includes, but is not limited to:
   - selling the PDF or source code;
   - using the content in paid courses, books, or training materials;
   - hosting the files on a website that charges for access or generates revenue from ads.

3. **Attribution**  
   If you share or adapt this material for non-commercial educational purposes, you must give appropriate credit to the original author.

4. **ShareAlike**  
   If you remix, transform, or build upon this material, you must distribute your contributions under the same license.

## Release Notes

### v1.3.0 (2026-07-05)

This release updates both the English and Chinese editions, with the main emphasis on keeping the two versions structurally aligned and easier to navigate.

In the English edition, the book structure has been refined around the current main entry points, chapter organization, and practice supplements. In the Chinese edition, the same structural design has now been brought into alignment with the English version: front matter, reader's guide, four thematic parts, chapter-level practice supplements, revised chapter files, and afterword. The main entry point `code_cn/main.tex` has also been aligned with the English build structure while preserving the Chinese typesetting setup.

Overall, this update improves repository organization, bilingual consistency, and reader navigation across both editions. It is a structural and editorial synchronization release rather than a complete mathematical rewrite of every chapter.

### v1.2.0 (2026-07-03)

This release substantially extends and revises several chapters of the English edition, especially Chapters 4, 6, 7, and 9, covering abstract algebra, point-set topology, complex analysis, and probability theory.

A considerable amount of new material was added, including more complete definitions, proofs, examples, counterexamples, and explanations of the motivations behind important concepts. The organization and writing style of these chapters were also revised to make them more consistent with the earlier and more developed parts of the notes.

A new reader's guide, chapter-level practice supplements, and an afterword were also introduced to improve the usability and structure of the project.

Please note that the project remains a work in progress. Some chapters are more developed than others, and future releases will continue to improve consistency, depth, and bilingual synchronization.
