# Treadmill Buyer Profile - EDA (Exploratory Data Analysis)

## Project Overview
This project aims to analyze the characteristics of customers who purchase treadmills from AeroFit, specifically identifying differences in customer demographics and preferences across various product types (KP281, KP481, and KP781). The goal is to provide actionable insights that will help AeroFit make better recommendations to new customers based on their profile.

### Product Portfolio:
- **KP281**: Entry-level treadmill ($1,500)
- **KP481**: Mid-level treadmill ($1,750)
- **KP781**: Advanced treadmill ($2,500)

### Data Description:
The dataset, `aerofit_treadmill_data.csv`, contains the following columns:
- **Product**: Treadmill purchased (KP281, KP481, or KP781)
- **Age**: Customer's age (in years)
- **Gender**: Customer's gender (male/female)
- **Education**: Customer's education level (in years)
- **MaritalStatus**: Marital status (single/partnered)
- **Usage**: Average weekly usage (times per week)
- **Fitness**: Self-rated fitness on a scale from 1 (poor) to 5 (excellent)
- **Income**: Customer's annual income (in USD)
- **Miles**: Average weekly miles walked/run

## Analysis Summary
### 1. Data Exploration and Processing
- **Data Import**: Read the dataset into a DataFrame.
- **Shape and Structure**: Checked the dimensions and data types of the columns.
- **Missing Values**: Detected and handled missing values appropriately.
- **Duplicate Values**: Checked and removed any duplicates.

### 2. Statistical Summary
- A brief analysis of the statistical summary of both categorical and numerical features, highlighting key patterns.

### 3. Non-Graphical Analysis
- **Value Counts**: Analyzed the distribution of categorical features like `Product`, `Gender`, `MaritalStatus`, etc.
- **Unique Attributes**: Listed unique values for categorical features.

### 4. Graphical Analysis
- **Univariate Analysis (Numerical Features)**:
  - Distribution plot, count plot, and box plot for features like `Age`, `Income`, `Miles`, etc.
- **Univariate Analysis (Categorical Features)**:
  - Count plot for categorical features like `Product`, `Gender`, `MaritalStatus`.
- **Bivariate Analysis**:
  - Analyzed the effect of features on the product purchased, such as:
    - Product vs Gender
    - Product vs MaritalStatus
    - Product vs Age
- **Multivariate Analysis**:
  - Created pairplots to explore relationships between different features.

### 5. Correlation Analysis
- Visualized the correlation matrix using a heatmap to analyze relationships between numerical features.

### 6. Outlier Detection
- Applied the IQR (Interquartile Range) method to detect outliers in numerical features.

### 7. Conditional Probabilities
- Calculated conditional probabilities for various combinations of features like:
  - Product vs Gender
  - Product vs Age
  - Product vs Income
  - Product vs Fitness
  - Product vs MaritalStatus

### 8. Actionable Insights & Recommendations
- Provided insights on customer behavior and trends, such as:
  - The profile of customers most likely to purchase specific treadmill models.
  - Recommendations for targeted marketing based on customer demographics and preferences.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Files
- `aerofit_treadmill_data(1).ipynb`: The Jupyter notebook with all the exploratory data analysis and visualizations.
- `README.md`: Project overview and details.

## How to Run the Analysis
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Treadmill-Buyer-Profile-EDA.git
