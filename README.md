# Data-Mining-Project-1
Data Preprocessing, EDA and Regression Analysis Project for IT496

## PROJECT SUMMARY:

Summarizing the insights about the dataset through EDA, we derived the following:
-	Null Values: The code first checks for null values in the dataset and finds that there are no null values in any of the columns.
-	Statistical Summary: A statistical summary of the dataset is displayed, which includes summary statistics such as mean, standard deviation, minimum, maximum, etc., for each numerical column.
-	Haversine Value Analysis: The code identifies data points where the Haversine value is equal to zero, indicating that the starting and ending points have the same latitude and longitude. It counts and reports the total data points where latitude and longitude are unequal, but the Haversine value is still zero. Rows with Haversine value equal to zero are dropped from the dataset.
-	Negative Distance Analysis: The code checks for data points where the Distance is negative and finds none. It also checks for data points where Distance is equal to zero.
-	Data Visualization: A histogram of the 'Duration' column is plotted, showing the distribution of trip durations. Boxplots for the 'Distance' and 'Duration' columns are created to visualize the presence of outliers.
-	Outlier Removal: Outliers in the 'Distance' and 'Duration' columns are removed based on the boxplot analysis.
-	Monthly Analysis: The total number of pickups is calculated for each month, and a bar chart is created to visualize the monthly distribution of trips. Average trip duration by month is calculated and plotted in a line chart.
-	Day of Week Analysis: The average trip duration is calculated for each day of the week (PDweek) and displayed in a line chart.
-	Day of Month Analysis: Average trip duration by day of the month (Pday) is calculated and plotted in a line chart.
-	Hour of the Day Analysis: Average trip duration by hour of the day (Phour) is calculated and plotted in a line chart.
-	Correlation Analysis: A heatmap is generated to visualize the correlation between continuous data columns. It helps identify relationships between variables.
-	Column Categorization: The code separates columns into continuous and categorical data columns based on the number of unique values in each column.
-	Correlation Heatmap for Continuous Data: A heatmap is generated specifically for the continuous data columns to explore correlations between them.
  
Overall, the EDA provides a comprehensive understanding of the dataset, identifies potential data quality issues (e.g., zero Haversine values), and explores relationships and patterns in the data through various visualizations. It also addresses outliers in the 'Distance' and 'Duration' columns, which is important for building predictive models.

## Possible problems on the dataset

- Bike Rental Demand Prediction:
   Problem: Forecasting bike rental numbers at various times of the day.
   Application: Optimizing bike availability and enhancing user experience for bike-sharing companies.

- Trip Duration Exploration:
   Problem: Investigating factors influencing bike trip durations and predicting trip durations given those factors.
   Application: Gaining insights into user behavior for improved trip planning and station management.

- Bike Station Usage Forecasting:
   Problem: Predicting individual bike station or docking point usage.
   Application: Facilitating station maintenance and resource allocation for balanced bike availability.

- Weather Impact on Bike Rentals:
   Problem: Analyzing how weather conditions affect bike rental patterns.
   Application: Enabling bike-sharing services to prepare for weather-related demand fluctuations.

- Seasonal Demand Analysis:
   Problem: Examining variations in bike rental demand across seasons.
   Application: Supporting resource allocation and seasonal-tailored marketing strategies.

  ### We chose Trip Duration Exploration because it can help understand user behavior patterns which in turn can help the bike rental company optimize their business strategy and improve station planning.

## CONTRIBUTIONS
1) Data Pre-Processing: Jalp Patel and Dhyey Vachani
2) Exploratory Data Analysis (EDA): Vedant Pandya, Suyash Bhagat, and Kalhar Patel
3) Modeling: Vedant Pandya and Kalhar Patel
