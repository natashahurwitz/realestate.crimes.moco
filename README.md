# realestate.crimes.moco
INST737 - Digging into Data Group Project
Arash Asadabadi, Ashley Turnbull, Natasha Hurwitz, Nibret Data

The goal of this project was to determine if crime had an impact on housing prices in Montgomery County, Maryland. 
We obtained, combined and cleaned both public and non-public datasets.  We used descriptive statitics, feature-engineering,
machine learning (SVM), principle component analysis (PCA) and regression models to predict housing prices based on our combined dataset.

This README file indicates the purpose of each included file.

Crime_2014.csv: List of all incident for Montgomery County for the 6/2013 - 6/2014 period
Crime-final.csv: Crime rates for 23 crime categories in all zip codes
Crime-original.csv: Original crime file for 6/2013 - 6/2014
Crime_by_Zipcode_2014.csv: All the incidents in the crime_2014 are categorized in this file
Date-crime.csv: Crime rates for different months
Facilities_by_Zipcode.csv: Facility count for all the zip codes in Montgomery County
Long_and_Foster.csv: Original Long & Foster housing prices data
Long_and_Foster_Columns _removed.csv: Long & Foster data without NAs and extra variables
MC_Home_Sales_by_Zip_Code_2014.csv: The median house sale price by Montgomery County zipcode for 2014, according to the Maryland Department of Planning
MC_IRS.csv: Zipcode, type of zip code, and IRS population
MCPS_Dropout_Attendance_by_Zipcode.csv: Dropout, attendance, and graduation rates by zip code
Merge.csv: Number of sales, crime, population, and sale prices by zip code
Most_Data.csv: Combined data sets including different variables in zip code level
most_data_2014.csv: Revised version of Most_Data.csv
final_script.R: The combined R script for the project
project_code.Rmd: The R-markdown file (.Rmd) which includes all combined code for each of the analyses and generated images.  This includes code for:
●	Checking/installing R libraries that are required in the code
●	Data cleaning
●	Analyses
●	Visualizations (graphs, maps)
project_output.html: The output of the Rmd file
Project_Writeup.docx: The project writeup explaining all aspects of the project
Presentation_PPT.pptx: the PowerPoint slides for our group presentation on the project
