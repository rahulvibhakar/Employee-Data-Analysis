```markdown
# Employee Data Analysis

A Streamlit-based employee analytics dashboard that helps explore workforce data, visualize trends, and predict key outcomes such as churn, turnover probability, and salary.

## Overview

This project analyzes employee dataset records and provides interactive visual insights for:

- Employee overview and summary statistics
- Department-wise and gender-wise attrition analysis
- Data visualizations (histograms, scatter plots, box plots)
- Employee clustering using K-Means
- Employee churn prediction using Random Forest
- Turnover probability using Logistic Regression
- Salary prediction using Linear Regression

## Features

- Interactive filtering by department, gender, and age range
- Real-time data summaries and descriptive statistics
- Advanced analytics including skewness and kurtosis
- Visualization dashboard for insights
- ML-based prediction models for business use cases
- Easy-to-use Streamlit interface

## Tech Stack

- Python
- Streamlit
- Pandas
- OpenPyXL
- Matplotlib
- Seaborn
- Scikit-learn
- Folium
- SciPy

## Project Structure

```bash
Employee-Data-Analysis/
├── employee.py
├── Employee.xlsx
├── README.md
├── portfolio.css
└── tasks.json
```

## Dataset

The app reads the Excel file:

- `Employee.xlsx`

Make sure the dataset is present in the project root and contains the sheet named:

- `Employee Sample Data`

## Installation

1. Clone the repository:
```bash
git clone https://github.com/rahulvibhakar/Employee-Data-Analysis.git
cd Employee-Data-Analysis
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install streamlit pandas openpyxl matplotlib scikit-learn seaborn folium scipy
```

## Run the App

```bash
streamlit run employee.py
```

Then open the local URL shown in the terminal, usually:

```bash
http://localhost:8501
```

## Usage

From the sidebar, select the analysis type such as:

- Overview
- Visualization
- Clustering
- Churn Prediction
- Attrition Analysis
- Turnover Probability
- Salary Prediction

Apply filters for department, gender, and age range to analyze a specific workforce segment.

## Example Analysis Modules

### Overview
Displays dataset head, summary statistics, and descriptive analytics.

### Visualization
Generate histograms, scatter plots, and box plots for several columns.

### Clustering
Groups employees based on selected variables like age and salary using K-Means.

### Churn Prediction
Predicts whether an employee may churn using a Random Forest model.

### Attrition Analysis
Measures attrition by department and gender, with correlation heatmaps.

### Turnover Probability
Estimates turnover likelihood using logistic regression.

### Salary Prediction
Predicts annual salary using an employee regression model.

## License

This project is intended for educational and analytical purposes.

## Author

Rahul Vibhakar
```
