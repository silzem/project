This repository contains all **data, notebooks and outputs** for the personal project in the following course:

**Programming in Spatial Data Science (SDS210)**
University of Zurich (UZH)
Module Coordinator: Hendrik Wulf

# Project topic: Distribution of recent Wildfires across Australia's states/territories

## Repository Structure

This repository consists of 
- data
- notebooks
- outputs

## Data Source

Two sources were used for the data of this project:

1. An API to a csv for life fire data (MODIS Near Real Time) of NASA's FIRMS:
   
2. A boundary GeoPackage of Australia's States/Territories from the Australian Bureau of Statistics:

## Execution

The goal of the project is to show which Australian states/territories showed most records of active wildfires during the last 5 days.

**Workflow**
- Access active fire data
- Clean & Rearrange Data
- Add boundary GeoPackage of States/Territories
- Spatial Analysis: Count fires per State/Territory
- Visualise in a interactive Heatmap and Folium Map with Layers


