# Analyzing_data_with_pandas

Overview

This project performs comprehensive data analysis on the classic Iris dataset, demonstrating data exploration, statistical analysis and visualization techniques using Python.
The analysis includes data cleaning, statistical summaries and various visualization methods to understand patterns and relationships within the dataset.

Tasks Completed

1. Data Loading and Exploration
Loaded the Iris dataset using scikit-learn
Explored data structure and types
Handled missing values 
Examined the distribution of features across species

2. Statistical Analysis
Computed descriptive statistics for all features
Performed group analysis by species
Identified key patterns and relationships in the data
Analyzed correlations between different measurements

3. Data Visualization
Line Chart: Shows measurement trends when sorted by petal length
Bar Chart: Compares average measurements across species
Histograms: Displays distribution of measurements by species
Scatter Plots: Reveals relationships between feature pairs
Pair Plot: Shows all pairwise relationships simultaneously
Box Plots: Illustrates statistical distributions of measurements by species

4. Key Findings
Iris setosa is clearly distinguishable from other species based on petal dimensions
Petal length and width show the strongest correlation
Sepal width shows more overlap between species than other features
The three species form distinct clusters in the feature space
Virginica species has the largest sepal length and petal dimensions
Setosa species has the smallest petal length and width

## Requirements
Python 3.x

# Libraries:

 -pandas (data manipulation)
 -numpy (numerical operations)
 -matplotlib (basic plotting)
 -seaborn (enhanced visualization)
 -scikit-learn (dataset loading)

## Installation
# Create and activate a virtual environment 

python -m venv venv
source venv/bin/activate  

# Install required packages

pip install pandas numpy matplotlib seaborn scikit-learn

# Run the analysis with:

python visualisation.py

This analysis confirms the Iris dataset's value as a classification benchmark, with petal features being particularly discriminative for species identification.
