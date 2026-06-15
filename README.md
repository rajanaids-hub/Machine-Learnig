# Machine Learning Basics — Hands-on

A beginner-friendly series of Jupyter notebooks that walks you through the core concepts and algorithms of Machine Learning using Python and scikit-learn.

## Notebooks

| # | Notebook | Topics |
|---|----------|--------|
| 01 | [Introduction & Data Preprocessing](01_introduction_and_preprocessing.ipynb) | What is ML, EDA, missing-value imputation, encoding, feature scaling, train/test split |
| 02 | [Linear Regression](02_linear_regression.ipynb) | Simple & multiple linear regression, MSE / RMSE / MAE / R², residual analysis |
| 03 | [Classification](03_classification.ipynb) | Logistic Regression, Decision Tree, Random Forest, confusion matrix, precision/recall/F1 |
| 04 | [Clustering](04_clustering.ipynb) | K-Means (Elbow Method, Silhouette Score), DBSCAN, customer segmentation |

## Prerequisites

- Python 3.8+
- [Jupyter Notebook](https://jupyter.org/) or [JupyterLab](https://jupyterlab.readthedocs.io/)

Install the required packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

## Getting Started

```bash
# Clone the repository
git clone https://github.com/rajanaids-hub/Machine-Learnig.git
cd Machine-Learnig

# Launch Jupyter
jupyter notebook
```

Open the notebooks in order (01 → 02 → 03 → 04) to follow the learning path.

## Learning Path

```
01 Intro & Preprocessing
        ↓
02 Linear Regression  (Supervised — Regression)
        ↓
03 Classification     (Supervised — Classification)
        ↓
04 Clustering         (Unsupervised)
```

## Topics at a Glance

- **Supervised Learning** — training on labelled data to predict continuous values (regression) or class labels (classification)
- **Unsupervised Learning** — discovering hidden structure in unlabelled data (clustering)
- **Data Preprocessing** — handling missing values, encoding categories, scaling features
- **Model Evaluation** — accuracy, MSE/R², confusion matrix, silhouette score
