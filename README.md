# NYC Yellow Taxi Data Analysis | Python & Power BI

## Project Overview

This project focuses on analyzing New York City Yellow Taxi trip data for January 2026 using Python and Microsoft Power BI.

The goal is to understand taxi trip patterns, passenger behavior, fare details, payment methods, and pickup and drop-off locations through data cleaning, exploratory data analysis (EDA), and interactive visualizations.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Microsoft Power BI
- Parquet Dataset

## Dataset Source

The dataset used in this project is the **NYC Yellow Taxi Trip Record Data for January 2026**, published by the New York City Taxi & Limousine Commission (NYC TLC).

**Official Dataset Source:**  
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

### How to Access the Dataset

1. Open the official NYC TLC Trip Record Data website using the link above.
2. Find the **2026** trip record data.
3. Navigate to the **January** Yellow Taxi trip records.
4. Download the corresponding `.parquet` file.
5. Load the downloaded file into Python using Pandas for analysis.

Example:

```python
import pandas as pd

df = pd.read_parquet("yellow_tripdata_2026-01.parquet")

print(df.shape)
df.head()
```

The dataset used in this project contained approximately **3.72 million rows and 20 columns** before the analysis and data preparation steps.

**Note:** The dataset is provided by NYC TLC. Please refer to the official source for the original file and its documentation.

## Project Workflow

### 1. Data Loading and Understanding
- Loaded the January 2026 Yellow Taxi trip records from a Parquet file.
- Inspected the dataset dimensions, columns, and data types.
- Examined missing values and data quality.

### 2. Data Cleaning and Preparation
- Identified missing values in selected columns.
- Examined unusual or potentially invalid values.
- Reviewed passenger counts, rate codes, payment types, and other trip attributes.
- Prepared pickup and drop-off location information using the taxi zone lookup data.

### 3. Exploratory Data Analysis (EDA)
- Explored taxi trip and fare-related information.
- Examined passenger counts and payment methods.
- Investigated pickup and drop-off locations.
- Assessed data quality to support reliable analysis.

### 4. Power BI Dashboard

The project also includes a Power BI dashboard designed to present taxi trip metrics and trends through interactive visualizations.

Dashboard screenshots will be added to this repository to showcase the visual design and analytical work.

## Repository Contents

- `nyc_taxi_analysis.ipynb` — Python notebook containing the analysis and data preparation work.
- `screenshots/` — Dashboard screenshots, to be added.

## Why the Dataset and Power BI File Are Not Included

The original Parquet dataset and Power BI dashboard file are not included in this repository because their file sizes exceed GitHub's web-based upload limit.

To make the project reproducible, the original dataset can be downloaded directly from the official NYC TLC website linked above.

The Python notebook is available in this repository for reviewing the analysis workflow. Dashboard screenshots will be provided to demonstrate the Power BI visualizations.

## Key Learning Outcomes

- Working with a large real-world dataset.
- Handling missing values and investigating data quality.
- Performing data preparation and exploratory analysis using Python.
- Combining trip data with taxi zone lookup information.
- Developing data analysis skills relevant to business reporting and visualization.

## Project Status

In Progress — Python data analysis and preparation are documented in the notebook. The Power BI dashboard presentation and portfolio documentation are being finalized.

## Author

Aspiring Data Analyst

Skills: Python | SQL | Excel | Power BI | Data Analysis



