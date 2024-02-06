## ENHANCING GEOSPATIAL DATA QUALITY FOR COMPREHENSIVE ANALYSIS OF ANGOLA 

### Introduction

This project aims to conduct a thorough geospatial analysis to unveil valuable insights into the geographic context of Angola's land sector data. Despite the project's focus, several data quality  issues have surfaced, impacting the precision and comprehensiveness of the analysis. 

### Issues
1. No recorded data exists for Angola's biodiversity hotspot and protected areas. It seems that information was lost during preprocessing, as column names were retained when attempting to read the dataframes. 
2. Datasets in the form of JSON files within the land cover dataset are unable to be read when loaded as geojson dataframes, making it impossible to analyze the data and generate charts/maps specific to Angola. Additionally, there is no available data for Angola's planted forests under the land cover dataset. 

### Recommendation
It is imperative to prioritize data cleaning and validation processes to address geometry issues and enhance the overall accuracy of geospatial datasets. This will establish a more reliable foundation for a comprehensive analysis of Angola's land sector data.