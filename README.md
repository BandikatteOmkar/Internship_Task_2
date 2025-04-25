# Internship_Task_2
# Titanic Dataset - Exploratory Data Analysis (EDA)

This project explores the **Titanic dataset** using Python to extract meaningful insights through data visualization and summary statistics.

## 📂 Dataset

The dataset contains information about Titanic passengers such as:
- Passenger class
- Age
- Gender
- Fare paid
- Number of siblings/spouses (`SibSp`)
- Number of parents/children (`Parch`)
- Survival status

## 📊 Goals of this EDA

- Understand survival patterns based on gender, class, fare, and family size
- Visualize data distributions and relationships between variables
- Identify key factors contributing to survival

## 🔍 Key Observations

1. **Females** had the highest survival rate.
2. **1st class passengers** had better chances of survival.
3. People who **paid higher fares** were more likely to survive.
4. Passengers with **1–2 family members** had higher survival.
5. **Large families (4–6 members)** had lower chances of survival.

## 📁 Project Structure

- `Task2.ipynb` — Jupyter notebook containing all analysis, visualizations, and insights.

## 📦 Libraries Used

- pandas
- numpy
- matplotlib
- seaborn

## 📈 Visualizations Included

- Barplots (Survival by Sex, Class, Embarkation)
- Boxplots and Violin plots (Fare vs Survival)
- Correlation heatmap
- Histogram distributions
- Family size vs Survival

## 🚀 Getting Started

1. Clone the repo or download the notebook.
2. Make sure the Titanic dataset CSV is available in the correct path.
3. Run the notebook in a Jupyter environment (like JupyterLab, Google Colab, or VS Code).

```bash
pip install pandas numpy matplotlib seaborn
