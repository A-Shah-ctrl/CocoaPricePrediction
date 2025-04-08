# Cocoa Price Prediction

This project has been created as a submission of the STA457/STA2202 Final Project. 

### Authors
Ashka Shah, Peush Gomes and Yiyi Li. All authors have contributed equally to this project.

### The Code Files
All the code file are in R Markdown format. The folloding is a description of the contents of the code files.

1) DataCleaning.Rmd - contains all the code that was run (with explanation) to clean and process all the datasets and merge them into a final usable dataset (can be found at data/cleaned_data.csv)
2) ARIMAModels.Rmd - contains all the code that was run (with explanation) to analyze data and develop ARIMA models for Cocoa Futures Prediction 
3) MultipleRegressionModel.Rmd - contains all the code that was run (with explanation) to analyze data and develop the Multipl Linear Regression with Lagged Variables model for Cocoa Futures Prediction 
4) RandomForestAndSARIMA.Rmd - contains all the code that was run (with explanation) to analyze data and develop the SARIMA and Random Forest Models for Cocoa Futures Prediction 
5) FinalReport.Rmd - contains all the text and code that was used to generate the plots, figures and the content of the FinalReport.pdf

### Usage

1) Clone the repository
2) Download RStudio. Navigate to this folder
3) Run the Rmd files for output and results. 

### Data and its Sources
 For the purposes of modeling cocoa futures prices we used three datasets. Two of the datasets were already provided to us by the instructors of STA457H/STA2202H, while one dataset was externally sourced by our team. 
 The datasets used for this project are stored in the **data** folder -
 1. Cocoa Futures Price Dataset- This dataset provided by the instructors consists of daily Closing Prices
 for Cocoa Futures contracts and was obtained from the International Cocoa Organization (ICCO).
 It consists of data from Oct 2, 1994 to Feb 27, 2025. This dataset is stored under the file name
 Cocoa_Daily_Prices.csv.
 2. Ghana Climate Dataset- This dataset provided by the instructors consists of daily Temperature and
 Precipitation in Ghana and was obtained from the National Centers for Environmental Information
 (NCEI). It consists of data from Jan 1, 1990 to Nov, 28, 2024. This dataset is stored under the file
 name Ghana_Climate_Data.csv.
 3. Ghana Currency Exchange Rate Dataset- This is the dataset we sourced externally which con
sists of monthly Average Exchange Rate values for Cedi to USD obtained from the [International
 Monetary Fund](https://data.imf.org/regular.aspx?key=61545850). It ranges from Jan 1990 to Sep 2024. The data is stored under the filename
 Ghana_Exchange_Rates.csv 

There were two other datasets from Food and Agriculture Organization of the United Nations we wanted to incorporate (1) [Production, Yield and Harvest data for Cocoa Beans in Ghana] (https://www.fao.org/faostat/en/#data/QCL), to model the supply of cocoa in Ghana (2) [Cocoa Beans Import in the World] (https://www.fao.org/faostat/en/#data/QCL), to model the demand of cocoa in the world.  Unfortunately, we were unable to these two datasets. <i>Rationale for using and not using certain data sources can be found in FinalReport.pdf</i>.

<b>Note - </b> This data does not belong to us. All the data used in this project was open source.


