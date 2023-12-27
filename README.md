# Affordable Housing Snapshot

## Overview
This project, "Affordable Housing Snapshot," aims to analyze housing violations in Boston to develop a ranking metric for landlords, aiding tenants in making informed decisions. Our approach uses violation datasets to assign scores based on violation types and frequency.

## Data
The project utilizes four violation datasets: Rentsmart data, Code Enforcement Data, Building and Property Violations Data, and 311 Data. Additionally, Parcel data was used for mapping violations to owners.

## Notebooks and Analysis
Various Jupyter notebooks are used for initial analysis before running the final project notebook. These notebooks cover different aspects of the analysis and are essential for understanding the full scope of the project.

## Running the Project
- Ensure you have Python and Jupyter Notebook installed.
- Clone the repository and navigate to the project directory.
- Run each analysis notebook before the final project notebook for a comprehensive understanding.
- Data links and detailed instructions are provided in the repository.

Do the following only for the first time you are using this repository.
1. Create a folder called `datasets` and put all the following csv files inside it.
    - Download Building Violations dataset here:  https://data.boston.gov/dataset/building-and-property-violations1/resource/800a2663-1d6a-46e7-9356-bedb70f5332c and name it "building_violations.csv"
    - Download Code Enforcements dataset here:  https://data.boston.gov/dataset/public-works-violations/resource/90ed3816-5e70-443c-803d-9a71f44470be and name it "code_enforcement.csv"
    - Download Rent Smart Dataset here:  https://data.boston.gov/dataset/rentsmart/resource/dc615ff7-2ff3-416a-922b-f0f334f085d0 and name it "rent_smart.csv"
    - Download Parcel Dataset here: https://datacommon.mapc.org/browser/datasets/360 and name it "parcel.csv"
    - Download all 311 csv files for years 2016-2022 here: https://data.boston.gov/dataset/311-service-requests and name it "311_service_requests_[yr]"
    - Download the boston districts shapefiles here: https://bostonopendata-boston.opendata.arcgis.com/datasets/boston::new-city-council-districts-passed-9-4-on-november-2-2022-effective-for-the-2023-municipal-election/about . In the event that you decide to rename the .shp file, make sure that all the other files have a similar name to prevent errors. 

2. Run the following files:
    - building_violations_cleaning.ipynb
    - code_enforcements_cleaning.ipynb
    - 311_cleaning.ipynb
3. create a file called cleaned_datasets and put the resulting cleaned csv files here.
    -  (you need to have 3 csv files in total in this folder)
4. Run final_cleaning.ipynb
5. Finally you can run project.ipynb.
## Project Report
The final project report provides an in-depth analysis and findings. It is attached for a detailed understanding of the project's background, methodology, and results.





 
