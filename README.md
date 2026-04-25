# Experiment 17: Statistical and Specialised Data Visualisation
# Arddra Soni
# PRN:25070123022
# ENTC A1
## Overview

This experiment explores statistical and specialised visualisation techniques using two datasets — a small categorical sales dataset and a simulated 100-row customer loan dataset.

---

## Libraries Used

| Library | Purpose |
|---------|---------|
| **Pandas** | Creating and managing DataFrames |
| **NumPy** | Generating random data reproducibly |
| **Matplotlib** | Core plotting — area, pie, box, histogram, bubble charts |
| **Seaborn** | Styled boxplots, heatmaps, and enhanced scatter plots |

---

## Datasets

**Dataset 1 — Sales Data (5 rows):** Categories A–E with Values, Sales, and Profit columns.

**Dataset 2 — Loan Data (100 rows):** Customer Age, Income, Loan Amount, Credit Score, and a derived Loan Status (Approved if Credit Score > 600).

---

## Charts Used

| Chart | Key Idea |
|-------|----------|
| **Area Plot** | Shows magnitude over categories using `fill_between()` |
| **Dual Area Plot** | Overlays Sales and Profit areas for comparison |
| **Pie Chart** | Shows each category's share of the total |
| **Exploded Pie Chart** | Highlights a specific slice by pulling it outward |
| **Donut Chart** | Pie chart with a white circle cut from the centre |
| **Boxplot** | Shows spread, median, and outliers of a distribution |
| **Histogram** | Shows frequency distribution of credit scores |
| **Correlation Heatmap** | Colour-coded matrix of pairwise correlations between variables |
| **Basic Bubble Plot** | Scatter plot where bubble size encodes a third variable |
| **Advanced Bubble Plot** | Encodes four variables using x, y, size, and colour |

---

## Conclusion

This experiment moves beyond basic charts to cover tools for **distribution analysis** (boxplots, histograms), **composition** (pie/donut), **magnitude** (area), **correlation** (heatmaps), and **multi-variable relationships** (bubble plots) — forming the core toolkit for statistical data exploration in Python.
