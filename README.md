# Diversity in Tech Companies Analysis

## Project Description
This project analyzes diversity metrics in various tech companies. The dataset includes percentages of different demographic groups such as gender and ethnicity across multiple years. The goal is to clean, analyze, and visualize the data to understand trends, distributions, and comparisons among companies, with a specific focus on diversity.

## Dataset Information
The dataset, `Diversity in tech companies.csv`, contains the following columns:
- **Company**: Name of the company.
- **Year**: Year of the data.
- **Female %**: Percentage of female employees.
- **Male %**: Percentage of male employees.
- **% White**: Percentage of white employees.
- **% Asian**: Percentage of Asian employees.
- **% Latino**: Percentage of Latino employees.
- **% Black**: Percentage of black employees.
- **% Multi**: Percentage of employees with multiple ethnicities.
- **% Other**: Percentage of employees from other ethnic backgrounds.
- **% Undeclared**: Percentage of employees who did not declare their ethnicity.

## Setup Instructions
1. **Clone the repository**:
    ```
    git clone https://github.com/yourusername/diversity-in-tech-companies.git
    cd diversity-in-tech-companies
    ```

2. **Install the necessary Python packages**:
    ```
    pip install pandas seaborn matplotlib
    ```

3. **Place the dataset**:
   Ensure the dataset `Diversity in tech companies.csv` is placed in the root directory of the project.

4. **Run the analysis**:
   Execute the provided Python script to perform the analysis and generate visualizations.

## Analysis Steps
1. **Data Loading and Initial Inspection**:
   - Load the dataset using `pandas`.
   - Display the first few rows and check for missing values and data types.

2. **Data Cleaning**:
   - Remove special characters (`<`, `>`, `-`) from percentage columns.
   - Convert percentage columns to numeric values and fill NaN values with `0`.

3. **Exploratory Data Analysis (EDA)**:
   - Generate summary statistics for numerical columns.
   - Visualize the distribution of numerical variables using histograms.
   - Visualize the count of records by company using a count plot.

4. **Relationship Visualization**:
   - Create a pairplot to visualize relationships between different variables.

5. **Trend Analysis**:
   - Group data by company and year.
   - Plot trends over the years for each diversity metric.

6. **Company Comparison**:
   - Compare female and black percentages across companies using bar plots.

7. **Overall Diversity Distribution**:
   - Visualize the distribution of all diversity metrics using a boxplot.

8. **Correlation Analysis**:
   - Generate a heatmap to analyze correlations between different diversity metrics.

9. **Company Ranking Based on Total Diversity**:
   - Calculate and plot the total diversity score for each company.

10. **FAANG Companies Analysis**:
    - Analyze trends in female percentage among Amazon, Apple, Netflix, and Google.

11. **Ethnicity Analysis**:
    - Reshape the data to analyze multiple ethnicities over the years.
    - Visualize the rise of multiple ethnicities in FAANG companies.

## Results and Visualizations
- **Histograms**: Displayed the distribution of numerical variables.
- **Count Plot**: Showed the number of records for each company.
- **Pair Plot**: Highlighted relationships between variables.
- **Trend Plots**: Illustrated diversity metric trends across years for each company.
- **Bar Plots**: Compared diversity metrics across companies by year.
- **Box Plot**: Visualized the overall distribution of diversity metrics.
- **Heatmap**: Showed correlations between diversity metrics.
- **Ranking Plot**: Ranked companies based on total diversity.
- **Line Plots**: Analyzed trends in FAANG companies and visualized the rise of multiple ethnicities.

## Conclusion
This project provides a comprehensive analysis of diversity in tech companies, highlighting key trends and comparisons. The visualizations and analyses can help stakeholders understand the current state of diversity in the tech industry, informing future diversity initiatives and policies.

## Contributing
If you would like to contribute to this project, please fork the repository and create a pull request with your changes. Ensure that your contributions are well-documented and tested.

## License
This project is licensed under the MIT License.

## Acknowledgements
I would like to thank kaggle for providing the dataset used in this analysis.
