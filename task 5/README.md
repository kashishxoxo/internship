#  Titanic Dataset Exploratory Data Analysis (EDA)

This project performs an exploratory data analysis (EDA) on the Titanic dataset to uncover key patterns and relationships that influenced passenger survival rates.

##  Dataset

The dataset used is `train.csv` from the [Kaggle Titanic Machine Learning Challenge](https://www.kaggle.com/c/titanic/data), containing information on passengers including demographics, ticket class, fare paid, and survival status.

##  Tools & Environment

- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** and **Seaborn** for data visualization
- **Jupyter Notebook** via **Visual Studio Code (VS Code)** for interactive analysis

##  Analysis Performed

### 1. Basic Data Exploration

- Displayed first few rows, dataset info, and summary statistics
- Checked for missing values
- Explored distributions of key categorical variables: `Survived`, `Sex`, and `Pclass`

### 2. Data Cleaning

- Encoded `Sex` as numerical (`Sex_encoded`)
- Dropped rows with missing `Age` values for heatmap and pairplot analysis

### 3. Correlation Heatmap

- Visualized correlation between features like `Sex_encoded`, `Pclass`, `Age`, `Fare`, and `Survived`

### 4. Pairplot Analysis

- Examined relationships between features colored by survival status

### 5. Visualizations

- **Histogram** of Age distribution
- **Boxplot** of Age vs Survival
- **Scatterplot** of Fare vs Age, colored by Survival

##  Key Insights

### Passenger Class and Survival

- Passengers in **1st class** had significantly higher survival rates
- Suggests **socioeconomic status** impacted access to lifeboats

### Gender and Survival

- **Females** had a much higher chance of survival
- Reflects the **"women and children first"** evacuation policy

###  Fare Paid and Survival

- Higher fare-paying passengers had better survival rates
- Indicates a correlation between **ticket price** and **rescue likelihood**

###  Age and Survival

- **Children** had slightly better survival odds
- Supports prioritization of the young during evacuation



