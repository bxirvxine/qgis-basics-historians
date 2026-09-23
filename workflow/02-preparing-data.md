**Preparing the data for the map**

This section explains how to prepare historical location data for use in QGIS. We will create a spreadsheet of historical locations with names and geographic coordinates, then save it in a format QGIS can import.

1) Create a spreadsheet

Create an Excel spreadsheet containing the locations to be mapped. In the Name column, include the text you want to display on the map for each location. 

2) Add geographic coordinates

Each location requires geographic coordinates which will be the location displayed as a point on the map. Add separate columns for longitude and latitude, using decimal degrees.

![Excel spreadsheet containing the location data](../images/excel-data.png)

3) Save the spreadsheet

Save the spreadsheet as both a standard Excel file and as a csv file. Keep the Excel file as the master copy of the dataset. QGIS uses the coordinates in your dataset to place each location on the map. Keeping an Excel file as the master dataset also makes it easier to update the data without losing the original version.

To add or remove locations in the future, update the Excel master file and then save an updated CSV file, replacing the old version of the existing CSV. Refresh the layer as required by clicking on the refresh symbol of two arrows in the toolbar.

