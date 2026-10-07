# 🌸 Iris Dataset – Exploratory Data Analysis (EDA)

## 📌 Overview
This project performs Exploratory Data Analysis on the classic Iris dataset using Python. It uses Pandas, NumPy, Matplotlib, and Seaborn to understand the data, find relationships between measurements, and visualize patterns that separate the three species.

## 🎯 Objectives
- Load and understand the Iris dataset
- Explore rows, columns, and data types
- Generate statistical summaries
- Check for missing values and duplicate records
- Analyze relationships between numerical features
- Create visualizations to identify patterns in sepal and petal measurements

## 🌿 About the Data
The dataset contains **150 records** of three Iris species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

A **sepal** is the outer part of the flower that protects the bud, and a **petal** is the colorful part that attracts insects.

### Feature Measurements

![Iris flower showing petal length, petal width, sepal length, and sepal width](images/iris_measurements.png)

| Feature | Description |
|---|---|
| SepalLengthCm | Length of the sepal |
| SepalWidthCm | Width of the sepal |
| PetalLengthCm | Length of the petal |
| PetalWidthCm | Width of the petal |
| Species | Target label |
| Id | Row identifier (not used as a feature) |

Dataset file: `Iris.csv` (150 rows × 6 columns)

## 🛠️ Technologies
Python • Pandas • NumPy • Matplotlib • Seaborn • Google Colab

## 📊 EDA Performed
1. Dataset loading
2. First 5 rows
3. Shape and column names
4. Data types
5. Missing value analysis
6. Duplicate analysis
7. Correlation matrix and heatmap
8. Scatter plot
9. Histograms
10. Box plot
11. Pair plot
12. Key insights

## 🔍 Key Insights
- 150 flower records, 3 species, no missing values.
- No duplicate rows when `Id` is included (check duplicates on the four measurements alone, since the original Iris data has a few repeated rows).
- **PetalLengthCm and PetalWidthCm** have the strongest correlation (**0.96**).
- **SepalLengthCm and PetalLengthCm** are strongly positively correlated (**0.87**).
- Iris-setosa has the smallest petal measurements and is clearly separable.
- Iris-virginica generally has the largest petals.
- Petal measurements are the most useful for distinguishing species.

## 📈 Visualizations
- **Correlation heatmap:** relationships between numerical features
- **Scatter plot:** sepal length vs. petal length
- **Histograms:** distribution of each measurement
- **Box plot:** spread and possible outliers
- **Pair plot:** pairwise relationships across all four measurements

## ▶️ How to Run
```bash
pip install pandas numpy matplotlib seaborn
```
Open the notebook in Google Colab or Jupyter, place `Iris.csv` in the same folder, and run all cells.

## 📁 Project Structure
```
├── README.md
├── Iris.csv
├── iris_eda.ipynb
└── images/
    └── iris_measurements.png
```

## 📝 Conclusion
The dataset is clean, well structured, and suitable for further statistical analysis or machine learning. Petal length and petal width are especially effective at separating the three Iris species.

## 👤 Author
**Prathana Kamlesh Tandel**
