# 📊Titanic-Data-Analysis-and-Visualization-with-Python-Libraries

# 📊 Titanic Dataset Analysis using Python

This project performs exploratory data analysis (EDA) on the Titanic dataset using Python libraries like **NumPy**, **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 🔧 Key Steps

- Imported essential Python libraries.
- Loaded the Titanic dataset using `pandas.read_csv()`.
- Displayed the first and last 10 rows of the dataset.
- Visualized missing values using a heatmap.
- Explored relationships and distributions using various plots and charts.

---

## 📊 Charts & Visualizations Explained

### 1. Heatmap (Missing Values)
This chart shows where data is missing in the dataset. It uses colors (like light blue or white) to highlight empty cells, helping you quickly see which columns or rows need cleaning.

### 2. Correlation Heatmap
This shows how strongly related the numeric columns are to each other. For example, it tells you if age and fare are related. The values range from -1 to 1:
- **1** = strong positive correlation  
- **-1** = strong negative correlation  
- **0** = no relationship  

### 3. Scatter Plot (Age vs Fare)
This chart places dots on a graph where the x-axis is **Age** and the y-axis is **Fare**. It shows how much people of different ages paid. Patterns or clusters can help identify trends or outliers.

### 4. Bar Chart
This chart uses rectangular bars to show the size of different categories. For example, it might show the number of people from each embarkation point. Taller bars mean more people.

### 5. Pie Chart
A circular chart divided into slices, where each slice shows the percentage of people from different categories (like ports: **S**, **Q**, and **C**). It helps compare parts of a whole.

### 6. Exploded Pie Chart
Similar to a normal pie chart, but one slice is pulled out to highlight it. It also shows exact percentages on each slice.

### 7. Histogram
This chart shows how data (like **Age**) is distributed across intervals. It’s like a bar chart but used for numerical ranges (e.g., how many people are aged 0–10, 10–20, etc.).

### 8. Box Plot
This shows the spread and outliers of numeric data. It includes:
- Minimum and maximum values  
- Median (middle value)  
- Quartiles (25% and 75%)  
Outliers appear as dots outside the box.

### 9. Line Plot
A line connects data points to show trends over a continuous variable like **age** or **time**. It’s good for visualizing patterns or changes.

### 10. Scatter Plot with Color Grouping
Same as a scatter plot, but each point is colored based on a category (e.g., **gender**). This helps compare groups visually on the same chart.

### 11. Strip Plot
A chart that plots individual points (like **fare prices**) grouped by a category (like **gender**). It's useful for spotting overlapping data points.

### 12. Violin Plot
A fancy version of a box plot. It shows the distribution shape (like a **violin**) and is good for comparing how data spreads across categories.

### 13. Pair Plot
This creates scatter plots for all pairs of numeric columns. It’s a quick way to see relationships between all variables in one view.

---

## 🛠 Tools & Libraries

- `numpy`
- `pandas`
- `matplotlib.pyplot`
- `seaborn`

---

## 📁 Dataset

The dataset used is the **Titanic Dataset**, commonly used for machine learning and data analysis practice. It includes passenger information like:
- Age
- Fare
- Sex
- Embarked (port)
- Survival status

---

## 📌 Objective

To understand the data and derive visual insights into survival patterns, missing values, and relationships among various features of Titanic passengers.

---

## 📷 Sample Visuals

> *(You can add screenshots of your visualizations here)*

---

## 📬 Contact

For any questions or feedback, feel free to reach out!

---

