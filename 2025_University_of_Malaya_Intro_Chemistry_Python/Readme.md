#  Chemistry in Python

This repository contains Jupyter notebooks for a short **primer on computational and data-driven chemistry**.
The materials were prepared for the **Python Lecture Series** at the **University of Malaya**.

---

##  Contents

| File                                                                                                                                                   | Description                                                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`RDkit.ipynb`](https://colab.research.google.com/github/Svatunek-Lab/teaching/blob/main/2025_University_of_Malaya_Intro_Chemistry_Python/RDkit.ipynb) | Introduction to **cheminformatics with RDKit** — molecules from SMILES, visualization, 2D→3D conversion, descriptors, and Lipinski’s Rule of Five. |
| [`ML.ipynb`](https://colab.research.google.com/github/Svatunek-Lab/teaching/blob/main/2025_University_of_Malaya_Intro_Chemistry_Python/ML.ipynb)       | Basic **machine learning on chemical data** — from molecular descriptors to predictive modeling.                                                   |
| `data/`                                                                                                                                                | Example datasets used in the notebooks.                                                                                                            |

---

##  Requirements

You can run the notebooks locally or on **Google Colab**.
The following Python packages are required:

```
rdkit
py3Dmol
pandas
scikit-learn
matplotlib
```

To install locally:

```bash
pip install rdkit py3Dmol pandas scikit-learn matplotlib
```

---

##  Quick Start

Open the notebooks directly in **Google Colab** by clicking:

* [RDkit.ipynb](https://colab.research.google.com/github/Svatunek-Lab/teaching/blob/main/2025_University_of_Malaya_Intro_Chemistry_Python/RDkit.ipynb)
* [ML.ipynb](https://colab.research.google.com/github/Svatunek-Lab/teaching/blob/main/2025_University_of_Malaya_Intro_Chemistry_Python/ML.ipynb)

---

##  Topics Covered

* Representing molecules with **SMILES**
* Visualizing molecules in **2D** and **3D**
* Calculating **molecular descriptors**
* Applying **Lipinski’s Rule of Five**
* Preparing data for **machine learning**
* Building simple **predictive models** for chemical properties

---

##  Credits

Developed by **Dennis Svatunek**, TU Wien
for the **University of Malaya Python Lecture Series (2025)**
