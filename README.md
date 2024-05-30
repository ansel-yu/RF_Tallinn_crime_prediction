# Analyzing the relationships between crime and socioeconomic and spatial factors using random forest: a case study of Tallinn
The spatial factors of crime and its socioeconomic background are important topics in crime research. This study uses a grid framework to represent various spatial, environmental, and socioeconomic factors across Tallinn in 500-meter grids. The study aims to predict the number of crimes in each grid cell through a random forest machine learning model and identify the main contributing factors. Machine learning models do not explain causal relationships between variables but highlight possible correlations, so crime factors need to be discussed within Tallinn's context. Among various types of crime, the factor of commercial locations shows the strongest relationship with the number of crimes. These reflect the concentration of economic activities, assets, and the gathering of people, which are important conditions for crime motivations. Secondly, factors such as the number of renters and the population with low socioeconomic status are associated with the number of crimes against public order.


## Author
Cheng-Wei Yu


## Data
The crime data from the Estonian Police and Border Guard Board was classified and used as the dependent variables. The covariates used the roads, land use, points of interest (POIs), green spaces, housing, and demographic and socioeconomic data.

|Dataset	|Variable	|Unit	|
| :---: | :---: | :---: | 
|Crime|	Crimes against public order / Crimes against property / Total crime incidents|	Number of incidents per grid cell|
|Road| Trail / Neighborhood level / City level|	Length (meters) per grid cell|
|Land use| Discontinued dense urban fabric / Discontinued medium dense urban fabric / Industrial, commercial, public, military, and private units / Continuous urban fabric |	Area (square meters) per grid cell|
|Green space| Area of green space|	Area (square meters) per grid cell| 
|Diversity of land use| Number of land use and green space types | Number of land use types per grid cell|
|Point of Interest	| Commercial / Recreational / Public services / Camera surveillance|	Number of points per grid cell|
|Housing type| Small-scale apartment house / Standalone house / Large-scale apartment house / Auxiliary house / Others|	Number of houses per grid cell|
|Demographic, socioeconomic, and housing |Age groups (10) / Ethnicity (2) / Socioeconomic status (3) / House conditions (3) / House ownership (2)|	Number of people per grid cell|
|Spatial |X and Y coordinates|	X and Y coordinate of the grid cell centroid|


## Acknowledgements
 - [Geoinformatics for Urbanised Society, University of Tartu](https://ut.ee/en/curriculum/geoinformatics-urbanised-society)
