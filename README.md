# Mohamed Sherief

👋 Hi there! I'm **Mohamed Sherief**, a passionate **Data Analyst** with a focus on using **Python**, **Jupyter Notebooks**, and **Power BI** to analyze and visualize data. I specialize in turning raw data into actionable insights and am always expanding my skillset to stay ahead in the world of data analytics.

🔎 Currently honing my skills in data analysis, data visualization, and machine learning techniques.

---

### 🚀 About Me:
I specialize in:

- **Data Wrangling and Cleaning**: Using **Pandas** to transform raw data into clean datasets.
- **Exploratory Data Analysis (EDA)**: Leveraging statistical techniques and **visualization** tools to uncover patterns.
- **Data Visualization**: Using **Matplotlib**, **Seaborn**, and **Power BI** to create impactful, easy-to-understand visualizations.
- **Jupyter Notebooks**: My go-to environment for documenting and sharing my data analysis workflows.

---

### 🛠️ Tools & Technologies

- **Programming Languages**: Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Data Visualization**: Power BI, Matplotlib, Seaborn
- **Data Analysis**: Jupyter Notebooks, Pandas, NumPy
- **Database & SQL**: SQL, MySQL
- **Version Control**: Git, GitHub
- **Other Tools**: Excel, Google Colab, Tableau (learning)

---

### 📊 Mockup Data: Python & Power BI Example

Here’s a simple mockup of a dataset and its analysis workflow in Python that I often use for practice:

#### Mockup Data: Sales Data

| Date       | Product Category | Region | Sales Amount | Units Sold |
|------------|------------------|--------|--------------|------------|
| 2023-01-01 | Electronics       | North  | 1000         | 50         |
| 2023-01-01 | Clothing          | South  | 500          | 30         |
| 2023-01-02 | Electronics       | East   | 1200         | 60         |
| 2023-01-02 | Furniture         | West   | 800          | 40         |
| 2023-01-03 | Clothing          | North  | 700          | 35         |

#### Python Analysis Workflow:

```python
import pandas as pd
import matplotlib.pyplot as plt

# Sample data
data = {
    'Date': ['2023-01-01', '2023-01-01', '2023-01-02', '2023-01-02', '2023-01-03'],
    'Product Category': ['Electronics', 'Clothing', 'Electronics', 'Furniture', 'Clothing'],
    'Region': ['North', 'South', 'East', 'West', 'North'],
    'Sales Amount': [1000, 500, 1200, 800, 700],
    'Units Sold': [50, 30, 60, 40, 35]
}

# Create DataFrame
df = pd.DataFrame(data)

# EDA: Plotting sales data by category
category_sales = df.groupby('Product Category')['Sales Amount'].sum()

category_sales.plot(kind='bar', title='Sales Amount by Product Category')
plt.xlabel('Product Category')
plt.ylabel('Sales Amount')
plt.show()
````

This Python code demonstrates how I analyze sales data by category, performing **Exploratory Data Analysis (EDA)** and visualizing the results with **Matplotlib**.

In **Power BI**, I would use similar datasets to create interactive dashboards, allowing business stakeholders to filter and drill down into the sales data by region, product category, or date.

---

### 📚 Skills & Technologies

* **Data Analysis & Manipulation**:

  * **Python**: Pandas, NumPy
  * **Jupyter Notebooks**: My primary tool for analysis, sharing notebooks, and collaboration.
  * **SQL**: Basic to intermediate query writing for data extraction.

* **Data Visualization**:

  * **Power BI**: Creating interactive dashboards and reports.
  * **Matplotlib** & **Seaborn**: For creating charts, graphs, and plots in Python.

* **Other Tools**:

  * **Excel**: Advanced Excel functions and analysis (PivotTables, VLOOKUP, etc.)
  * **Tableau**: Learning data visualization in Tableau for more complex use cases.

---

### 📫 How to reach me:

* **Email**: [mohamedsherief760@gmail.com](mailto:mohamedsherief760@gmail.com)
* **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/mohamed-sherief-6629ba118/)
* **Kaggle**: [Kaggle Profile](#)

---

### 🌱 What I’m Currently Learning:

* **Machine Learning**: Applying machine learning algorithms to real-world datasets.
* **Advanced SQL**: Optimizing queries for large datasets.
* **Advanced Power BI**: Learning advanced DAX and Power Query.

---

### 🌍 Fun Fact:

Outside of data analytics, I enjoy \[add personal interests or hobbies, e.g., reading, photography, cooking].

---

### 🔗 Let's Connect:

Feel free to check out my [LinkedIn Profile](https://www.linkedin.com/in/mohamed-sherief-6629ba118/) and my repositories for more on my data analytics journey.


---

### Customization Notes:
- I added a simple **mockup dataset** with sales data and provided an example of Python analysis.
- If you plan to upload a project related to **Power BI**, you can create a folder for it, link to it here, and explain your visualizations.
- For future projects, you can replace the "mockup data" section with any real-world datasets and analysis you work on.

Let me know if you want to tweak any part of this, or if you'd like help setting up a particular section!
```
