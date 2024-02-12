## ENHANCING GEOSPATIAL DATA QUALITY FOR COMPREHENSIVE ANALYSIS OF ALBANIA

### Introduction

This project is designed to conduct an in-depth geospatial analysis, intending to unveil valuable insights into the geographic context of Albania's land sector data. However, the success of this project is currently hindered by significant data quality issues affecting the precision and comprehensiveness of the analysis.

### Issues

1. The `geometry` column exposes a considerable number of invalid geometries for Albania, hindering the successful creation of maps for the protected areas dataset. Only two valid geometries are present, raising concerns about potential data entry errors, inconsistencies in spatial representations, or other underlying data quality problems.
2. Datasets in JSON format within the land cover dataset pose challenges when loaded as geojson dataframes, preventing the analysis of data and the generation of charts/maps specific to Albania. Notably, there is a lack of available data for Albania's planted forests under the land cover dataset, limiting the scope of the analysis.

### Recommendation

It is of utmost importance to prioritize comprehensive data cleaning and validation processes to effectively address the identified geometry issues. By doing so, we can enhance the overall accuracy of geospatial datasets, providing a more reliable foundation for conducting a thorough and insightful  analysis of Albania's land sector data. This proactive approach will not only mitigate existing challenges but also ensure the success of the geospatial analysis project, fostering a more robust understanding of Albania's geographic landscape.