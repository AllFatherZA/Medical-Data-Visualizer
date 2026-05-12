---

# Medical Data Visualizer

A **Python + Pandas + Seaborn** project that cleans and analyzes medical examination data, then visualizes categorical distributions and correlations. Built as part of the [freeCodeCamp Data Analysis with Python Certification](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/medical-data-visualizer).

## 📖 Project Description
This project processes patient medical records to highlight relationships between lifestyle factors and cardiovascular disease. It normalizes categorical features, generates bar plots to compare distributions, and draws a heatmap to reveal correlations between variables.

---

## 🚀 Features
- **Data Cleaning**
  - Removes incorrect records (e.g., diastolic > systolic).
  - Filters outliers in height and weight (outside 2.5th–97.5th percentiles).
- **Normalization**
  - Converts `cholesterol` and `gluc` into binary flags (`0` = normal, `1` = above normal).
  - Adds an `overweight` column based on BMI > 25.
- **Visualizations**
  - **Categorical Plot:** Shows counts of lifestyle/health indicators split by cardiovascular disease (`cardio`).
  - **Heatmap:** Displays correlations between medical variables.

---

## 🛠️ Tech Stack
- [Python 3](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

---

## ⚙️ Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/AllFatherZA/Medical-data-visualizer.git
   cd Medical-data-visualizer
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook medical_data_visualizer.ipynb
   ```

---

## 📊 Visualizations
### Categorical Plot
- Compares distributions of features (`cholesterol`, `gluc`, `overweight`, `active`, `smoke`, `alco`) split by cardiovascular disease (`cardio`).

### Heatmap
- Shows correlations between variables after cleaning the dataset.
- Highlights relationships such as blood pressure vs. cardiovascular disease.

---

## 👨‍💻 Author
- GitHub: AllFatherZA
- Project Maintainer: **Sibusiso Mnyandeni**

---
