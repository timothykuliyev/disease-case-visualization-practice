# disease-case-visualization-practice
This project analyzes and visualizes flu case data using Python. It demonstrates data processing with Pandas, statistical analysis with SciPy, and visualization with Matplotlib. The purpose of the project was to gain some practice utilizing the different libraries typically used in data analysis.

## Features

 - Reads a dataset (flu_case_data.csv)

 - Cleans and processes the data

 - Checks for valid variables before analysis

 - Performs correlation analysis using scipy.stats.linregress

 - Generates scatter plots with regression lines

## Installation

To run this project, install the necessary dependencies:
 - matplotlib
 - pandas
 - scipy

## Usage

Run the main.py script:

Expected Output

 - A scatter plot visualizing the correlation between selected variables

 - A printed statistical summary, including the regression equation, R-squared value, and p-value

## File Structure

disease-case-analytics

|---- flu_case_data.csv

|---- main.py

|---- README.md

|---- requirements.txt

## Notes

 - The dataset is artificially generated for practice.

 - The script automatically checks whether the selected variables can be compared.

 - If no valid data remains after cleaning, the script exits.

## Next steps
 - Use more advanced linear regression models (OLS, non-linear models) to improve p-values and r-values
