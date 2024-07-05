# Exploratory Data Analysis of Game Sales

This project involves an exploratory data analysis (EDA) of game sales to answer several key questions about the industry trends and preferences.

## Key Questions

1. **Global Bestsellers:** Which games have the highest global sales?
2. **Yearly Sales:** Which year recorded the highest global sales?
3. **Genre Popularity:** What are the most popular game genres globally and in each region (North America, Europe, Japan, Rest of the World)?
4. **Changing Preferences:** How have genre preferences evolved over the years?

## Project Structure

The project is structured in a Jupyter Notebook format. Below is an outline of the notebook:

1. **Introduction**
    - An overview of the objectives and questions to be answered.

2. **Data Loading and Initial Exploration**
    - Importing necessary libraries (`pandas`, `matplotlib.pyplot`).
    - Loading the dataset and displaying the first few rows for an initial understanding.

    ```python
    import pandas as pd
    import matplotlib.pyplot as plt

    df = pd.read_csv('path_to_your_dataset.csv')
    df.head()
    ```

3. **Global Bestsellers**
    - Analysis to identify games with the highest global sales.
    
4. **Yearly Sales**
    - Analysis to determine which year recorded the highest global sales.
    
5. **Genre Popularity**
    - Analysis of the most popular game genres globally and in each region.

6. **Changing Preferences**
    - Analysis of how genre preferences have evolved over the years.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Pandas library
- Matplotlib library

### Installing

1. **Clone the repository:**

    ```bash
    git clone https://github.com/LeoIvin/Game-Sales-Exploratory-Data-Analysis.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd game-sales-eda
    ```

3. **Install the required libraries:**

    ```bash
    pip install pandas matplotlib
    ```

4. **Run the Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

## Usage

Open the `xbox-analysis.ipynb` notebook in Jupyter and run the cells to perform the analysis. Each section of the notebook includes comments and explanations to guide you through the analysis process.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.



