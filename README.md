# Battery Aging and Impedance Analysis

This project analyzes the **NASA Battery Dataset** to track the internal resistance and health of Li-ion batteries during charge, discharge, and impedance tests. The dataset provides insights into the changes in **Electrolyte Resistance (Re)**, **Charge Transfer Resistance (Rct)**, and **Battery Impedance** as the battery undergoes repeated cycles, helping us understand its aging process and the criteria for its end-of-life (EOL).

### Dataset Information
- **Source**: [NASA Battery Dataset on Kaggle](https://www.kaggle.com/datasets/patrickfleith/nasa-battery-dataset/data)
- **Description**: This dataset contains impedance measurements, electrolyte resistance, and charge transfer resistance taken during multiple charge/discharge cycles at various temperatures.
- **Goal**: The analysis focuses on how **Battery Impedance**, **Electrolyte Resistance (Re)**, and **Charge Transfer Resistance (Rct)** change as the battery ages over time.

## Project Structure
The project consists of the following components:
- **Data Processing**: The dataset is filtered to focus on impedance measurements.
- **Visualization**: Several plots are created to track how **Battery Impedance**, **Re**, and **Rct** change over time, visualizing battery aging trends.

## Files in the Repository

- **`battery_analysis.py`**: Main Python script for data loading, cleaning, processing, and generating visualizations.
- **`metadata.csv`**: Dataset containing battery test data.
- **`README.md`**: This file that provides an overview of the project.

## Requirements
To run this project, make sure you have the following Python libraries installed:
- `pandas`
- `plotly`
- `matplotlib` (optional for additional visualization)
- `numpy` (if needed for additional processing)

You can install these dependencies using pip:
```bash
pip install pandas plotly matplotlib numpy
