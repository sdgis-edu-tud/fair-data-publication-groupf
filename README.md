# Unpacking Dresden

## Table of Contents

- [Unpacking Dresden](#unpacking-dresden)
  - [Table of Contents](#table-of-contents)
- [1. GENERAL INFORMATION](#1-general-information)
  - [1.1 Unpacking Dresden](#11-unpacking-dresden)
  - [1.2 Dataset description](#12-dataset-description)
  - [1.3 Author Information](#13-author-information)
  - [1.4 Dates of data collection](#14-dates-of-data-collection)
  - [1.5 Geographic location of data collection](#15-geographic-location-of-data-collection)
  - [1.6 Keywords](#16-keywords)
  - [1.7 Language](#17-language)
  - [1.8 Information about funding sources that supported the collection of the data](#18-information-about-funding-sources-that-supported-the-collection-of-the-data)
- [2. METHODOLOGICAL INFORMATION](#2-methodological-information)
  - [2.1 Research questions, methods and envisioned uses](#21-research-questions-methods-and-envisioned-uses)
    - [2.1.1 Sub-Research question 1 (Biodiversity)](#211-sub-research-question-1-biodiversity)
    - [2.1.2 Sub-Research question 2 (Climate adaptation)](#212-sub-research-question-2-climate-adaptation)
    - [2.1.3 Sub-Research question 3 (Quality of Life)](#213-sub-research-question-3-quality-of-life)
    - [2.1.4 Analysis Methods](#214-analysis-methods)
    - [2.1.5 Envisioned uses of the data set](#215-envisioned-uses-of-the-data-set)
  - [2.2 Methods for processing the data](#22-methods-for-processing-the-data)
    - [2.2.1 Defining spatial units](#221-defining-spatial-units)
    - [2.2.2 Processing Data for S-MCDA](#222-processing-data-for-s-mcda)
  - [2.3 Instrument- or software-specific information](#23-instrument--or-software-specific-information)
- [3. FILE OVERVIEW](#3-file-overview)
  - [3.1 File List](#31-file-list)
    - [3.1.1. Spatial Units](#311-spatial-units)
    - [3.1.2. Final Attributes](#312-final-attributes)
    - [3.1.3. Analysis Results](#313-analysis-results)
  - [3.2 Relationship between files](#32-relationship-between-files)
  - [3.3 File formats and naming conventions](#33-file-formats-and-naming-conventions)
    - [3.3.1 File formats](#331-file-formats)
    - [3.3.2 Naming conventions](#332-naming-conventions)
- [4. DATA-SPECIFIC INFORMATION](#4-data-specific-information)
  - [4.1 Spatial\_Units.geojson](#41-spatial_unitsgeojson)
  - [4.2. Attributes](#42-attributes)
    - [4.2.1 Spatial\_Units-Land\_Use\_Types.geojson](#421-spatial_units-land_use_typesgeojson)
    - [4.2.2 Spatial\_Units-Accessibility.geojson](#422-spatial_units-accessibilitygeojson)
    - [4.2.3 Spatial\_Units-Visibility.geojson](#423-spatial_units-visibilitygeojson)
    - [4.2.4 Spatial\_Units-Shade\_3pm.geojson](#424-spatial_units-shade_3pmgeojson)
    - [4.2.5 Spatial\_Units-Flood\_Safety.geojson](#425-spatial_units-flood_safetygeojson)
    - [4.2.6 Spatial\_Units-Infiltration\_Capacity.geojson](#426-spatial_units-infiltration_capacitygeojson)
    - [4.2.7 Spatial\_Units-Space\_along\_Streams.geojson](#427-spatial_units-space_along_streamsgeojson)
    - [4.2.8 Spatial\_Units-Green\_Area.geojson](#428-spatial_units-green_areageojson)
    - [4.2.9 Spatial\_Units-NDVI.geojson](#429-spatial_units-ndvigeojson)
    - [4.2.10 Spatial\_Units-Soil\_Quality.geojson](#4210-spatial_units-soil_qualitygeojson)
  - [4.3 Analysis Results](#43-analysis-results)
    - [4.3.1 Spatial\_Units-All\_Attributes.geojson](#431-spatial_units-all_attributesgeojson)
    - [4.3.2 Spatial\_Units-MCDA.geojson](#432-spatial_units-mcdageojson)
    - [4.3.3 Spatial\_Units-Typology\_Construction.geojson](#433-spatial_units-typology_constructiongeojson)
- [5. SHARING/ACCESS INFORMATION](#5-sharingaccess-information)
  - [5.1 Licenses/restrictions placed on the data](#51-licensesrestrictions-placed-on-the-data)
  - [5.2 Links to other resources](#52-links-to-other-resources)
    - [5.2.1 Links to publications that cite or use the data](#521-links-to-publications-that-cite-or-use-the-data)
    - [5.2.2 Links to other publicly accessible locations of the data](#522-links-to-other-publicly-accessible-locations-of-the-data)
    - [5.2.3 Was data derived from another source?](#523-was-data-derived-from-another-source)
  - [5.3 Recommended citation for this dataset](#53-recommended-citation-for-this-dataset)

# 1. GENERAL INFORMATION

## 1.1 Unpacking Dresden

Dresden is considered one of the greenest cities in Europe, with approximately 62% of its total area covered by forests, parks, and green spaces. This extensive green infrastructure includes the large woodland of the Dresdner Heide in the north and the Großer Garten in the city center, contributing to both ecological richness and urban quality of life. The city’s location in the Elbe Valley, framed by vineyards and wooded hills, is defined by the Elbe River, which meanders through the urban fabric and is bordered by wide river meadows. These meadows, cutting across the city, have historically hosted a variety of uses and activities—visible in old photographs—and remain a defining feature of Dresden's atmosphere and spatial identity.

The Environment Office, responsible for nature conservation, places great emphasis on the protection of biotopes within the city. These areas not only serve as essential refuges for rare and endangered species, such as the beaver and corn crake, but also function as peaceful recreational spaces for residents. The presence of such species within the urban core is seen as a significant achievement in local conservation efforts and a testament to the ecological quality of Dresden's landscape.

Dresden’s built environment reflects a complex layering of historical reconstruction, post-war development, and more recent car-centric urban expansion. The city is most recognizably shaped by its flood control strategies, which have left a prominent mark in the form of the wide, grassy Elbe meadows that traverse the urban core. While these meadows serve as a natural buffer for high waters, they remain largely undeveloped green corridors with limited ecological or recreational diversity. Beyond these, Dresden’s green spaces are relatively limited, with only a few notable urban parks and one major urban forest. Much of the city’s later development—particularly in the post-war and post-reunification periods—has prioritized road infrastructure and low-density layouts, contributing to a fragmented urban fabric that often lacks pedestrian accessibility and integrated ecological planning. This context underscores the need for rethinking the relationship between the built environment and the landscape to better support both human and non-human life.

## 1.2 Dataset description

This dataset contains qualitative and/or quantitative data on key elements that integrate the ecological and social functions of the city.

Along with the Elbe river, Dresden comprises a dense network of streams, which are spread out across its fabric. Presently, the streams are secluded from being a valuable part of the city. The problems are characterised by ecological issues, inappropriate land use by residents, and artificial channeling (Project case description). They, along with the Elbe river hold potential to become elements of integrating the ecological and social functions of the city by reclaiming the historical identity of waterfronts and restoring natural habitats. Therefore, there arises a need to understand how to integrate these streams into the network of protected green areas and public spaces, while maximising their contribution to biodiversity while adapting to the risk of flooding within and around the city.

Additional details about the project can be obtained from [our report]([https://.../](https://sdgis-edu-tud.github.io/report-asa2025-groupf/)).

## 1.3 Author Information

1. Co-investigator 1
   - Name: Adriano Mancini  
   - Institution: TU Delft  
   - Email: <a.mancini-1@student.tudelft.nl>
2. Co-investigator 2
   - Name: Alankrita Sharma  
   - Institution: TU Delft  
   - Email: <a.sharma-73@student.tudelft.nl>
3. Co-investigator 3
   - Name: Alexandre Bry  
   - Institution: TU Delft  
   - Email: <a.m.e.bry@student.tudelft.nl>
4. Co-investigator 4
   - Name: Grase Stephanie Stuka  
   - Institution: TU Delft  
   - Email: <grasestephaniestuka@student.tudelft.nl>
5. Co-investigator 5
   - Name: Soroush Saffarzadeh  
   - Institution: TU Delft  
   - Email: <s.saffarzadeh@student.tudelft.nl>

## 1.4 Dates of data collection

Data processing date: June \- July 2025

## 1.5 Geographic location of data collection

Dresden is located in eastern Germany, specifically in the state of Saxony, near the Czech border. It sits on both banks of the Elbe River, within the Dresden Basin, the Lusatian granitic crust to the north, and the Elbe Sandstone Mountains to the east.

- City coordinates: 51° 3' 1.4652'' N and 13° 44' 14.1432'' E
- Google map link [Dresden](https://maps.app.goo.gl/ZN1TXFU7RVbFkqdB9)

## 1.6 Keywords

Stream Restoration, Spatial Analysis, FAIR Data, MCDA, Typology Construction

## 1.7 Language

English

## 1.8 Information about funding sources that supported the collection of the data

This research project was not funded by any association since it is part of the assignments for Applied Spatial Analysis for Sustainable Urban Development at TU Delft.

# 2. METHODOLOGICAL INFORMATION

## 2.1 Research questions, methods and envisioned uses

Along with the Elbe river, Dresden comprises a dense network of streams, which are spread out across its fabric. Presently, the streams are secluded from being a valuable part of the city. The problems are characterised by ecological issues, inappropriate land use by residents, and artificial channeling. They, along with the Elbe river hold potential to become elements of integrating the ecological and social functions of the city by reclaiming the historical identity of waterfronts and restoring natural habitats. Therefore, there arises a need to understand how to integrate these streams into the network of protected green areas and public spaces, while maximising their contribution to biodiversity while adapting to the risk of flooding within and around the city.

These concerns and identified potentials beg the question that, **how can urban streams be restored and integrated in Dresden's fabric, such that there is a synergy between human activities and the natural environment?**

This is investigated by adopting an integrated approach for **biodiversity**, **climate adaptation** and **quality of life**.

Based on the three criteria that we decided to tackle, we came up with sub-research questions and numerical indicators that we could use to evaluate them. These numerical indicators are called attributes and have to be normalised—in our case between 0 and 1—so that they can be compared, weighted and thereafter clustered properly depending on their relevance and similarities.

### 2.1.1 Sub-Research question 1 (Biodiversity)

**What are the potentials and current urgencies in the integration of the natural elements in the urban landscape of Dresden?**

- **Attribute 1: Green connectivity (quantitative)**: Aims to identify the potential green corridors along the streams.
- **Attribute 2: Soil Quality (qualitative)**: Aims to identify land areas along the stream which have poor soil quality.
- **Attribute 3: Plant Health: (quantitative)**: Aims to identify which plants along the streams have a poor health compared to others.

### 2.1.2 Sub-Research question 2 (Climate adaptation)

**What are the main challenges and the potential spatial interventions to adapt to climate change?**

- **Attribute 1: Flood exposure (qualitative)**: Aims to identify which areas are most at risk under different flood scenarios, and how these risks are spatially distributed in relation to existing infrastructure and urban development.  
- **Attribute 2: Soil infiltration (qualitative)**: Aims to understand the capacity of different soils—especially those in proximity to water bodies—to absorb and regulate rainwater.  
- **Attribute 3: Shading (quantitative)**: Aims to know the shade coverage of open spaces across the stream area networks, to identify the potential areas for heat resilience. Also, the open spaces that have the highest exposure to the heat waves can be recognised through the ground shadow analysis, especially during the peak time of warm periods in the area.
- **Attribute 4: Available space near streams (quantitative)**: Aims to understand how much space is available to allow for simple interventions and improve the current situation.

### 2.1.3 Sub-Research question 3 (Quality of Life)

**How accessible, inviting, and diverse is Dresden's public space, and how can it reach its full potential?**

- **Attribute 1: Visibility of the streams from surrounding urban areas (qualitative)**: The visibility factor refers to how visible the streams are from an urban area. This is also a qualitative value that reflects the visual openness of the streams through a quantitative method.  
- **Attribute 2: Peripherality (qualitative)**: The analysis aims to identify spatial units that are close or far away from the places where many people live.  
- **Attribute 3: Diversity (land use variety)**: This analysis identifies the types of land use around the stream corridors. More variety of uses indicates a more vibrant and inclusive public space.

### 2.1.4 Analysis Methods

Two data-driven methods were used to conduct the analysis:

- **S-MCDA (Spatial Multi-Criteria Decision Analysis)** — S-MCDA was used to weigh the different attributes against each other. The method supports decision-making by evaluating and ranking alternatives (the attributes) within the three objectives of biodiversity, climate adaptation and quality of life.
- **Typology Construction** — Typology construction is used to group attributes into homogenous types based on similarities. This was used to identify patterns in data and make clusters of attributes that show similarity, which can thereafter be used to understand the type of interventions which would be impactful.

### 2.1.5 Envisioned uses of the data set

Analyses that tackle biodiversity, climate adaptation and/or quality of life in the areas around streams and rivers in Dresden.

## 2.2 Methods for processing the data

### 2.2.1 Defining spatial units

The spatial units used in this study are hexagons with a dimension of 250 meters. The study area of Dresden is divided using a complete surface of a hexagonal pattern. Then it is overlaid with the water stream network and river body from OpenStreetMap to keep only the hexagons that intersect with at least one stream. Finally, the isolated hexagons were removed.

The main reason behind picking the dimensions of 300 meters is based on two main reasons:

1. The walking/biking distance: the estimated radius is used to evaluate the spaces around the water stream within a low walking distance, as pedestrians or cyclists have the highest exposure and engagement with urban streams.  
2. The space but not the line: the spatial units are also going to determine the probable area of intervention. Then the streams are not the only lines that need to be changed, but the space surrounding them is also affected in both ways. This space includes the buildings, facilities, and natural habitats that all have synergies along with their neighboring stream structure.

The spatial units are also filtered by a 500-meter buffer of the main river, Elbe, as it is one of the key spatial elements that have shaped the city’s form, functions, mobilities, and identity that cannot be overlooked. So, a larger buffer of hexagonal spatial units where divided in the buffer zone of the Elbe river as it covers a larger area of the urban fabric in terms of biodiversity, morphology, climate adaptation, and quality of life.

All attributes also need to be aggregable at the scale of the spatial units, so that we can assign one unique value to each spatial unit for each attribute. This was an important limitation on the type of computations and therefore the type of attributes that we can use.

### 2.2.2 Processing Data for S-MCDA

- **Biodiversity**:  
  - **Attribute 1:  Green connectivity (quantitative)**: the area of the vegetation layer from OpenStreetMap was quantified. This layer was then intersected with the spatial units to focus on the vegetation which falls within the units. The values of the areas were then graduated to visualise the spatial units which lacked vegetation to those which were densely vegetated. These values were then normalised to make them comparable to other attributes. Here, 0 indicates the spaces which lack vegetation and 1 indicates dense vegetation, signalling at the potential spaces to add vegetation and form green corridors along the streams.  
  - **Attribute 2: Soil Quality (qualitative)**: It is measured using the Bodenqualität (soil quality) layer from the Dresden open data portal. The different soil qualities, ranging from 1-6 (1 indicating low and 6 indicating extremely high quality) was intersected with the layer of the spatial units. The weighted area for each soil type in each unit was calculated by multiplying their area by their quality number. All different soil qualities present in each spatial unit were then aggregated to get the weighted area in each unit. These values were ultimately normalised and graduated to create the final map, which showed us the spatial units where there is a high concentration of poor soil quality, which are necessary to be addressed for biodiversity. Few spatial units do not have any value, aa the layer did not hold any data at those locations. Those units are dropped out from the MCDA analysis.  
  - **Attribute 3: Plant Health (quantitative)**: Plant health is measured using the normalized difference vegetation index (NDVI), computed as an average of the values in June, July and August (when the vegetation is facing the highest stress) over the five last available years (2020-2024). The values are computed on a 10 by 10 m raster (based on the values of Sentinel-2), and then averaged over the spatial units. Higher values correspond to healthier vegetation.  
- **Climate adaptation**:  
  - **Attribute 1: Flood exposure (qualitative)**: As part of a study commissioned by the Civil Engineering Office in 2020, following the introduction of a new flood protection law in the Saxony region, a new rainfall-runoff model was developed. Based on this model, working maps were created to show the areas that would be flooded during events expected to statistically occur once every 20 and 100 years, as well as under an additional extreme scenario. Using the spatial layers from these scenarios, which indicated the areas affected by each flood event, we created an attribute for “exposure to floods.” Exposure to one or more flood risk areas was assigned a negative weight, with the severity increasing for each additional scenario to which an area was exposed. The aggregation of this data into a single attribute was carried out by first creating separate polygons for areas where multiple flood scenarios overlapped. Then, a value between 0 and 1 was assigned to each layer, using percentage-based weighting to reflect the relative severity of each scenario. We were interested in answering the following question: which are the most flood-prone areas in Dresden?  
  - **Attribute 2: Soil infiltration (qualitative)**: Soil sealing caused by infrastructure prevents water from being absorbed into the ground, accelerates surface runoff, and reduces space for natural stream dynamics. Identifying areas most affected by man-made interventions was therefore a key priority. However, even in unsealed areas, not all soils absorb water equally. In the context of an analysis aimed at informing integrated, city-wide interventions, it is essential to consider the varying water absorption capacities of different soil types. To address this, we used the Soil Infiltration Capacity layer to assign each spatial unit a degree of infiltration potential. This allowed us to distinguish between areas where water can be absorbed with minimal, ‘light’ ecological restoration and those that require more intensive interventions—such as the removal of built structures or the restoration of ecological processes specific to the local soil type and its characteristics.  
  - **Attribute 3: Shading (quantitative)**: By knowing the shade coverage of open spaces across the stream area networks, the potential areas for heat resilience can be spotted. Also, the open spaces that have the highest exposure to the heat waves can be recognised through the ground shadow analysis, especially during the peak time of warm periods in the area. The DSM and DTM raster layers were needed to run the shadow analysis based on the building and vegetation heights. The raster layer was clipped out based on the dissolved layer of spatial units to limit the area of analysis. The buildings layer was also masked out from the DSM layer and patched with it again to represent the updated building heights. After that, the aspect and edge heights were calculated using the UMEP plugin to process the preliminary data for the shadow analysis. The shadow analysis is done based on three time intervals during the day within the peak times of warm periods in the area. The output layer with which was a raster layer, was then aggregated to the spatial units using the Zonal Statistics tool to translate the shading values to the polygon spatial units. The output values were the median (average) values contained within each spatial unit and were already distributed between zero (full shadow) and one (no shadow) values.  
  - **Attribute 4: Available space near streams (quantitative)**: The necessity of available open space along the streams and the water body will be a potential opportunity for design interventions to prevent, or at least reduce, the flood risk along the streams’ banks. This can be achieved by calculating the available open space areas in the close proximity of the streams and rivers of Dresden. This was assessed by using the land use ground layer collected from the Surfdrive dataset and filtered based on the undeveloped land and grassland values. After that, the layer was intersected with the spatial units to calculate the coverage space of each land type within each spatial unit before being joined by attributes to the raw spatial units again. By joining the intersected layer to spatial units based on their join attributes, the available space within each spatial unit is already available. In order to normalize the values, the area values were all divided by the highest area number, and the new results were distributed between zero, as the lowest coverage or available area, and one, as the highest coverage and available area.
- **Quality of life**:  
  - **Attribute 1: Visibility of the streams from surrounding urban areas (qualitative)**: The analysis is conducted by interpolating points from the streamline with a 500-meter radius of urban surroundings.  
  - **Attribute 2: Peripherality (quantitative)**: The analysis computes the shortest paths from sample points in the city to the centers of the spatial units, to compute an approximation of a value proportional to the population that lives at a distance smaller than 1km of the spatial unit. This gives a measure of accessibility or centrality, which is then normalised and reversed and therefore called peripherality.  
  - **Attribute 3: Diversity (land use variety)**: This analysis identifies the types of land use around the stream corridors, more variety of uses enhances the connectivity of streams with the current urban fabric. It is well connected if there are various public spaces and/ or amenities present.

Once each attribute has produced a normalised value for each spatial unit, all the attributes need to be aggregated into one final value. Since all of them do not participate equally in the goals we mentioned earlier, we tried to weight them according to their relative importance in achieving our goals. These weights could then be used to compute a weighted average that is easier to use, thanks to reducing the problem to one dimension instead of several dimensions.

To compute the weights, we made individual Saaty matrices for the attributes of each of the three objectives. Then, we divided them by 3 to assign the same weight to the three attributes, and got a final set of weights that summed to 1\. We chose this method because it allowed us to assign more weights to the most reliable and pertinent attributes, while maintaining the balance between the three main objectives.

## 2.3 Instrument- or software-specific information

- QGIS desktop 3.34.10 was used for geospatial analysis. It was used to compute the layers for S-MCDA and prepare the base layer for typology construction.
- R-Studio version 2024.12.1+563 was used to conduct the analysis for typology construction using k-means clustering.

# 3. FILE OVERVIEW

Are there multiple versions of the dataset? No

## 3.1 File List

### 3.1.1. Spatial Units

The spatial units that are used for the analysis are contained in Spatial\_Units.geojson. This is the base layer for all the layers containing the single attributes and the analysis results.

### 3.1.2. Final Attributes

- Spatial\_Units-Land\_Use\_Types.geojson: Land use variety  
- Spatial\_Units-Accessibility.geojson: Population living at less than 1km  
- Spatial\_Units-Visibility.geojson: Visibility of the Streams  
- Spatial\_Units-Shade\_3pm.geojson: Proportion of shaded area at 3pm  
- Spatial\_Units-Flood\_Safety.geojson: Flood safety based on a simulation  
- Spatial\_Units-Infiltration\_Capacity.geojson: Infiltration capacity of the soil  
- Spatial\_Units-Space\_along\_Streams.geojson: Amount of usable space available  
- Spatial\_Units-Green\_Area.geojson: Proportion of area covered by greenery  
- Spatial\_Units-NDVI.geojson: Plant health based on NDVI  
- Spatial\_Units-Soil\_Quality.geojson: Soil quality

### 3.1.3. Analysis Results

The final results of the analysis consists of 3 main files:

- Spatial\_Units-All\_Attributes.geojson: the aggregation of the normalised values of all the attributes for all the spatial units  
- Spatial\_Units-MCDA.geojson: the results of our MCDA analysis based on the attributes and the weights that we used. There is one column for each category (Biodiversity, Quality of Life and Climate Adaptation) and one column with the average for the 3 categories.  
- Spatial\_Units-Typology\_Construction.geojson: the results of our typology construction analysis on a subset of the attributes. It contains both the clusters and the distance from each point to the center of the cluster.

## 3.2 Relationship between files

All the output layers contain all the columns of the base spatial units layer. Especially, they all contain the column “id”, which gives a unique identifier to each spatial unit and can be used to link the different files together.

## 3.3 File formats and naming conventions

### 3.3.1 File formats

GeoJSON (with specific CRS)

### 3.3.2 Naming conventions

- File names:  
  - Capitalise the main words  
  - Replace spaces with “\_”  
  - Use “-” to separate different pieces of information  
- Attributes:  
  - Capitalise the words (mostly)  
  - Replace spaces with “\_”

# 4. DATA-SPECIFIC INFORMATION

- Missing data code: NA
- Not Applicable: N/A

## 4.1 Spatial\_Units.geojson

1. Number of variables: 8  
2. Number of cases/rows: 2225  
3. Total file size: 1.4MB  
4. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| id | Unique identifier of the row | integer | N/A | 0 |
| left | Left coordinate of the spatial unit | float | meters (EPSG:25833) | 0 |
| top | Top coordinate of the spatial unit | float | meters (EPSG:25833) | 0 |
| right | Right coordinate of the spatial unit | float | meters (EPSG:25833) | 0 |
| bottom | Bottom coordinate of the spatial unit | float | meters (EPSG:25833) | 0 |
| row\_index | Row index of spatial unit in the set of hexagons | integer | N/A | 0 |
| col\_index | Column index of spatial unit in the set of hexagons | integer | N/A | 0 |
| Type | River or stream | string | N/A | 0 |

## 4.2. Attributes

In this category, all the layers have all the variables of Spatial\_Units.geojson as well as other variables. We will only describe the supplementary variables. Also, they all have 2225 rows corresponding to the same 2225 spatial units. Finally, all the layers contain a variable called “Normalised\_Value” that is the normalised variable between 0 and 1 that we used for MCDA. In the description of this variable, “reversed” means that the lowest value became 1 and the highest value became 0, while “not reversed” means that the lowest value became 0 and the highest value became 1\.

### 4.2.1 Spatial\_Units-Land\_Use\_Types.geojson

1. Number of variables: 8 \+ 2  
2. Total file size: 1.4MB  
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| Different\_Land\_Uses | Number of different land uses in the spatial unit | integer | N/A | 0 |
| Normalised\_Value | “Different\_Land\_Uses” normalised between 0 and 1 (not reversed) | float | N/A | 0 |

### 4.2.2 Spatial\_Units-Accessibility.geojson

1. Number of variables: 8 \+ 3  
2. Total file size: 1.7 MB  
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| Pop\_Density\_Sum | Sum of the population densities of all the starting points that were closer than 1km | float | ppl/hectare | 0 |
| Pop\_Density\_Sum\_Times\_2000\_Minus\_Cost\_Sum | Sum of the “pop × (2000 \- cost)” where pop is the population of the starting point and cost the distance from the starting point to the spatial unit centroid | float | ppl/hectare×m | 0 |
| Normalised\_Value | Normalised between 0 and 1 (Not reversed) | float | N/A | 0 |

### 4.2.3 Spatial\_Units-Visibility.geojson

1. Number of variables: 8 \+ 4  
2. Total file size: 1.6 MB  
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| \_sum | Sum of the visible pixels | float | N/A | 0 |
| \_count | Sum of the whole pixels | float | N/A | 0 |
| \_mean | Proportion of visible pixels to empty pixels | float | N/A | 0 |
| Normalised\_Value | Normalised between 0 and 1 (Not reversed) | float | N/A | 0 |

### 4.2.4 Spatial\_Units-Shade\_3pm.geojson

1. Number of variables: 8 \+ 4  
2. Total file size: 1.6 MB  
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| Count\_Pixels | Number of total pixels | float | N/A | 0 |
| Count\_Illuminated | Number of illuminated pixels | float | N/A | 0 |
| Proportion\_Shaded | Proportion of illuminated pixels to empty pixels | float | N/A | 0 |
| Normalised\_Value | Normalised between 0 and 1 (Reversed) | float | N/A | 0 |

### 4.2.5 Spatial\_Units-Flood\_Safety.geojson

1. Number of variables: 8 \+ 5  
2. Total file size: 1.6 MB  
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| LOW\_AREA | Area corresponding to low risk | float | m² | 0 |
| MID\_AREA | Area corresponding to medium risk | float | m² | 0 |
| EXT\_AREA | Area corresponding to extreme risk | float | m² | 0 |
| SAFE\_AREA | Area corresponding to no risk | float | m² | 0 |
| Normalised\_Value | Normalised between 0 and 1 (Reversed) | float | N/A | 0 |

Here, the risk refers to the category of risk that was assigned in the simulation made by the authorities of Dresden. Each risk value was assigned a value (0 for EXT, 0.33 for MID, 0.67 for LOW and 1 for SAFE), so that 0 corresponds to highest risk and 1 to lowest risk, and the weighted average was computed in each spatial unit, before being normalised.

### 4.2.6 Spatial\_Units-Infiltration\_Capacity.geojson

1. Number of variables: 8 \+ 1  
2. Total file size: 1.5MB  
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| Normalised\_Value | Normalised value of the average infiltration capacity of the soil (not reversed) | float | N/A | 0 |

### 4.2.7 Spatial\_Units-Space\_along\_Streams.geojson

1. Number of variables: 8 \+ 2  
2. Total file size: 1.5MB  
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| availablespacearea\_new  | Area of available space in the spatial unit | float | m² | 0 |
| Normalised\_Value | “availablespacearea\_new” divided by the area of the spatial unit (it is directly normalised between 0 and 1\) | float | N/A | 0 |

### 4.2.8 Spatial\_Units-Green\_Area.geojson

1. Number of variables: 8 \+ 3  
2. Total file size: 1.6MB  
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| Area | Area of the spatial unit | float | m² | 0 |
| Green\_Area | Area of greenery in the spatial unit | float | m² | 0 |
| Normalised\_Value | “Green\_Area” / “Area” (it is directly normalised between 0 and 1\) | float | N/A | 0 |

### 4.2.9 Spatial\_Units-NDVI.geojson

1. Number of variables: 8 \+ 2  
2. Total file size: 1.5MB  
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| ndvi\_mean | Average value of the Normalised Difference Vegetation Index in the months of June, July, August from 2020 to 2024 | float | N/A | 0 |
| Normalised\_Value | “ndvi\_mean” normalised between 0 and 1 (not reversed) | float | N/A | 0 |

### 4.2.10 Spatial\_Units-Soil\_Quality.geojson

1. Number of variables: 8 \+ 4  
2. Total file size: 1.7MB  
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| Area | Area of the spatial unit covered with data about soil quality | float | m² | 6 (actually corresponds to 0m²) |
| Sum\_area\_times\_quality | Aggregated sum of “area × quality” where quality is a value from 1 to 6 associated based on the raw data | float | m² | 6 |
| Average\_Quality | “Sum\_area\_times\_quality” divided by “Area” | float | N/A | 6 |
| Normalised\_Value | “Average\_Quality” normalised between 0 and 1 (not reversed) | float | N/A | 0 |

“Normalised\_Value” does not have any missing values because the missing values were replaced by 0\. We made this choice because missing values corresponded to urban areas without any data, where we can say that there is no infiltration because of the soil cover.

## 4.3 Analysis Results

In this category, all the layers have all the variables of Spatial\_Units.geojson as well as other variables. We will only describe the supplementary variables. Also, they all have 2225 rows corresponding to the same 2225 spatial units.

### 4.3.1 Spatial\_Units-All\_Attributes.geojson

1. Number of variables: 8 \+ 10
2. Total file size: 1.9 MB
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| Space\_along\_Streams |  | float | N/A | 0 |
| Soil\_Quality |  | float | N/A | 0 |
| NDVI |  | float | N/A | 0 |
| Infiltration |  | float | N/A | 0 |
| Green\_Area |  | float | N/A | 0 |
| Flood\_Safety |  | float | N/A | 0 |
| Land\_Use_Types |  | float | N/A | 0 |
| Shade\_3pm |  | float | N/A | 0 |
| Accessibility |  | float | N/A | 0 |
| Visibility |  | float | N/A | 0 |

Each variable corresponds to the “Normalised\_Value” variable of the corresponding file mentioned in the previous section.

### 4.3.2 Spatial\_Units-MCDA.geojson

1. Number of variables: 8 \+ 2
2. Total file size: 1.5 MB  
3. Variable List:

| Full name | Description | Type of variable | Unit of measurement | Number of missing values |
| :---- | :---- | :---- | :---- | :---- |
| Cluster | ID of the cluster that the row is in | integer | N/A | 0 |
| Cluster\_Dist | Euclidean distance from the row to the centroid of its cluster | float | N/A | 0 |

More information about the attributes used can be found in our report.

### 4.3.3 Spatial\_Units-Typology\_Construction.geojson

the results of our typology construction analysis on a subset of the attributes. It contains both the clusters and the distance from each point to the center of the cluster.

# 5. SHARING/ACCESS INFORMATION

## 5.1 Licenses/restrictions placed on the data

This work is available under a Creative Commons Attribution 4.0 International License. For license details, see [http://creativecommons.org/licenses/by/4.0/](http://creativecommons.org/licenses/by/4.0/).

## 5.2 Links to other resources

### 5.2.1 Links to publications that cite or use the data

[https://sdgis-edu-tud.github.io/report-asa2025-groupf/](https://sdgis-edu-tud.github.io/report-asa2025-groupf/)

### 5.2.2 Links to other publicly accessible locations of the data

[https://github.com/sdgis-edu-tud/report-asa2025-groupf/tree/main/src](https://github.com/sdgis-edu-tud/report-asa2025-groupf/tree/main/src)

### 5.2.3 Was data derived from another source?

Yes, both from the educational institution (TU Delft, Faculty of Architecture & Built Environment) dataset and the open-data public datasets from the study area.

## 5.3 Recommended citation for this dataset

None.

This README.md file template was generated on 2022-04-19 by Claudiu Forgaci and Adele Therias according to the 4TU.ResearchData [Guidelines for creating a README file](https://data.4tu.nl/info/en/use/publish-cite/upload-your-data-in-our-data-repository) and the Cornell University template [Guide to writing "readme" style metadata](https://cornell.app.box.com/v/ReadmeTemplate) and is licensed under CC BY 4.0
