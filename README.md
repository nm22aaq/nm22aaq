# GHG Time Series Prediction Project

## Overview

This project focuses on analyzing and predicting Greenhouse Gas (GHG) emissions and temperature anomalies over time using various statistical and machine learning models. The analysis includes data preprocessing, visualization, and model implementation, including ARIMA, SARIMA, and LSTM models for time series forecasting.

## Project Structure

- **Data**: This directory contains the datasets used for the analysis, including GHG emissions data and temperature anomaly data.
  
- **Scripts**: Python scripts and Jupyter notebooks for data processing, visualization, and model training.

- **Models**: Pre-trained models and saved model files.

- **Results**: Outputs of model predictions and visualizations.

- **README.md**: Project documentation (this file).

## Installation

1. **Clone the Repository**
   ```
   git clone https://github.com/nm22aaq/nm22aaq/blob/main/Copy_of_GHG_Time_Series_Prediction_project.ipynb
   ```

2. **Navigate to the project directory**
   ```
   cd GHG-Time-Series-Prediction
   ```

3. **Create a Virtual Environment**
   ```
   python3 -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

4. **Install Dependencies**
   ```
   pip install -r requirements.txt
   ```

## Usage

1. **Data Preprocessing**:
   - The script preprocesses the GHG and temperature anomaly data, including data cleaning, aggregation, and transformation.

2. **Visualization**:
   - Various visualizations are generated to explore the data, such as line plots, heatmaps, and scatter plots.

3. **Modeling**:
   - The project implements ARIMA, SARIMA, and LSTM models to predict future GHG emissions and temperature anomalies.
   - Model performance is evaluated using RMSE.

4. **Forecasting**:
   - Forecast future GHG emissions for a specified number of years using the trained LSTM model.

5. **Results**:
   - The results of the predictions are saved and can be visualized using the provided scripts.

## Files

- **`temperature_data.txt`**: Raw temperature anomaly data.
- **`EDGARv8.0_FT2022_GHG_booklet_2023.xlsx`**: GHG emission data by sector and country.
- **`GHG_Time_Series_Prediction_project.ipynb`**: Jupyter notebook with the full analysis and model implementation.
- **`requirements.txt`**: List of dependencies required to run the project.

## Results

- Visualizations showing the trends in GHG emissions and temperature anomalies.
- Predictions of future temperature anomalies and GHG emissions.
- Comparison of model performances.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements

- Data sources include the EDGAR database for GHG emissions and NASA for temperature anomaly data.
- Libraries used: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `statsmodels`, `tensorflow`.

