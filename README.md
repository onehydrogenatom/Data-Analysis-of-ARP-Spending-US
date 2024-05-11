# README

## Arkansas ARPA Funds Analysis

### Overview
This script is designed to analyze data related to Arkansas's use of American Rescue Plan Act (ARPA) funds. It focuses on expenditure patterns, particularly in terms of salaries, benefits, and projects in specific communities.

### Prerequisites
- R installed on your system
- Necessary R packages: dplyr

### Setup
1. Make sure R is installed on your system.
2. Install the required R packages using the following commands:
3. Set up your OpenAI API key by replacing `"YOUR-API-KEY"` in `Sys.setenv(OPENAI_API_KEY = "YOUR-API-KEY")` with your API key.

### Usage
1. Ensure the CSV file containing the data (`April-2023-Reporting-Data-through-March-31-2023(1).csv`) is located in the specified path (`C:\\Users\\bendw\\Downloads\\`).
2. Run the script in an R environment.

### Functionality
- **Data Loading and Inspection**: The script loads the dataset and inspects its size and column classes.
- **Data Filtering**: It filters the dataset to focus on Arkansas and specific communities.
- **Numeric Conversion**: Certain columns are converted to numeric format after removing dollar signs and commas.
- **NA Value Handling**: Missing values in certain columns are replaced with zeros.
- **Data Analysis**: Various calculations are performed on the filtered data, such as mean, median, and sum of expenditures.
- **Percentage Analysis**: It calculates the percentage of projects by expenditure category for both overall and specific community datasets.

### Outputs
- Summary statistics such as mean, median, and sum of expenditures.
- Percentage breakdown of projects by expenditure category.

### Contact
For any questions or issues regarding this script, please contact ben.d.wash@gmail.com.

