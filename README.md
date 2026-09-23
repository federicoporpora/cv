# Federico Porpora — Curriculum Vitae

[![Build and Release CV](https://github.com/federicoporpora/cv/actions/workflows/build-cv.yml/badge.svg)](https://github.com/federicoporpora/cv/actions/workflows/build-cv.yml)
[![Latest Release](https://img.shields.io/github/v/release/federicoporpora/cv?label=latest%20release&style=flat-square&color=007ec6)](https://github.com/federicoporpora/cv/releases/tag/latest)
[![LaTeX](https://img.shields.io/badge/LaTeX-Source-008080?style=flat-square&logo=latex&logoColor=white)](https://www.latex-project.org/)

This repository maintains the LaTeX source code and build automation for my professional Curriculum Vitae, available in both English and Italian.

The compilation and distribution pipeline is completely automated with **GitHub Actions**. Upon any update to the `main` branch, the source documents are compiled with `pdflatex` and published directly to the [Latest Release](https://github.com/federicoporpora/cv/releases/tag/latest).

---

## 📄 Download Latest PDFs

| Language | Download Link |
| :--- | :--- |
| **English (EN)** | [Download `Federico_Porpora_CV_EN.pdf`](https://github.com/federicoporpora/cv/releases/download/latest/Federico_Porpora_CV_EN.pdf) |
| **Italiano (IT)** | [Download `Federico_Porpora_CV_IT.pdf`](https://github.com/federicoporpora/cv/releases/download/latest/Federico_Porpora_CV_IT.pdf) |

---

## 🔨 Local Compilation

To compile the documents locally, make sure you have a TeX Live distribution installed:

```bash
# Compile English version
pdflatex -interaction=nonstopmode Federico_Porpora_CV_EN.tex

# Compile Italian version
pdflatex -interaction=nonstopmode Federico_Porpora_CV_IT.tex
```
