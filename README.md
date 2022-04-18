# Domeyer_ENV872_EDA_FinalProject

## Summary
This is Devin Domeyer's final project for Environmental Data Analytics at Duke University 2022. The goal of the analysis is to determine any significant changes in ozone and PM2.5 levels across North Carolina counties and across each month of the year. 

## Investigators

Devin Domeyer, priciple investigator. Duke University Masters of Coastal Environmental Management. 

## Keywords

Ozone, PM2.5, particulates, pollution, environmental health, climate change. 

## Database Information

Data was collected using the Download Daily Data tool (https://www.epa.gov/outdoor-air-quality-data/download-daily-data).
The following selections were made: 
* PM2.5 and Ozone (Pollutant)
* 2018 and 2019 (Year)
* North Carolina (Geographic Area)
* Download CSV (spreadsheet)

csv files were saved as `EPAair_O3_NC2018_raw.csv`, `EPAair_O3_NC2019_raw.csv`, `EPAair_PM25_NC2018_raw.csv`, and `EPAair_PM25_NC2019_raw.csv`. 

Data were accessed on 04-02-2022.

## Folder structure, file formats, and naming conventions 

Folders contained in the repository:
* Data: Contains subfolders of Raw and Processed for the project. All files are csv.
* Raw: Downloaded data in its original form.
* Processed: Processed data from the analysis.

## Metadata

Information gathered from: https://www.epa.gov/outdoor-air-quality-data/air-data-basic-information and https://aqs.epa.gov/aqsweb/documents/AQS_Format.html

Date: month/day/year
Source: AQS (Air Quality System) or AirNow
Site ID: A unique number within the county identifying the site.
POC: “Parameter Occurrence Code” used to distinguish different instruments that measure the same parameter at the same site.
Daily Mean PM2.5 Concentration: numeric value
Daily Max 8-hour Ozone Concentration: numeric value
Units: units for concentration

Daily_AQI_VALUE: Air quality index (range 0-500). Levels: 
0-50: Good (green)
51-100: Moderate (yellow)
101-150: Unhealthy for sensitive groups (orange)
151-200: Unhealthy (red)
201-300: Very unhealthy (purple)
301-500: Hazardous (maroon)

Site Name
DAILY_OBS_COUNT: number of observations per day
PERCENT_COMPLETE
AQS_PARAMETER_CODE
AQS_PARAMETER_DESC
CBSA_CODE
CBSA_NAME
STATE_CODE
STATE
COUNTY_CODE
COUNTY
SITE_LATITUDE
SITE_LONGITUDE
  
