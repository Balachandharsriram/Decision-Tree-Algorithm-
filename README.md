# 🌳 Decision Tree Classification on Diabetes Dataset

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Dataframe-green?style=flat-square&logo=pandas)
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow?style=flat-square&logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-purple.svg?style=flat-square)

---

## 🎯 Project Overview

This repository demonstrates building a **Decision Tree Classifier** on the popular **Diabetes dataset**.  
It covers everything from **data loading to evaluation and visualization**, making it a complete reference for beginners and practitioners alike.

---

## 🚀 Key Highlights

✅ **Data Handling**
- Loaded dataset using `pandas`
- Checked for missing values to ensure data quality

✅ **Model Building**
- Split data into training and testing sets (90% / 10%)
- Trained a **Decision Tree Classifier** using `entropy` as the splitting criterion

✅ **Performance Evaluation**
- Calculated **accuracy score**
- Displayed **confusion matrix** and **classification report** for precision, recall, F1 insights

✅ **Tree Visualization**
- Used `sklearn.tree.plot_tree` for a quick plot
- Rendered detailed tree with `graphviz` for feature-level decision paths

---

## 🛠 Tech Stack

| Library         | Usage                            |
|-----------------|---------------------------------|
| `pandas`        | Data manipulation               |
| `numpy`         | Numerical operations            |
| `scikit-learn`  | Model building & evaluation     |
| `matplotlib`    | (Optional) for plotting         |
| `graphviz`      | Advanced tree visualization     |

---
.
├── notebooks/
│ └── Decision Tree Algorithm.ipynb
├── data/
│ └── diabetes.csv
├── screenshots/
│ └── decision_tree_graphviz.png
├── README.md
└── requirements.txt

---
## ⚙️ How to Run

1️⃣ Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn graphviz

2️⃣ Open the notebook:

```bash
jupyter notebook

3️⃣ Run Decision Tree Algorithm.ipynb cell by cell.
```

✨ Why This Project?
✅ Offers a hands-on example of building and interpreting Decision Trees
✅ Easy to adapt for any binary classification dataset
✅ Shows how to use both plot_tree and graphviz for richer visuals

👨‍💻 Author
Developed by Balachandharsriram M.
💌 Always open to feedback and collaborations.

⭐ If you find this helpful...
Don’t forget to star ⭐ this repository — it motivates me to create more practical ML examples!


