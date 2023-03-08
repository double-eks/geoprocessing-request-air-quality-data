# Request Air Quality Data

## _ArcGIS Pro Python Toolbox_

A geoprocessing toolbox with 2 tools avaiable developed by Sean X. from _Carnegie Mellon University_

### How to use

1. Download the Zip file and decompress
2. Make sure **RequestAirQualityToolbox.pyt** (ArcGIS python toolbox file) and all the **.py** files are in the same dictionary
3. Open ArcGIS Pro Catalog panel
4. Right click Toolbox and use **Add Toolbox** to add **RequestAirQualityToolbox.pyt**
5. Add .pyt to the toolbox
6. Choose a proper geoprocessing tool in the toolbox and go!

<br></br>

### Tool 1 - Request Daily AQI by ZIP

- Request daily air quality data for a **city** or **county** from EPA Air Quality System in a given time range
- Output a feature table of cleaned data

<br></br>

### Tool 2 - Request Daily AQI by County


- Input a county (polygon) feature layer/class to request daily air quality data for a **county** or **counties** from EPA Air Quality System in a given time range
- Output a feature table of cleaned data
  <br>_p.s. should be a bulk of data - total rows = input county count \* requested days_</br>

<br></br>

### Data source credit

US EPA Air Quality System (AQS) - [Air Quality Data Collected at Outdoor Monitors Across the US](https://www.epa.gov/outdoor-air-quality-data)
