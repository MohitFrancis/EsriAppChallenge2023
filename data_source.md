# Data Sources

## Web-hosted data

1. Provinces and Territories of Canada via esri Canada (https://services.arcgis.com/zmLUiqh7X11gGV2d/arcgis/rest/services/Canada_Provinical_boundaries_generalized/FeatureServer)

2. Sentinel-2 10m Land Use/Land Cover Change from 2018 to 2021 via esri
(https://env1.arcgis.com/arcgis/rest/services/Sentinel_2_10m_Land_Cover_Change/ImageServer)

3. Canadian Protected & Conserved Areas Database* via esri Canada
(https://services1.arcgis.com/B6yKvIZqzuOr0jBR/arcgis/rest/services/CPCAD_Dec2019_proj/FeatureServer)
*Note: This was utilized during Web Map development. A local gdb was also downloaded from Canada Open Data and as main source of spatial analysis.

## Open sourced data in geodatabase or shapefile formatLocal data:
1. Canadian Protected & Conserved Areas Database
The Canadian Protected and Conserved Areas Database was downloaded from Canada's Open Data Portal as a geodatabase via https://www.canada.ca/en/environment-climate-change/services/national-wildlife-areas/protected-conserved-areas-database.html
This is the main source for spatial analysis.

2. Terrestrial Ecoregion
The geodatabase was downloaded from Canada's Open Data Portal via https://open.canada.ca/data/en/dataset/ade80d26-61f5-439e-8966-73b352811fe6

- Ecoregion Descriptions retrieved and scraped from Ecological Framework of Canada website: http://www.ecozones.ca/

- Python codes and output csv can be found here: https://github.com/MohitFrancis/EsriAppChallenge2023/tree/main/scripts

3. Key Biodiversity Areas
The Canada Key Biodiversity Areas dataset was downloaded from KBA Canada (https://kbacanada.org/explore/map-viewer/) as shapefile.
The file is read directly into ArcGIS Pro.

## Open sourced data in other formats that were first converted into geodatabase in ArcGIS Pro:

1. Exclusive Economic Zone (EEZ)
The EEZ zone dataset was downloaded from Flanders Marine Institute (https://www.marineregions.org/eezdetails.php?mrgid=8493) as GML file.
The file is read directly into ArcGIS Pro and converted into a geodatabase.

2. Important Bird Areas (IBA)
The Canada Important Bird Areas dataset was downloaded from IBA Canada (https://www.ibacanada.org/explore_how.jsp?lang=en) as KML file.
The file is read directly into ArcGIS Pro and converted into a geodatabase.



