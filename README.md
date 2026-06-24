# Iris Dataset Exploration and Visualization

A beginner-friendly data science notebook that explores the classic Iris dataset using Python.

## Objective
Load, inspect, and visualize the Iris dataset to understand data distributions and relationships between features.

## Dataset
- **Name:** Iris Dataset
- **Source:** Built-in via `seaborn.load_dataset('iris')`
- **Size:** 150 samples, 5 columns
- **Classes:** Setosa, Versicolor, Virginica

## What This Notebook Covers
- Loading data using **pandas**
- Inspecting structure with `.shape`, `.columns`, `.head()`
- Summary statistics with `.describe()` and `.info()`
- **Scatter plot** — relationship between sepal and petal length
- **Histograms** — distribution of all 4 features
- **Box plots** — spread and outliers per species
- **Pairplot** — all feature relationships at once

## Libraries Used
- `pandas`
- `matplotlib`
- `seaborn`

## How to Run
Open directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/iris-data-exploration/blob/main/iris_exploration.ipynb)

Or clone and run locally:
```bash
git clone https://github.com/YOUR_USERNAME/iris-data-exploration.git
```

## Key Findings
- Setosa is clearly separable from the other two species based on petal size
- Petal length and width are the most useful features for classification
- Sepal width contains a few outliers visible in the box plot
