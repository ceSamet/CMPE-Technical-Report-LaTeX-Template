# CMPE Technical Report LaTeX Template

A professional, compliant LaTeX template designed for Engineering Technical Reports (specifically aligned with Kadir Has University CMPE guidelines).

This template is optimized for **Times New Roman** typography, **IEEE citation style**, and strict formatting rules (margins, spacing, headers). It also includes built-in fixes for common Turkish language character conflicts in LaTeX.

## 🚀 Features

* **Strict Formatting:** Pre-configured geometry (3cm/2cm margins), 1.5 line spacing, and paragraph indentations.
* **Typography:** Uses `newtxtext` and `newtxmath` for modern, glitch-free Times New Roman font rendering.
* **IEEE Referencing:** Integrated `biblatex` with IEEE style (`[1]`, `[2]`) and automatic sorting.
* **Turkish Language Support:**
    * `babel` support for Turkish hyphenation.
    * **Automated Fix:** Includes `\shorthandoff{=}` to prevent conflicts between Turkish characters and graphic commands.
* **Professional Tables:** Pre-loaded with `booktabs` for publication-quality tables.
* **Advanced TOC:** Custom Table of Contents width settings to handle long Appendix titles without overlap.

## 📂 Project Structure

```text
.
├── main.tex           # The primary LaTeX source file
├── references.bib     # BibTeX database for citations
├── figures/           # (Recommended) Directory for storing images
└── README.md          # This file
