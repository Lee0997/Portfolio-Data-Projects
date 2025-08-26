# Student Performance Analysis

This project analyzes student performance data to uncover insights and build predictive models. The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, model building, and visualization.

## Project Structure

- **data/**: Contains the raw dataset (`StudentsPerformance.csv`).
- **notebooks/**: Jupyter notebooks for each stage of the analysis:
  - `Data_Cleaning.ipynb`: Data preprocessing and cleaning steps.
  - `EDA.ipynb`: Exploratory data analysis to understand trends and patterns.
  - `Modelling.ipynb`: Machine learning model development and evaluation.
  - `Visualisation.ipynb`: Visualizations for insights and results.
- **scripts/**: (Optional) Python scripts for reusable functions or automation.

## Dataset

The dataset (`StudentsPerformance.csv`) includes information on students' scores in math, reading, and writing, along with demographic and background variables such as gender, race/ethnicity, parental level of education, lunch type, and test preparation course.

## How to Use

1. **Clone the repository** and navigate to the `student-performance` folder.
2. **Install dependencies** (see below).
3. **Open the notebooks** in Jupyter or VS Code and run the cells in order.

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install requirements with:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Project Steps

1. **Data Cleaning**: Handle missing values, correct data types, and prepare the dataset for analysis.
2. **EDA**: Explore distributions, relationships, and key statistics.
3. **Feature Engineering**: Encode categorical variables and select features for modeling.
4. **Modeling**: Train and evaluate machine learning models to predict student performance.
5. **Visualization**: Create plots and charts to communicate findings.

## License

This project is licensed under the MIT License.
