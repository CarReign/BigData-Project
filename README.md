# Storm Tracks Dataset
## Introduction
The National Hurricane Center (NHC) conducts a post-storm analysis of each tropical cyclone in its area of responsibility to determine the official assessment of the cyclone's history. This analysis makes use of all available observations, including those that may not have been available in real time. 
This dataset is the NOAA Atlantic hurricane database best track data. The original NOAA Atlantic Hurricane Database Best Track Data dates back to 1951 and includes detailed information on each storm. However, for the purpose of this project, we have chosen to focus on the years 2001-2022 only. This decision was made due to our current capacity and resources. Handling such a large volume of data could be challenging and may require more computational resources and sophisticated data analysis techniques than we currently possess. The data for these years will be used to analyze and understand the characteristics and impacts of hurricanes during this period.
### Dataset Description
-	ID: This is a unique identifier for each storm.
-	name: The name of the storm.
-	year, month, day, hour: The date and time of the storm.
-	Latitude and Longitude: The geographical coordinates of the storm.
-	Status: The status of the storm at the given time.
-	Category: Saffir-Simpson hurricane category calculated from wind speed.
- NA: Not a hurricane
1. 64+ knots
2. 83+ knots
3. 96+ knots
4. 113+ knots
5. 137+ knots
-	Wind: The storm's maximum sustained wind speed (in knots)
-	Pressure: Air pressure at the storm's center (in millibars)

## Data Collection and Processing
The data is collected by the National Hurricane Center (NHC) staff after the dissipation of every tropical cyclone occurring in the Atlantic and eastern north Pacific basins. 
Accessing the Data
The data is available for download in widely-used GIS data formats. It can be accessed through the Historical Hurricane Tracks tool at www.coast.noaa.gov/hurricanes. This tool allows users to search and display global tropical cyclone data 



## StormCast: A Descriptive and Predictive Analytics App
### Members:
- Limpin, Louvila C
- Reinhart, Logronio
- Yongco, Carren Mae
## Introduction
StormCast is a desktop application that provides users with the ability to upload files and generate both descriptive and predictive analytics. The application is built using ElectronJS for the frontend and Python for the backend. The main features of the application include file uploading and analytics generation.
## Features
-	File Uploading: Users can upload files to the application. The application supports various file formats.

-	Descriptive Analytics: The application can produce descriptive analytics using measures of frequency. This includes calculating measures of central tendency (like mean, median, and mode), measures of dispersion (like range, variance, and standard deviation), and measures of frequency (like count, percent, and frequency) 1.

-	Predictive Analytics: The application uses Random Forest Regression for predictive analytics. This allows the application to make predictions based on the uploaded files.
  
## Deployment Instructions
To install and run the StormCast App, follow the following steps:
1.	Clone the repository to your local machine:
>git clone "repo link"
2.	Navigate to the project directory:
>cd gui
3.	Run stormcaster.py
>python stormCaster.py
4.	Load the CSV file by clicking the “Load CSV file” button; you can click “reset” to load another csv file.
5.	Click the “show descriptive analytics” to show the descriptive analytics.
6.	Click the “show predictive analytics” to show the predictive analytics.
7.	Click “show map” to show the path of all the storms.
