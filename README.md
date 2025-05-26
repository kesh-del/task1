# 💎 Diamonds Dataset Cleaning & Visualization

This project demonstrates a full data preprocessing and exploratory data analysis (EDA) pipeline using the [Diamonds Dataset](https://www.kaggle.com/datasets/shivam2503/diamonds). It involves cleaning, encoding, visualization, outlier handling, and normalization using Pandas, NumPy, Matplotlib, and Seaborn in Python.

---

## 📂 Dataset Source
- Kaggle: [https://www.kaggle.com/datasets/shivam2503/diamonds](https://www.kaggle.com/datasets/shivam2503/diamonds)
- File used: `diamonds.csv`

---

## 🧰 Libraries Used
- Python 3.x
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 📌 Steps Covered

### 1. Load and Explore the Dataset
- View basic statistics
- Check for null values
- Understand data types

### 2. Encode Categorical Columns
- Converted `cut`, `color`, and `clarity` into numeric values using category encoding.

### 3. Data Visualization
- Histogram of price distribution
- Boxplot for outliers in price
- Heatmap of feature correlations

### 4. Outlier Removal
- Used IQR method to remove outliers from `price` column.

### 5. Feature Scaling
- Standardized numerical features using `StandardScaler`.

---

## 📊 Visual Outputs
- Histograms
- Boxplots
- Correlation Heatmap

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diamonds-cleaning-visualization.git
   cd diamonds-cleaning-visualization
Install dependencies (optional if using Colab):

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Run the notebook:

Open diamonds_colab.ipynb in Google Colab

🧠 Author
Abhishek
