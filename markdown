# 🚲 Bike Buyers Data Analysis Dashboard

This repository contains a Python-based data analysis and visualization project using an Excel dataset about bike buyers. It includes gender, age, income, and purchase behavior, visualized using `matplotlib` and `pandas`.

---

## 📁 Dataset Overview

The dataset is loaded from an Excel file with the following relevant columns:

- `Gender`
- `Age`
- `Income`
- `Region`
- `Purchased Bike`

We focus primarily on analyzing gender distribution, regional sales, age-wise buying patterns, and purchase behavior.

---

## 📊 Visualizations

### 1. Gender-wise Bike Purchases (Pie Chart)

We first explore the proportion of purchases made by males and females using a pie chart.

![Gender Pie Chart](images/gender_pie_chart.png)

**Insights:**
- The purchase distribution is quite balanced between males and females.
- Gender does not significantly skew bike-buying behavior.

---

### 2. Region-wise Bike Purchases (Bar Chart)

This bar chart shows the number of bike purchases per region.

![Region Bar Chart](images/region_bar_chart.png)

**Insights:**
- Europe leads in purchases, followed by Pacific.
- Market opportunities exist in underperforming regions.

---

### 3. Age-wise Bike Purchases (Line Chart)

A line chart visualizes how purchases vary with age. Small labels on each point help identify exact purchase counts.

![Age Line Chart](images/age_line_chart.png)

**Insights:**
- Purchases are strong among individuals aged 30–50.
- Trends suggest targeting middle-aged customers for bike marketing.

---

### 4. Combined Dashboard

All three visualizations above are combined into a single dashboard view for a quick overview.

![Combined Dashboard](images/combined_dashboard.png)

This layout allows comparison across demographics and behavior at a glance.

---

### 5. Gender & Purchase Status Comparison (Grouped Column Chart)

A grouped column chart shows how many male and female customers purchased or did not purchase a bike.

![Grouped Column Chart](images/gender_purchase_column_chart.png)

**Insights:**
- Gender-wise distribution is fairly even.
- A slight majority of individuals (regardless of gender) did not purchase a bike.

---

### 6. Gender and Purchase Status as Separate Categories

For clarity, gender and purchase status are visualized as four distinct bars: Male, Female, Purchased, and Not Purchased.

![Separated Category Column Chart](images/separated_category_column_chart.png)

This offers a clearer breakdown between demographics and purchasing behavior.

---

## 🧰 Tools Used

- Python 3.x
- Jupyter Notebook
- pandas
- matplotlib
- openpyxl (for Excel import)

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bike-buyers-dashboard.git
   cd bike-buyers-dashboard
