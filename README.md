# NYC Motor Accidents Data Science Project Code

[Dataset](https://drive.google.com/drive/folders/1-O1tgH5R_LXVMhRpYRBOeiw7KEyMVAiJ?usp=sharing)

## Geo Spatial Analysis

**Notebook:** `NYC_Motor_Accidents_GeospatialAnalysis.ipynb`

### Datasets

1) `Geospatial_Analysis_cleaned_dataset.csv`: This dataset contains the cleaned data for Geospatial Analysis.

### Feedback Incorporated into the IPYNB

During the project presentation, it was noted that the visualization of the number of accidents in each neighborhood per accident cause was difficult to interpret. To improve this, we implemented an enhanced bar plot using Plotly, offering clearer data representation and interactivity, thus facilitating a more detailed interpretation of the results.

### How to run the code?

1. Run the "Imports", "Load Dataset" section using `Geospatial_Analysis_cleaned_dataset.csv`.
2. Run "Some Visualizations on the dataset" section.
3. Run "Creating Global Helper Function" section.
4. **SKIP** "Creating New Column", "Data Cleaning" and "Task: Handle Missing Data" sections.
5. For "Feature - Data Visualization":
    - **SKIP** "Some Analysis on the location, latitude, and longitude fields."
    - Run each block under "Feature: Borough Specific Plotting" section.

### Overview

The project conducts a geospatial analysis of traffic accidents within specific boroughs, using geospatial data to enhance road safety through detailed visualizations and analyses of accident severity, causes, and trends.

### Features

- **Plot Location Borough-wise Killed Severity**: Generates a map plotting accident coordinates based on severity within a borough. Customizable `killed_threshold` parameter.
- **Plot Location Borough-wise Injury Threshold**: Focuses on injuries, providing geographical accident distribution insights.
- **Plot Road Infrastructure Issue Locations**: Identifies and plots accident locations related to road infrastructure issues, aiding in road safety improvements.
- **Bar Chart - Accident-related Deaths by Borough**: Compares fatalities across boroughs to prioritize safety measures.
- **Bar Chart - Borough-wise Death Counts by Year**: Shows year-wise death counts, offering road safety trend insights.
- **Consolidated Bar Plot - Pedestrian, Motorist, and Cyclist Deaths**: Month-wise death breakdown for better understanding and targeted interventions.
- **Bar Plot - Borough-wise Accident Causes Leading to Deaths**: Identifies primary accident causes leading to fatalities.
- **Refined Bar Plot - Neighborhood-wise Accident Causes**: Provides a detailed accident cause analysis within neighborhoods.

### Usage

Each function or visualization is independently accessible for specific insights from the dataset. Detailed instructions on usage and parameters are available in the README of each function file.

### Conclusion

The project equips traffic authorities and road departments with insights from geospatial analysis to identify hotspots, causes, and trends for targeted safety measures and interventions.
