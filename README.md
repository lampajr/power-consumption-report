# Power Consumption Report Notebook

This repository provides a simple Jupyter notebook aiming to present
and plot charts in order to compare different proxies/tools for energy
consumption measurement.

## Prerequisites

Create a `.env` file setting the `HORREUM_BASE_URL` env variable that
specifies the Horreum base URL to fetch metrics from.

The following python packages must be installed:
```
matplotlib
numpy
python-dotenv
```

## Usage

Start Jupyter server, open the [power_consumption_comparison](./power_consumption_comparison.ipynb) notebook and run 
all the cells.