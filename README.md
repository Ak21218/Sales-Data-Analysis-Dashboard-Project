# Superstore Sales Dataset Analysis

This project performs exploratory data analysis on the Superstore sales dataset using Python and Pandas.

## Dataset
- **File**: `SampleSuperstore.csv`
- **Records**: 9,994 rows
- **Columns**: 13 (Ship Mode, Segment, Country, City, State, Postal Code, Region, Category, Sub-Category, Sales, Quantity, Discount, Profit)

## Analysis Performed

### Day 1: Basic Information
- Display first few rows of data
- Dataset shape and structure
- Column names and data types

### Day 2: Data Cleaning & Exploratory Data Analysis (EDA)
- Missing value detection
- Data type inspection
- Statistical summary of numerical columns

### Key Insights
- **Total Sales**: $2,297,200.86
- **Total Profit**: $286,397.02

#### Sales by Region:
- West: $725,457.82
- East: $678,781.24
- Central: $501,239.89
- South: $391,721.91

#### Sales by Category:
- Technology: $836,154.03
- Furniture: $741,999.80
- Office Supplies: $719,047.03

## Installation

### Requirements
- Python 3.7+
- pandas
- matplotlib

### Setup
```bash
pip install pandas matplotlib
```

## Usage

Run the analysis script:
```bash
python analysis.py
```

This will output:
- DataFrame overview and info
- Missing values summary
- Statistical summary
- Sales breakdown by region and category

## File Structure
```
.
├── analysis.py              # Main analysis script
├── SampleSuperstore.csv     # Dataset
└── README.md               # This file
```

## License
MIT License
