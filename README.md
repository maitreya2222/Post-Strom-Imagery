# Post-Strom-Imagery

A comprehensive and automated system for real-time flood detection, mapping, and prediction, utilizing Sentinel-1 SAR data, Digital Elevation Models (DEM), and advanced GIS tools to generate actionable flood intelligence for policymakers, emergency responders, and affected communities.

---

##  **Flood Response and Mapping Pipeline**

### **Overview**
The `Post-Strom-Imagery` project establishes a robust pipeline to accurately detect and map flood extents in real-time using satellite imagery, DEM data, and advanced geospatial analysis techniques. By leveraging data from NASA DRCS and the Copernicus satellite program, the pipeline generates GIS-compatible outputs to assist in disaster response, urban planning, insurance assessments, and risk mitigation.

---

###  **Key Features**
- **Real-Time Flood Mapping:** Automated extraction of flood boundaries using Sentinel-1 SAR VV bands and DEM-based slope analysis.
- **GIS-Compatible Outputs:** Generation of shapefiles, GeoJSON, and CSV outputs for municipality-wise flood impact analysis.
- **Advanced Flood Prediction:** A custom logistic model using Open-Meteo weather data (wind and pressure) to predict flood probabilities 7 days ahead.
- **High-Precision Algorithms:** Slope filtering, DEM integration, and speckle noise reduction for enhanced flood boundary accuracy.
- **Interactive Visualization:** Detailed visual outputs using Folium and Plotly for comprehensive flood zone analysis.

---

###  **Data Sources**
1. **NASA DRCS:** Real-time disaster response imagery for immediate flood impact assessment.
2. **Copernicus Sentinel-1 SAR:** High-resolution SAR VV bands for accurate flood detection.
3. **Digital Elevation Models (DEM):** Slope and elevation data for depth estimation and flood impact analysis.
4. **Open-Meteo API:** Weather data (wind speed, pressure) for future flood prediction.
5. **Historical Flood Data:** Hurricane Maria dataset for validation and accuracy testing.

---

###  **Notebooks and Implementation**
- **Objective 1:** Enhanced flood detection using slope-filtered VV backscatter difference (`notebooks/objectives/objective_1_updated.ipynb`).
- **Objective 3:** Future flood prediction using logistic model with Open-Meteo data (`notebooks/objectives/obj_3.ipynb`).
- **Additional Analysis:** Additional experimental implementation and analysis (`notebooks/objectives/Untitled3.ipynb`).

---

###  **Technologies Used**
- **Programming Languages:** Python, R
- **Machine Learning Libraries:** TensorFlow, Scikit-Learn
- **GIS and Mapping:** QGIS, GeoPandas, Folium
- **Data Processing:** Pandas, NumPy
- **Visualization:** Plotly, Matplotlib
- **Cloud Infrastructure:** AWS S3 for data storage, EC2 for processing

---

###  **Next Steps**
- Integrate DEM-based flood depth estimation.
- Implement advanced post-processing techniques for noise reduction and boundary refinement.
- Automate flood prediction updates using real-time weather data feeds.


