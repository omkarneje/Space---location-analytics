# User Analysis App

![location-analytics1](https://github.com/omkarneje/Space---location-analytics/assets/57482408/2affb3ff-f2ed-476a-b80d-616bb32aea18)


## Overview

The User Analysis App is a Streamlit web application that allows users to perform an analysis on user data. Users can upload data files, select specific dates, locations, and SSIDs to see the distinct count of User Names for each combination of the selected values. The results from files are merged for combined analysis. It provides an easy and intuitive way to visualize user activity based on the selected filters.

## Features

- Upload data files in CSV or Excel format.
- Interactive data selection widgets for Dates, Location Names, and SSIDs.
- Dynamic results are displayed as tables and interactive line charts.
- Option to merge results from two or more uploaded files.
- Downloadable results in CSV, or Excel format.
- Clear all selections and reset the app for a fresh start.

## How to use

1. Navigate to the Streamlit app URL.
2. Upload multiple Excel or CSV files using the upload widgets in the sidebar.
3. Select the desired filters for analysis.
5. Click 'Download Results' to download the results in a desired format.
6. Use the 'Reset' button to reset all selections and start a new analysis.

## Requirements

This app requires the following Python libraries:

- Streamlit
- Pandas
- Altair
- Openpyxl

## Deployment

This app is deployed on the Streamlit Cloud. For Local deployment, install the necessary Python packages using pip. It's recommended to do this in a virtual environment.

