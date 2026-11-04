# 🍽️ Dining Dynamics & Tipping Behaviour – Exploratory Data Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing restaurant dining data using **Python, Matplotlib, NumPy, Pandas, and Seaborn**. It explores the relationship between customers' total bills, tipping behaviour, dining days, and party sizes.

The project uses the built-in **Seaborn Tips Dataset** to perform Exploratory Data Analysis (EDA) and create a visually appealing dashboard containing four different visualizations.

The main objective is to understand customer spending patterns and tipping behaviour through effective data visualization.

## 🎯 Project Objectives

- Analyze average restaurant bills across different days of the week.
- Understand the relationship between total bills and tip amounts.
- Examine how party size affects tipping behaviour.
- Identify relationships between numerical variables using correlation analysis.
- Present meaningful insights through a 2×2 visualization dashboard.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Google Colab | Development environment |

## 📊 Visualizations Included

The project contains four major visualizations:

### 1. Bar Chart – Average Bill by Day
- Compares average restaurant bills across Thursday, Friday, Saturday, and Sunday.
- Helps identify which days have higher customer spending.

### 2. Scatter Plot – Total Bill vs Tip
- Shows the relationship between customers' total bills and tip amounts.
- Uses different colours to distinguish lunch and dinner customers.
- Includes a regression line to highlight the overall trend.

### 3. Box Plot – Tip by Party Size
- Examines how tipping amounts vary according to the number of diners.
- Displays the median, distribution, and outliers for different party sizes.

### 4. Correlation Heatmap
- Displays the correlation between numerical variables.
- Helps identify strong and moderate relationships between variables.
- Uses colour intensity and correlation values for easy understanding.

## 🔍 Key Takeaways

1. **Spending Patterns:** Sunday records the highest average spending among the four dining days.
2. **Bill and Tip Relationship:** Customers generally give higher tips when their total bills increase.
3. **Party Size:** Median tip amounts generally increase with party size, although individual tipping behaviour varies.
4. **Correlation Analysis:** Total bill and tip show a strong positive correlation, indicating that higher bills are generally associated with higher tips.

## 📁 Project Structure

```text
Dining-Dynamics-Tipping-Behaviour/
│
├── Matplotlib_Seaborn_Tips_Project.ipynb
│
├── tips_data_dashboard.png
│
└── README.md
```

## 🚀 How to Run the Project

You can execute this project using Google Colab without installing Python or any additional software.

**Step 1:** Open [Google Colab](https://colab.research.google.com/).

**Step 2:** Upload the `Matplotlib_Seaborn_Tips_Project.ipynb` notebook.

**Step 3:** Run all the code cells using **Runtime → Run all**.

**Step 4:** The notebook automatically loads the Seaborn Tips Dataset.

**Step 5:** The four visualizations will be generated as a dashboard.

**Step 6:** The dashboard image will be saved as `tips_data_dashboard.png`.

## 📈 Expected Output

The final output is a 2×2 dashboard containing:

- Average Bill by Day – Bar Chart
- Total Bill vs Tip – Scatter Plot
- Tip by Party Size – Box Plot
- Numerical Relationships – Correlation Heatmap

The dashboard provides a clear visual understanding of restaurant spending and customer tipping patterns.

## 📂 Dataset Information

**Dataset:** Seaborn Tips Dataset

The dataset contains restaurant information, including:

- Total Bill
- Tip
- Gender
- Smoker Status
- Day
- Time (Lunch/Dinner)
- Party Size

The dataset is loaded directly using:

```python
tips = sns.load_dataset("tips")
```

## 💡 Conclusion

This project demonstrates how Python libraries can be used to perform Exploratory Data Analysis and transform raw data into meaningful visual insights.

Through different visualization techniques, the project helps identify customer spending patterns, understand tipping behaviour, and explore relationships between dining variables.

It also provides practical experience in data analysis, statistical visualization, and dashboard creation.

## 👩‍💻 Author

**Swetha**

*Aspiring Data Analyst*

---

⭐ If you find this project useful, feel free to explore and connect!
