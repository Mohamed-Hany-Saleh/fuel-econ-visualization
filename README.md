# Vehicle Fuel Economy Analysis

A Python project to analyze and visualize vehicle fuel economy data. The project leverages powerful data analysis libraries like **Pandas**, **Matplotlib**, and **Seaborn** to generate insightful visualizations about fuel types, emissions, fuel efficiency, and vehicle characteristics.

## Table of Contents
- [Overview](#overview)
- [Key Insights](#key-insights)
- [Features](#features)
- [Technologies](#technologies)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [License](#license)

## Overview
This project provides a comprehensive analysis of fuel economy across different vehicle types. It includes data visualizations that help uncover patterns and trends in fuel usage, vehicle classes, CO2 emissions, and more. The dataset used is a detailed collection of vehicle fuel consumption data, making it ideal for studying automotive efficiency trends.

## Key Insights
1. **Diverse Vehicle Classes**: The analysis shows a significant variety in vehicle classes, indicating a wide range of consumer preferences and usage patterns.
2. **Fuel Type Preferences**: The distribution of fuel types reveals trends in consumer choices, with certain fuel types being more prevalent in specific vehicle classes.
3. **Efficiency Trends**: A comparison of city vs highway MPG illustrates how vehicle design impacts fuel efficiency in different driving conditions.
4. **Emissions Patterns**: The box plot of CO2 emissions by vehicle class provides insights into environmental impacts, highlighting classes with higher emissions.
5. **Transmission Impact**: Average CO2 emissions vary significantly by transmission type, indicating that certain transmissions may contribute more to environmental concerns.
6. **Fuel Economy by Make**: Violin plots reveal that some car manufacturers produce vehicles with significantly higher fuel economy scores than others, suggesting potential areas for improvement in design and technology.
7. **Trends Over Time**: The yearly trend of CO2 emissions shows how vehicle emissions have evolved over the years, reflecting changes in regulations and technology advancements.

## Features
- **Distribution of Vehicle Classes (VClass)**: A bar chart showing the count of vehicles in each vehicle class.
- **Fuel Type Distribution**: A bar chart illustrating the distribution of different fuel types used across vehicles.
- **City vs Highway MPG Comparison**: A scatter plot comparing city fuel economy (city) to highway fuel economy (highway) for all vehicles.
- **CO2 Emissions by Vehicle Class**: A box plot to compare CO2 emissions across different vehicle classes.
- **Fuel Economy Score Distribution**: A histogram showing the distribution of fuel economy scores (feScore) across all vehicles.
- **Cylinders vs Displacement**: A scatter plot of the number of cylinders against engine displacement (displ).
- **Average CO2 Emissions by Transmission Type**: A bar chart displaying the average CO2 emissions for each type of transmission (trans).
- **Fuel Economy (comb) Across Car Makes**: A violin plot to show the distribution of combined fuel economy (comb) across different car makes.
- **Average Fuel Efficiency by Drive Type**: A bar chart comparing the average fuel efficiency (comb) for different drive types (drive).
- **Yearly Trend of CO2 Emissions**: A line plot showing the trend of average CO2 emissions over the years.

## Technologies
- **Python 3.7+**
- **Pandas** for data manipulation.
- **Matplotlib** and **Seaborn** for data visualization.
- **NumPy** for numerical computations.

## Usage
To run this project in **Google Colab**:
1. Open the provided notebook in Google Colab.
2. Upload the dataset (`fuel-econ.csv`) when prompted.
3. Execute the code cells to generate visualizations and analyze the data.

## Visualizations

### Distribution of Vehicle Classes (VClass)
  
![1](https://github.com/user-attachments/assets/7aebebf1-be6a-4e5f-986c-9524ce8c0bfb)
*A bar chart showing the count of vehicles in each vehicle class.*

### Fuel Type Distribution
![2](https://github.com/user-attachments/assets/433241af-f921-4ead-beb0-d7fda4896244)

*A bar chart illustrating the distribution of different fuel types used across vehicles.*

### City vs Highway MPG Comparison
![3](https://github.com/user-attachments/assets/87a48913-3b63-4f12-8e39-96f43e1bf84c)

*A scatter plot comparing city fuel economy (city) to highway fuel economy (highway) for all vehicles.*

### CO2 Emissions by Vehicle Class
![4](https://github.com/user-attachments/assets/b90b474a-89ac-479b-9e93-47e4d87a0bfa)

*A box plot to compare CO2 emissions across different vehicle classes.*

### Fuel Economy Score Distribution
![5](https://github.com/user-attachments/assets/b767a33c-31b1-4993-a5a2-29c18b2b8d48)

*A histogram showing the distribution of fuel economy scores (feScore) across all vehicles.*

### Cylinders vs Displacement
![6](https://github.com/user-attachments/assets/662207f3-2c85-492a-a0d1-7579027a9348)

*A scatter plot of the number of cylinders against engine displacement (displ).*

### Average CO2 Emissions by Transmission Type
![7](https://github.com/user-attachments/assets/06562f47-d459-44f5-b929-dc2101cf0460)
 
*A bar chart displaying the average CO2 emissions for each type of transmission (trans).*

### Fuel Economy (comb) Across Car Makes
![8](https://github.com/user-attachments/assets/d2e1ce5b-7fac-4c97-9f48-ab8497936587)
 
*A violin plot to show the distribution of combined fuel economy (comb) across different car makes.*

### Average Fuel Efficiency by Drive Type
![9](https://github.com/user-attachments/assets/06c0fbd4-0bd0-4fac-b05e-d2a8e5cbe0ac)

*A bar chart comparing the average fuel efficiency (comb) for different drive types (drive).*

### Yearly Trend of CO2 Emissions
![10](https://github.com/user-attachments/assets/5d0fce5d-c6f3-409e-aa79-3e271bf2cfad)

*A line plot showing the trend of average CO2 emissions over the years.*

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
