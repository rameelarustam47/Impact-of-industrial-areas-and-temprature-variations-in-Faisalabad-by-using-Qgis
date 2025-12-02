# Impact-of-industrial-areas-and-temprature-variations-in-Faisalabad-by-using-Qgis
 This project aims to analyze the spatial relationship between industrial areas and surface temperature variations in Faisalabad using remote sensing and geographic information system (GIS) tools.
This repository contains geospatial data, analysis scripts, and visualizations for assessing the impact of industrial areas on land surface temperature (LST) in Faisalabad, Pakistan. The project uses Google Earth Engine (GEE) to generate yearly LST rasters and QGIS for mapping and spatial analysis of major industrial clusters, including Nishat Mills, Interloop, Kamal Limited, and others. The repository includes:

CSV files of major industries with coordinates and tehsil information.

GEE scripts to extract and process MODIS LST data for Faisalabad.

QGIS-ready raster and point layers for visualization of temperature patterns across industrial and rural areas.

Documentation explaining the methodology and interpretation of surface temperature variations, highlighting urban heat island effects and land-use impacts.

Purpose:

Study the relationship between industrial distribution and surface temperature.

Provide a GIS-ready dataset for further research on urban heat islands, climate, and urban planning in Faisalabad.

Serve as a case study for remote sensing and spatial analysis using open-source tools.

Technologies:

Google Earth Engine (JavaScript API)

Python (for CSV generation and data processing)

QGIS (mapping and visualization)
Results

The analysis of Faisalabad’s land surface temperature (LST) for 2024 using MODIS data, combined with industrial location data, revealed several important patterns:

Industrial Areas in the Northeast:

Major industrial zones such as Nishat Mills, Chenab Limited, Interloop, and Kamal Limited are concentrated in the northeast part of Faisalabad.

Despite high industrial activity, these areas do not always show the highest surface temperatures in the raster.

This is likely due to a mix of buildings, vegetation, and shaded areas within industrial zones, which reduce the apparent LST in satellite imagery.

Higher Temperatures in Southwestern and Southern Areas:

Regions toward Mandi Shah, Hewana, and the Faisalabad–Jhang side display higher daytime LST compared to industrial zones.

These areas are predominantly agricultural or open land, with bare soil and fewer trees, which heat up faster under direct sunlight.

This observation highlights that land cover and vegetation play a major role in surface temperature, sometimes more than industrial activity.

Urban Heat Island Effect:

Industrial and densely built-up areas in the northeast show moderately elevated LST compared to vegetated areas, indicating a localized urban heat island (UHI) effect.

The effect is noticeable but less pronounced than the heat generated in large open land areas captured by 1 km MODIS pixels.

Spatial Insights for Planning:

The analysis demonstrates that industries are not always the primary contributors to the hottest surface temperatures.

Planning for green spaces, tree cover, and land-use management is essential to mitigate surface heat in both industrial and surrounding rural areas.

Conclusion:
The results suggest that while industrial zones contribute to localized heat, the highest LST is often observed in open or agricultural land, particularly in the southwest and southern parts of Faisalabad. This provides valuable insights for urban planning, environmental monitoring, and climate adaptation strategies in the region.
