# Project BHUJAL 

## Overview
This project mainly deals with the use of drone-based technology to keep track of and predict the amount of **Evapotranspiration (ET)** in the respective agricultural fields. These drones are mounted with multispectral cameras as well as a thermal camera, and they are used to capture high-resolution aerial images, which are then processed in order to calculate ET. This piece of information helps the farmers with irrigation optimization, crop health monitoring, and sustainable water usages.

The required ET system uses **OpenCV** for image processing as well as **Google Earth Engine** for geospatial analysis and the **SEBAL (Surface Energy Balance Algorithm for Land)** model to calculate the ET from drone-collected data. **Plotly** is the software that is used for interactive data visualization and **Django** is the platform that is used for the web-based user interface.

## Key Features
- **Drone Integration**: Collects high-resolution multispectral and thermal data, using **NDVI Camera**
- **Evapotranspiration Estimation**: Calculates ET, LIA.
- **Precision Irrigation**: Provides real-time insights into crop water needs.
- **Interactive Data Visualization**: Displays ET, LIA, Humidity, Temprature, etc . . . data using Plotly on a Django-based dashboard.
- **Integration with Google Earth Engine**: Combines drone data with satellite imagery for enhanced analysis and show errors and corrections.

## Technologies Used
- **Drones**: _ _ _ _ _ _ _ _
- **Programming Languages**: Python, C++, HTML, CSS, JS
- **Web Framework**: Django (for the frontend and backend)
- **Image Processing**: OpenCV
- **Geospatial Analysis**: Google Earth Engine Python API
- **Visualization**: Plotly

