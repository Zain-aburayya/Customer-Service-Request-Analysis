# Customer-Service-Request-Analysis
This project is a straightforward data science endeavor, centered around Customer Service Request Analysis. It is an assignment completed as part of the Caltech course, demonstrating practical data analysis and customer service insights.

## Project Objectives:

1- Data Assessment and Fresh Dataset Preparation: The primary objective of this project is to assess the data and create a clean dataset suitable for analysis, ensuring data accuracy and reliability.

2- Relationship Identification via Bar Graph: We aim to identify and visualize relationships between two variables using bar graphs, enabling insights into data patterns and correlations.

3- City-wise Complaint Visualization: Another key objective is to visually represent the major types of complaints in each city, providing a clear and informative overview of complaint distribution.

## Prerequisites:

Before engaging with this project, it is recommended to have a foundational understanding of the following concepts and tools:

- Basics of Python: Familiarity with Python programming is essential as it forms the basis for data manipulation and analysis.

- Application of Python Libraries in Data Science: An understanding of Python libraries commonly used in data science, such as Pandas, NumPy, and Matplotlib, is beneficial.

- Perform Analysis on a Dataset: Prior experience in data analysis, including data cleaning, exploration, and transformation, is helpful for meaningful insights.

- Knowledge of DataFrame: Proficiency in working with DataFrames, often utilized in data manipulation and analysis, is advantageous.

## Problem Statement:

The task at hand involves the analysis of service request (311) calls originating from New York City. To accomplish this, data wrangling techniques will be employed to unravel the data's underlying patterns and to visualize the predominant types of complaints.

## Tasks to Perform:

### 1- Understand the dataset:
1.1 Import the dataset.

1.2 Visualize the dataset.

1.3 Print the columns of the DataFrame.

1.4 Identify the shape of the dataset.

1.5 Identify the variables with null values.

### 2- Perform basic data exploratory analysis:
2.1 Draw a frequency plot to show the number of null values in each column of the DataFrame.

2.2 Missing value treatment.

    2.2.1 Remove the records whose Closed Date values are null.

2.3 Analyze the date column and remove entries with incorrect timelines.

    2.3.1 Calculate the time elapsed in closed and creation date.
  
    2.3.2 Convert the calculated date to seconds for a better representation.
  
    2.3.3 View the descriptive statistics for the newly created column.
  
    2.3.4 Check the number of null values in the Complaint_Type and City columns.
  
    2.3.5 Impute the NA value with "Unknown City."
  
    2.3.6 Draw a frequency plot for the complaints in each city.
  
    2.3.7 Create a scatter and hexbin plot of the concentration of complaints across Brooklyn.

### 3- Find major types of complaints:
3.1 Plot a bar graph to show the types of complaints.
  
3.2 Check the frequency of various types of complaints for New York City.

3.3 Find the top 10 complaint types.

3.4 Display the various types of complaints in each city.

3.5 Create a DataFrame, df_new, which contains cities as columns and complaint types in rows.

### 4- Visualize the major types of complaints in each city:
4.1 Draw another chart that shows the types of complaints in each city in a single chart, where different colors show the different types of complaints.

4.2 Sort the complaint types based on the average Request_Closing_Time grouping them for different locations.

### 5- See whether the average response time across different complaint types is similar (overall):
5.1 Visualize the average of Request_Closing_Time.

### 6- Identify the significant variables by performing statistical analysis using p-values.

### 7- Perform a Kruskal-Wallis H test:
7.1 Fail to reject H0: All sample distributions are equal.

7.2 Reject H0: One or more sample distributions are not equal.
