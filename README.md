# OSM Post GIS

**Student:** Jennifer Todd  
**Course:** GIST 604B – Open Source GIS  
**Module:** Module 5 - OSM Post GIS Spatial Analysis  
**University of Arizona**  

## Project Description
This project focused on analyzing real-world geospatial data from OpenStreetMap using PostGIS and Python-based workflows. I worked with OSM-derived datasets in a spatial database, ran SQL queries for analysis, and used GeoPandas in Jupyter notebook.  

## Tools and Technologies
- OpenStreetMap (OSM)  
- PostgreSQL / PostGIS  
- SQL  
- Python (GeoPandas, pandas)  
- Jupyter Notebooks  
- GitHub Codespaces
  
## What I Did
- Set up and explored an OSM PostGIS database with multiple spatial layers  
- Ran and interpreted spatial SQL queries using joins, aggregations, and CTEs  
- Used the PostGIS geography type for spatial measurements  
- Executed SQL queries within Jupyter notebooks and visualized results using GeoPandas

## How to View / Run
[Instructions for viewing the project. For example:
- Link to live GitHub Pages site (if applicable)
- How to run a Python script
- How to open the map]

## Repository Structure
- Open the repository in GitHub Codespaces or a local environment with required dependencies installed  
- Start the PostGIS database environment
- Open and run the Jupyter notebooks  

## Repository Structure

    .
    ├── .devcontainer/
    │   ├── Dockerfile
    │   └── devcontainer.json
    ├── notebooks/
    │   ├── setup_osm_postgis.ipynb
    │   └── osm_postgis_queries.ipynb
    ├── sql/
    │   └── arizona/
    │       ├── 01_osm_restaurant_distribution.sql
    │       ├── 02_osm_park_area_by_county.sql
    │       ├── 03_osm_restaurants_near_streets.sql
    │       ├── 04_osm_railway_density_by_county.sql
    │       └── 05_osm_county_amenity_synthesis.sql
    ├── src/
    │   └── setup_osm_postgis.py
    ├── docker-compose.yml
    ├── pyproject.toml
    ├── uv.lock
    └── README.md
