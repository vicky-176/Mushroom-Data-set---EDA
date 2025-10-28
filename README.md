# EDA on Mushroom Dataset

This project presents a detailed Exploratory Data Analysis (EDA) of the Mushroom dataset. The dataset includes records describing various hypothetical mushroom species, classified as either edible or poisonous based on a range of physical characteristics.

## File Included
- **eda on mushroom.ipynb** — a Jupyter notebook containing all steps of the exploratory analysis, including data inspection, feature exploration, and visualizations.

## Dataset Overview
Each entry in the dataset represents a mushroom, described entirely through categorical attributes such as **cap shape**, **cap color**, **gill size**, **gill color**, **stalk shape**, and **odor**.

The target variable, **class**, indicates whether a mushroom is:
- **e** – edible  
- **p** – poisonous  

All features are categorical in nature, making this dataset suitable for statistical and visual exploration of categorical data relationships.

## Structure of the EDA

### 1. Univariate Analysis
- Frequency plots and count charts for each categorical variable  
- Analysis of the class distribution (edible vs poisonous)  
- Examination of the most common feature values  

### 2. Bivariate Analysis
- Exploration of relationships between each feature and the target variable  
- Evaluation of feature importance using chi-square tests  
- Comparative visualizations with bar and stacked plots  

### 3. Multivariate Analysis
- Correlation assessment using encoded variables  
- Pairplots for selected combinations of attributes  
- Detection of multicollinearity among features  

## Techniques and Tools
- **pandas**, **numpy** for data processing and manipulation  
- **matplotlib**, **seaborn** for data visualization  
- **LabelEncoder** for encoding categorical data  
- **Chi-square test** for measuring association between variables  

## Key Findings
- Attributes such as **odor**, **gill color**, and **spore print color** show strong distinctions between edible and poisonous mushrooms.  
- Certain features provide near-perfect separation, making them highly valuable for decision-tree or rule-based classification models.  
- The dataset contains no significant missing values, allowing for straightforward preprocessing and analysis.
