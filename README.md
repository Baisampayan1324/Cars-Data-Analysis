# Cars Data Analysis

This project analyzes car specifications and characteristics using Python and pandas. The analysis includes data cleaning, exploration, filtering, and transformation operations on car dataset.

# Disclaimer

This repo is intended **purely for educational purposes**.

The examples, models, and predictions used in this course are designed to teach how AI and LSTM models can be applied to financial data.  
They are **not meant to provide investment advice**, nor should they be used as a basis for real-world trading.

Always consult a certified financial advisor before making any financial decisions.

## Features
- Loads and inspects the car dataset
- Handles missing values (fills null values with mean)
- Explores different car makes and their counts
- Filters records by origin (Asia/Europe) and weight criteria
- Transforms data by applying functions to columns
- Performs statistical analysis and data manipulation

## How to Run
1. Open the notebook `notebooks/cars_data.ipynb` in VS Code or Jupyter.
2. Run cells sequentially to execute all analysis steps.
3. Make sure the dataset is present at `datasets/dataset.csv`.

## Requirements
- Python 3.x
- pandas
- Jupyter Notebook

## Dataset
The dataset should be placed in the `datasets` folder as `dataset.csv`. It contains car records with columns like Make, Origin, Cylinders, Weight, MPG_City, and other car specifications.

## Project Structure
```
Cars Data Analysis/
├── datasets/
│   └── dataset.csv
├── notebooks/
│   └── cars_data.ipynb
└── README.md
```

Happy Learning