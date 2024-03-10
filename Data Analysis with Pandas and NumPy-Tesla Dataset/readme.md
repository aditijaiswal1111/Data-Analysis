Data Analysis with Pandas and NumPy
Overview
This repository contains Python code for performing data analysis using Pandas and NumPy libraries. The analysis is divided into two main problems:

One-Dimension Random Walk Simulation: Simulating a random walk of a person along a line in a 2-D plane.
Insights from Tesla Accident Data: Analyzing and extracting insights from a dataset containing information about Tesla accidents.
Problem 1: One-Dimension Random Walk
Description
Imagine a person walking down a road from point 'A' to point 'B', where at each step, they move forward with equal probability of moving one step to the right or left.

Tasks
Simulate the random walk and plot the position of the walker versus the step number.
Run the simulation 100 times for 20 steps each and plot the average position of the walker with error bars.
Redo the simulation with bias, where the probability of moving left is slightly higher than moving right.
Problem 2: Tesla Accident Data Analysis
Description
Analyzing a dataset containing information about Tesla accidents to extract various insights.

Tasks
Load the dataset and clean it by removing unnecessary columns.
Plot histograms and bar graphs for deaths by year, country, state (USA), and fatality distribution.
Analyze the cause of the highest accidents using common words from the description column.
Determine cyclist-related fatalities by country.
Investigate Autopilot claimed accidents and their verification status.
Analyze the 'model'-wise distribution of accidents and determine which model results in minimal driver damage.
Explore sudden acceleration cases and their distribution by model and state.
Identify the most frequently occurring words in the 'Details' column of sudden acceleration cases.
Files Included
random_walk.py: Python script for simulating a one-dimensional random walk.
tesla_accident_analysis.py: Python script for analyzing Tesla accident data.
Tesla Deaths - Deaths.csv: Dataset containing information about Tesla accidents.
Tesla Deaths – Sudden Acceleration.csv: Dataset containing information about Tesla sudden acceleration cases.
Usage
To run the code:

Make sure you have Python installed on your system.
Install the required libraries: Pandas, NumPy, and Matplotlib.
Execute the Python scripts provided for each problem.
