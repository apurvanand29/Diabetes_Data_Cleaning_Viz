# Diabetes Dataset Cleaning Project

This project involves cleaning a Diabetes dataset to handle missing values, misspelled words, outliers, and duplicate values. The cleaned data can now be used for drawing trends and insights.

## Dataset

The dataset used for this project is sourced from the file `diabetes_unclean.csv`.

## Cleaning Steps

The cleaning process includes the following steps:

1. **Importing Libraries**: Utilize libraries such as Pandas for data manipulation and Seaborn for data visualization.
2. **Reading Data**: Load the CSV file containing the uncleaned Diabetes data.
3. **Handling Column Names**: Rename columns to ensure consistency and clarity.
4. **Handling Missing Values**: Identify and replace missing values with appropriate substitutes such as mean values, and remove rows with remaining missing values.
5. **Handling Mis-spelled Words**: Correct any misspellings in the data columns, ensuring uniformity in categorical data.
6. **Handling Outliers**: Detect and remove outliers using statistical methods to ensure data integrity.
7. **Handling Duplicate Values**: Identify and remove duplicate rows to avoid redundant data.
8. **Saving Cleaned Data**: Save the cleaned dataset to a new CSV file for further analysis.

## Results

The cleaned dataset is saved as `Cleaned_Diabetes_Data.csv`. This dataset is now free from missing values, misspelled words, outliers, and duplicates, making it suitable for further analysis to draw trends and insights about Diabetes.

## Usage

To use this cleaned dataset, load the `Cleaned_Diabetes_Data.csv` file into your data analysis or visualization tool of choice. The dataset is ready for any statistical analysis, machine learning modeling, or visualization to uncover insights related to Diabetes.

