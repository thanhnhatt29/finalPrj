# Visualization, Analysis, and Sales Prediction for a Supermarket in the US Market

## Description
This project aims to visualize, analyze, and predict the sales of a supermarket in the US market. The project uses Jupyter Notebook to perform data analysis and prediction steps.

## Project Structure
- [`code/`](code/): Contains the notebook files.
- [`data/`](data/): Contains the data used in the project.
- [`chart/`](chart/): Contains visualizations and charts generated during the data analysis process.

## System Requirements
- Python 3.x
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

## Installation
1. Clone this repository:
    ```sh
    git clone https://github.com/thanhnhatt29/IDVI_finalPrj
    ```
2. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```
3. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

## Main Contents
1. **Read Input Data**: Load the sales data from the Kaggle.

2. **Pre-processing**:
    - Normalize: Use normalization techniques to ensure data is on the same scale.
    - Handle Missing Data: Use methods such as removing rows/columns with missing data or replacing missing values with the mean median, or most frequent value.

3. **Data Visualization and EDA**: Use libraries like seaborn, matplotlib to create visualizations that help understand the data better.

4. **Modeling**: 
    - KMeans: Use the KMeans clustering algorithm to group the data.
    - Time Series Forecasting with SARIMA and Prophet

## Data
The data used in this project is sourced from the [Superstore Sales Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting).

## Results
The pdf for analysis stored in [`result`](result) folder