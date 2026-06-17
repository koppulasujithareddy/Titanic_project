# Titanic Dataset - Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on performing an Exploratory Data Analysis (EDA) on the classic Titanic passenger dataset. The primary goal is to analyze passenger demographics, ticket data, and survival statuses to identify the core factors that heavily influenced whether a passenger survived or lost their life during the disaster.

## Features & Analysis Performed
* **Data Summary & Shape:** Inspected the overall dimensions of the dataset and mapped out missing data structures.
* **Data Visualizations:** Generated visual charts to analyze overall survival distributions.
* **Feature Categorization:** Conducted breakdown analyses comparing survival rates across different genders and socioeconomic ticket classes.

## Key Insights Uncovered
* **Dataset Scale:** The dataset contains 891 passenger records across 12 distinct data columns.
* **Missing Value Gaps:** Identified significant gaps in the data, including 177 missing entries in the `Age` column and 687 missing entries in the `Cabin` column.
* **Gender Disparity:** Visual analysis confirms a stark contrast in survival rates between genders, showing that females had a significantly higher likelihood of survival than males.
* **Class Disparity:** Socioeconomic status was a critical determinant of passenger outcomes. Passengers holding 3rd class tickets accounted for the absolute majority of casualties, while 1st class passengers experienced the highest survival rates.

## Technologies Used
* **Python 3**
* **Jupyter Notebook**
* **Pandas** (Data manipulation and analysis)
* **Matplotlib** (Static data plotting)
* **Seaborn** (Statistical data visualization)

## How to Run the Project
1. Clone this repository to your local machine.
2. Ensure you have Anaconda or Python installed along with the required libraries:
```bash
   pip install pandas matplotlib seaborn notebook
