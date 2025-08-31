# Data-Visualization-project

This project explores the **Breast Cancer Wisconsin (Diagnostic) dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)). The aim is to apply a range of visualisation techniques to better understand the dataset, highlight patterns, and distinguish between **benign** and **malignant** diagnoses.  

---

## Project Overview  

The project demonstrates how visualisation can support exploratory data analysis by:  

- Highlighting correlations between features.  
- Showing class separability (benign vs malignant) across multiple attributes.  
- Identifying trends, outliers, and redundancies in the dataset.  

The workflow includes:  

1. **Heatmap (Correlation Plot)** – Uses Pearson correlation to examine relationships between features.  
2. **Beeswarm Plot (Quasirandom)** – Helps avoid overplotting and makes the separation between benign and malignant cases clearer.  
3. **Histogram** – Displays feature distributions, highlighting which features best separate diagnoses.  
4. **Scatter Plots with Ellipses** – Provides confidence regions to show overlap or separability between classes.  

---

## Dataset  

The dataset contains diagnostic features of breast cancer cases, with each feature having three variations:  

- **Mean**  
- **Standard error (SE)**  
- **Worst**  

The target variable indicates whether a case is **Benign (B)** or **Malignant (M)**.  

---

## Visualisations  

- **Heatmap**: Shows the strength and direction of correlations between features.  
- **Beeswarm plots**: Display individual data points without overlap, aiding visual comparison across 30 features.  
- **Histograms**: Reveal variance within features and show how well they separate diagnoses.  
- **Scatter plots with ellipses**: Illustrate 95% confidence regions to highlight areas of overlap and separation between classes.  

---

## Key Findings  

- Visualisation helps in identifying **redundant features** with high correlation.  
- Certain features clearly separate benign and malignant cases, while others show heavy overlap.  
- Scatter plots with confidence ellipses provide a more nuanced view of class separability.  

---

## Technologies Used  

- Python  
- Matplotlib / Seaborn  
- Pandas / NumPy  

---

## How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/breast-cancer-visualisation.git
   cd breast-cancer-visualisation
