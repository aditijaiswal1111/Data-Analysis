# Analysis of Indian Power Infrastructure Data (2004-2021)

## Overview
This project involves analyzing the Indian Statewise Electricity Infrastructure data spanning from 2004 to 2021. The dataset provides information on various aspects such as power requirement, availability, per capita availability, and installed power capacity for different states and union territories of India. The analysis includes preliminary data cleaning, understanding the nature of the data, exploratory data analytics, and drawing inferences. Additionally, forecasting of power requirements for each state based on projected population data for the upcoming years is performed.

## Dataset Description
The dataset is sourced from the RBI Annual Publication "Handbook of Statistics on Indian States" and contains the following columns:
- State/Union Territory
- Year
- Power Requirement Net Crore Units
- Availability Of Power Net Crore Units
- Availability Of Power Per Capita kiloWatt-Hour
- Installed Power Capacity MegaWatt

## Tasks
### Step 1: Data Preparation
- Read the dataset into a Pandas dataframe and verify the column headers.
- Check for missing values, duplicate entries, data errors, and potential outliers.

### Step 2: Analysis Tasks
#### Sampling
- Discuss strategies for simple random sampling and advantages/disadvantages of stratified sampling.

#### Descriptive Statistics
- Compute mean, median, and standard deviation of power requirements and availability.
- Visualize distribution of power requirements and availability using box plots.

#### Random Variables
- Define and calculate empirical probability distribution of the difference between power requirement and availability.
- Calculate probability of power requirement exceeding availability.

#### Mean and Expectation
- Calculate expected power requirement and per capita power availability.
- Determine expected installed power capacity for randomly selected group of states.

#### Sample Mean and Variance
- Calculate sample mean and variance of power requirement for states based on population size.

#### Skewness
- Compute skewness of power availability and requirement for all states and specific population size ranges.

#### Cluster Summary Statistics
- Stratify states into clusters based on population size and calculate summary statistics for power requirement and availability within each cluster.
- Visualize distribution within each cluster using box plots.

### Step 3: Forecasting
- Utilize projected population data to forecast expected power requirements for each state, making any assumptions explicit.

## Usage
1. Ensure you have Python installed along with necessary libraries like Pandas, NumPy, and Matplotlib.
2. Run the provided Jupyter notebook or Python script containing the analysis code.

## Files Included
- **Indian_Power_Infrastructure_Data.csv**: Dataset containing Indian power infrastructure data.
- **analysis.ipynb**: Jupyter notebook containing the analysis code.
- **forecasting.py**: Python script for forecasting expected power requirements.

## Requirements
- Python 
- Pandas
- NumPy
- Matplotlib

