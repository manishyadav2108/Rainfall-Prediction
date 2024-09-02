# Sydney Rainfall Prediction Project

This project focuses on analyzing and predicting rainfall in Sydney using historical weather data. The dataset includes various weather parameters such as temperature, humidity, pressure, and rainfall measurements.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to explore the relationships between different weather parameters and their impact on rainfall in Sydney. By analyzing historical data, we can gain insights and potentially build models to predict future rainfall.

## Dataset
The dataset used in this project is stored in the file `sydney_rain prediction.csv`. It contains the following columns:
- **Date:** The date of the observation.
- **Location:** The location of the observation (Sydney).
- **MinTemp:** Minimum temperature recorded on the day.
- **MaxTemp:** Maximum temperature recorded on the day.
- **Rainfall:** The amount of rainfall recorded (in mm).
- **Humidity9am:** Humidity level at 9 AM.
- **Humidity3pm:** Humidity level at 3 PM.
- **Pressure9am:** Atmospheric pressure at 9 AM.
- **Pressure3pm:** Atmospheric pressure at 3 PM.
- **Temp9am:** Temperature at 9 AM.
- **Temp3pm:** Temperature at 3 PM.
- **RainToday:** A binary indicator of whether it rained today.
- **RainTomorrow:** A binary indicator of whether it rained the next day (target variable for prediction).

## Installation
To run this project, you need to have Python installed along with the following libraries:
- `numpy`
- `pandas`
- `seaborn`

You can install these dependencies using pip:
```bash
pip install numpy pandas seaborn

## Project Structure
Interview Prep Final project.ipynb: The Jupyter notebook containing the analysis and prediction workflow.
sydney_rain prediction.csv: The dataset used for analysis.


## Usage
To run the notebook, simply open it in Jupyter Notebook or JupyterLab:
The notebook will guide you through the steps of loading the data, performing exploratory data analysis, and building prediction models.

## Contributing
If you wish to contribute to this project, feel free to fork the repository and submit a pull request.
