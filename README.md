# vocaloid-python
# Vocaloid Python Project 🎶

## Overview
This project integrates **core Python programming concepts** with **data analysis** and **machine learning**, using *Vocaloid* as a thematic context.  
The work covers:
- Functions, loops, conditionals, classes, and exceptions
- Data structures (dict, list, set, tuple) and slicing
- File I/O with PNG figure exports
- Exploratory analysis using **pandas** and **matplotlib**
- Predictive modelling with **scikit-learn**

It is accompanied by a formal report (`Vocaloid_Report_Finalized.docx`) written to academic standards, including **Harvard referencing**.

---

## Files
- `Vocaloid.ipynb` — Jupyter/Colab-ready notebook with full implementation
- `Vocaloid_Report_Finalized.docx` — Word report (~700+ words, with abstract, intro, methods, results, conclusion, references, appendix of figures)
- `figs/` — generated screenshots and figures for inclusion in the report
- `README.md` — this file

---

## Implementation Highlights
- **Functions & slicing**: `first_two_songs()` previews the first two entries for a given Vocaloid.
- **Loops & conditionals**: menu system driven by a `while True` loop with `if/elif` branches.
- **Classes & exceptions**: includes a `Song` class and a small custom `InputError` for safe input.
- **Machine learning**:  
  - Pre-processing with `ColumnTransformer` (One-Hot encoding)  
  - Models: Decision Tree & Logistic Regression  
  - Evaluation with accuracy scores and comparison plots
- **Operators coverage**: explicit demo of `**` (exponentiation) and `//` (floor division) for rubric alignment.

---

## Figures (Appendix in Report)
1. Songs per Vocaloid  
2. Genre Distribution  
3. Year Distribution  
4. Top Producers  
5. Dataset Head (preview table)  
6. Model Accuracy (Decision Tree vs Logistic Regression)

---

## How to Run
1. Open `Vocaloid.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Run all cells (`Runtime` > `Run all`).
3. The notebook will:
   - Build the in-memory Vocaloid song database
   - Provide menu interaction
   - Generate and save analysis figures
   - Train and evaluate models

Figures will be saved into `figs/` automatically.

---

## References
- Yamaha Corporation. (n.d.). *Vocaloid official*.  
- Crypton Future Media. (n.d.-a). *Hatsune Miku*.  
- Crypton Future Media. (n.d.-b). *Megurine Luka*.  
- Crypton Future Media. (n.d.-c). *Genre trends in Vocaloid*.  
- TWINDRILL. (n.d.). *Kasane Teto official fan materials*.  

---

## Author
**Sam Breen**  
Prepared for assessment submission, showcasing both programming fundamentals and applied data analysis in a cultural context.
