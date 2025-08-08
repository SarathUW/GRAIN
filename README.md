<img src="./assets/images/gitRepo_cover.png" alt="logo" width="1000" height="auto">

## Global Registry of Agricultural Irrigation Networks
GRAIN is an OpenStreetMap (OSM) based dataset of the world's irrigation canals. OSM country-scale data is retrieved from [Geofrabrik.de](https://www.geofabrik.de/), processed using [OSMium CLI Toolkit](https://osmcode.org/osmium-tool/) to filter for waterways. A Random Forest classifier is used to differentiate between man-made canals and natural rivers and any misclassified labels are corrected. 