# data-visualizations-challenge

## Background
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

## Tasks
This assignment is broken down into the following tasks:

### Prepare the data.
    - Run the provided package dependency and data imports, and then merge the mouse_metadata and study_results DataFrames into a single DataFrame.

### Generate summary statistics.
    - A row for each drug regimen. These regimen names should be contained in the index column.
    - A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.

### Create bar charts and pie charts.
    - Generate two bar charts. Both charts should be identical and show the total number of time points for all mice tested for each drug regimen throughout the study.
    - Create the first bar chart with the Pandas DataFrame.plot() method.
    - Create the second bar chart with Matplotlib's pyplot methods.
    - Generate two pie charts. Both charts should be identical and show the distribution of female versus male mice in the study.
    - Create the first pie chart with the Pandas DataFrame.plot() method.
    - Create the second pie chart with Matplotlib's pyplot methods.
### Calculate quartiles, find outliers, and create a box plot.
    - Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens. Use the following substeps:
    
### Create a line plot and a scatter plot.
    - Select a mouse that was treated with Capomulin, and generate a line plot of tumor volume versus time point for that mouse.
    - Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.
### Calculate correlation and regression.
    - Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.
    - Plot the linear regression model on top of the previous scatter plot.
### Analyze the Results.