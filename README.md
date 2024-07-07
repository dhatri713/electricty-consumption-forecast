Electricity Consumption Forecasting

This project utilizes the "Individual household electric power consumption" dataset from UC Irvine's Machine Learning Repository to forecast electricity consumption using various statistical models and Long Short-Term Memory (LSTM) networks.
Dataset

The dataset contains 2,075,259 measurements gathered in a house located in Sceaux (7km from Paris, France) between December 2006 and November 2010 (47 months).

Link to Dataset: [UC Irvine ML Repository - Individual Household Electric Power Consumption](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)

Features:

    Date: Date in format dd/mm/yyyy
    Time: Time in format hh:mm
    Global Active Power: Household global minute-averaged active power (in kilowatt)
    Global Reactive Power: Household global minute-averaged reactive power (in kilowatt)
    Voltage: Minute-averaged voltage (in volt)
    Global Intensity: Household global minute-averaged current intensity (in ampere)
    Sub Metering 1: Energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven, and a microwave (hot plates are not electric but gas powered).
    Sub Metering 2: Energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing machine, a tumble-dryer, a refrigerator, and a light.
    Sub Metering 3: Energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water heater and an air-conditioner.

Project Objective

The goal of this project is to forecast electricity consumption using various time series forecasting models and identify the model that performs best.
Methodology

    Data Preprocessing:
        Handling missing values
        Feature scaling
        Data splitting

    Modeling:
        Implemented and evaluated various statistical models including Vector Autoregression (VAR) and Vector Autoregressive Moving Average (VARMA).
        Explored deep learning models with a focus on Long Short-Term Memory (LSTM) networks, which have shown superior performance.

Results

After testing various models, LSTMs were found to deliver the best performance for the given dataset.
