# SharafDataScience-Clustering-Antarctic-Penguin-Species
# Penguin Clustering Analysis

This project supports a team of researchers studying penguin populations in Antarctica. The dataset provided (`penguins.csv`) contains biometric information about penguins, and the goal is to identify distinct species through unsupervised learning techniques such as clustering.

## Dataset Description

The dataset consists of the following columns:

| Column              | Description                    |
|---------------------|--------------------------------|
| `culmen_length_mm`  | Culmen (beak) length in mm     |
| `culmen_depth_mm`   | Culmen (beak) depth in mm      |
| `flipper_length_mm` | Flipper length in mm           |
| `body_mass_g`       | Body mass in grams             |
| `sex`               | Sex of the penguin             |

**Note**: The species of each penguin is not recorded, but the researchers know there are at least three: **Adelie**, **Chinstrap**, and **Gentoo**.

## Project Workflow

1. **Data Loading & Exploration**:
   - Load the penguin dataset using Pandas.
   - Display basic statistics and check for missing values.

2. **Preprocessing**:
   - Convert categorical variables into dummy/indicator variables.
   - Standardize numerical features using `StandardScaler`.

3. **Clustering**:
   - Apply K-Means clustering.
   - Determine optimal number of clusters (k) using methods like the elbow method.
   - Fit and predict clusters.

4. **Visualization**:
   - Visualize clusters with scatter plots and feature comparisons.
   - Analyze the distribution of features across clusters.

## 🛠Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Scikit-learn

## Goal

The primary goal is to uncover natural groupings within the penguin dataset that may correspond to different penguin species using unsupervised machine learning methods.

## 📎 References

- Data collected by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER.
- Scikit-learn documentation on clustering: https://scikit-learn.org/stable/modules/clustering.html
