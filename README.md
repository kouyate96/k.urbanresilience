# Urban Flood Risk and Resilience Mapping in Bamako, Mali

## Hydroinformatics & Urban Resilience Specialist  
### Fousseini Kouyaté, Ph.D

Climate Risk | Flood Modeling | GIS & Remote Sensing | Urban Infrastructure | Disaster Risk Management

---

# Overview

This repository presents a comprehensive urban flood hazard and resilience assessment for the city of Bamako, Mali, using remote sensing, geospatial analysis, flood hazard datasets, and urban land cover information.

The project aims to support climate-resilient urban planning, disaster risk reduction (DRR), flood-prone infrastructure identification, and decision-support for urban resilience investments in rapidly urbanizing African cities.

The workflow integrates:

- Flood hazard mapping
- Land use / land cover analysis
- Flood exposure assessment
- Urban resilience prioritization
- Flooded built-up and agricultural area analysis
- Spatial vulnerability mapping

This work aligns with international urban resilience and disaster risk management initiatives, including World Bank Urban, Resilience and Land programs.

---

# Study Area

The study focuses on Bamako, the capital city of Mali, located along the Niger River in West Africa.

Rapid urbanization, floodplain occupation, increasing impervious surfaces, and climate variability have significantly increased flood exposure and vulnerability in the city.

---

# Objectives

The main objectives of this project are:

- Assess flood hazard intensity across multiple return periods
- Identify flood-prone built-up and agricultural areas
- Quantify flood exposure patterns
- Develop a Flood Impact Priority Index
- Support climate-resilient urban planning and infrastructure management
- Provide spatial decision-support tools for flood resilience strategies

---

# Datasets Used

| Dataset | Source | Purpose |
|---|---|---|
| JRC Flood Hazard Maps v2.1 | JRC / CEMS GLOFAS | Flood depth mapping |
| ESA WorldCover 2021 | ESA | Land use / land cover |
| SRTM DEM | USGS | Elevation and slope |
| OpenStreetMap Basemap | OSM | Urban visualization |

---

# Methodology

The methodology combines flood hazard analysis, terrain analysis, and land-use exposure assessment using Google Earth Engine.

## Main Steps

### 1. Flood Hazard Mapping
Flood depth maps were extracted from the JRC Flood Hazard dataset for:

- RP10
- RP20
- RP50
- RP100
- RP200
- RP500

### 2. Land Use Classification
ESA WorldCover 2021 was used to identify:

- Built-up areas
- Agricultural land
- Water bodies
- Vegetation classes

### 3. Flood Exposure Assessment
Flood depth thresholds (> 0.5 m) were applied to determine:

- Flooded built-up areas
- Flooded agricultural zones
- Flood intensity classes

### 4. Flood Impact Priority Index
A resilience-oriented spatial index was developed using:

- Flood depth
- Terrain slope
- Land-use weighting

The index identifies priority intervention zones for:

- Urban drainage
- Flood mitigation
- Resilience planning
- Infrastructure adaptation

---

# Technologies

- Google Earth Engine
- JavaScript
- Remote Sensing
- GIS & Spatial Analysis
- Urban Flood Modeling
- Geospatial Data Analytics

---

# Repository Structure

```bash
├── maps/
├── figures/
├── scripts/
├── outputs/
├── README.md
```

---

# Key Results

## 1. Land Use / Land Cover Map

The LULC analysis shows that built-up areas dominate the urban landscape of Bamako, particularly along the Niger River corridor, increasing flood exposure and urban vulnerability.

![LULC Map](figures/Bamako.png)

---

# Flood Hazard Maps

## RP10 Flood Depth

![RP10 Flood Depth](figures/RP10_Flood_Depth.png)

## RP20 Flood Depth

![RP20 Flood Depth](figures/RP20_Flood_Depth.png)

## RP50 Flood Depth

![RP50 Flood Depth](figures/RP50_Flood_Depth.png)

## RP100 Flood Depth

![RP100 Flood Depth](figures/RP100_Flood_Depth.png)

## RP200 Flood Depth

![RP200 Flood Depth](figures/RP200_Flood_Depth.png)

## RP500 Flood Depth

![RP500 Flood Depth](figures/RP500_Flood_Depth.png)

---

# Flooded Agricultural Areas

## RP10 Agricultural Flooding

![RP10 Agriculture](figures/RP10_Flood_Agriculture.png)

## RP50 Agricultural Flooding

![RP50 Agriculture](figures/RP50_Flood_Agriculture.png)

## RP100 Agricultural Flooding

![RP100 Agriculture](figures/RP100_Flood_Agriculture.png)

## RP200 Agricultural Flooding

![RP200 Agriculture](figures/RP200_Flood_Agriculture.png)

---

# Flooded Built-Up Areas

## RP10 Built-Up Flooding

![RP10 Built-Up](figures/RP10_Flood_Builtup.png)

## RP50 Built-Up Flooding

![RP50 Built-Up](figures/RP50_Flood_Builtup.png)

## RP100 Built-Up Flooding

![RP100 Built-Up](figures/RP100_Flood_Builtup.png)

## RP200 Built-Up Flooding

![RP200 Built-Up](figures/RP200_Flood_Builtup.png)

## RP500 Built-Up Flooding

![RP500 Built-Up](figures/RP500_Flood_Builtup.png)

---

# Flood Impact Priority Index

The Flood Impact Priority Index identifies highly vulnerable flood-prone urban zones requiring urgent intervention.

The index integrates:

- Flood hazard intensity
- Low-slope vulnerability
- Built-up exposure
- Agricultural exposure

This approach supports:

- Urban resilience planning
- Flood mitigation prioritization
- Climate adaptation strategies
- Infrastructure investment planning

![Flood Priority Index](figures/Flood_priority_index1.png)

---

# Key Findings

- Flood exposure increases significantly with higher return periods.
- Built-up areas located near the Niger River are highly vulnerable.
- Agricultural flood exposure is concentrated within floodplain corridors.
- Low-slope urban areas exhibit higher flood accumulation potential.
- The eastern section of Bamako presents critical resilience intervention hotspots.

---

# Policy Relevance

This work supports:

- Climate-resilient urban development
- Disaster Risk Management (DRM)
- Urban drainage planning
- Flood-resilient infrastructure design
- Spatial planning and land-use management
- Sustainable urban resilience strategies

The outputs can support governments, development partners, and urban planners in prioritizing flood adaptation investments.

---

# Future Improvements

Potential future developments include:

- Integration of population exposure
- Socioeconomic vulnerability assessment
- Real-time flood forecasting
- HEC-RAS hydraulic simulations
- Climate change flood scenarios
- Machine learning flood susceptibility analysis

---

# Contact

- LinkedIn: www.linkedin.com/in/fousseini-kouyate
- Email: your_email_here

---

# License

This repository is intended for academic, research, and professional portfolio purposes.
