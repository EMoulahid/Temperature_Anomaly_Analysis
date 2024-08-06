# Temperature Anomaly Analysis

This project analyzes global temperature anomalies using data from NASA's GISS dataset and visualizes the results using Plotly. The analysis includes a line chart of temperature anomalies and a rolling average line chart to observe trends over time.

## Project Overview

The project involves:

1. **Loading Data:** Importing global temperature anomalies data from NASA GISS.
2. **Data Cleaning:** Handling non-numeric values and missing data.
3. **Data Analysis:** Calculating rolling averages to smooth out anomalies over a specified window.
4. **Data Visualization:** Creating interactive visualizations to display temperature anomalies and rolling averages.

## Data

The dataset used is sourced from NASA GISS and can be found [here](https://data.giss.nasa.gov/gistemp/tabledata_v4/T_AIRS/GLB.Ts+dSST.csv). It contains global temperature anomalies compared to the 2007-2016 baseline.

## Installation

To run this project, you'll need to install the required Python libraries. You can do this using `pip`:

```bash
pip install pandas plotly
