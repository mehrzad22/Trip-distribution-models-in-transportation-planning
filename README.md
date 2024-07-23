# Trip-distribution-models-in-transportation-planning

## Overview

This project implements the **Furness** and **Gravity Distribution Models** to analyze and predict the distribution of population and resources. These models are essential tools for researchers and urban planners, allowing for optimized resource allocation and a better understanding of demographic patterns.


## Getting Started

1. **Load Data**: 
   - The models read input data from an Excel file located at `D:/Uni/7/haml/HW/HW6/HW6.xlsx`. 
   - Make sure the data is structured correctly, with necessary columns for origin and destination populations, as well as distance or cost matrices.

2. **Run the Model**: 
   - Execute the Python script to apply the models. 
   - The script includes two main sections:
     - **Furness Model**: Adjusts the distribution based on origin and destination populations, using a specified cost matrix.
     - **Gravity Distribution Model**: Applies a gravitational approach to understand population flow and resource distribution.

3. **Error Calculation**: 
   - The model iteratively adjusts the distribution until the error between observed and expected distributions is minimized. 
   - The error is calculated and logged for each iteration, allowing you to track convergence.

4. **Visualize Results**: 
   - The error progression is plotted to help visualize model performance over iterations. This can assist in diagnosing convergence issues or understanding the model's behavior.


