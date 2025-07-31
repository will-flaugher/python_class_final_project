# Impact of Price on Product Ratings: Amazon India Analysis

This repository contains the final project for UNC's "Introduction to Python for Business Analytics" course, completed by Kwabena Frimpong, Isabel Karst, Paul Nolan, William Flaugher, and Hao Sun.

## 📌 Project Summary

This project analyzes Amazon India product data to explore how pricing, discounting, and product category relevance influence customer behavior, specifically in terms of review count and product ratings.

We used Python for data cleaning, exploratory data analysis, hypothesis testing, and visualization. The project culminates in both a Jupyter Notebook and a final presentation slide deck.

## 📁 Repository Structure

python_class_final_project/
│
├── README.md
├── final_project.ipynb #Jupyter Notebook with data prep, analysis, and results
└── final_slides.pdf #Slide deck summarizing methodology and findings


## ❓ Research Questions

1. Do larger discounts correlate with more product reviews?
2. Do higher-priced products receive better average ratings?
3. Do more "personally significant" categories (e.g., clothing, beauty) elicit more customer engagement?

## 📊 Summary of Findings

- **Discount size** had minimal influence on review count.
- **Price** was positively correlated with product ratings.
- **Category relevance** showed some impact on review volume, but this effect weakened after removing outliers.

## 🧰 Tools & Libraries

- Python 3.x
- pandas, matplotlib, seaborn, numpy
- Jupyter Notebook

## 📦 How to Run

1. Clone or download the repository.
2. Ensure the `data/amazondata.csv` file is in place.
3. Open `final_project.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all cells to replicate the analysis and visualizations.

To install any required libraries:

```bash
pip install pandas numpy matplotlib seaborn


## 📎 References
Dataset: Amazon Products – India (Kaggle)


Project submitted solely for academic purposes. Maintained by Will Flaugher.
