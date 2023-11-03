# Modern GIS Workshop

Welcome! This repo contains the code and guides used for the I-Guide Forum 2023 at Columbia University. The slides for this workshop can be found [here](https://docs.google.com/presentation/d/1-oSLrcywtmlmt4aSWI4rDqCu_mR2V4luLvh5RSVjdnk/edit?usp=sharing).

## Requirements

- [VS Code](https://code.visualstudio.com/) (preferred but any IDE will work)
- [Docker](https://www.docker.com/get-started/)
- [DuckDB](https://duckdb.org/docs/archive/0.9.0/installation/index)
- [dbt](https://docs.getdbt.com/docs/core/installation)
- [pgAdmin](https://www.pgadmin.org/)
- Optional
    - GDAL (will install with Docker)
    - QGIS

## Data Downloads

- [NYC Flood Plains](https://data.cityofnewyork.us/Environment/Sea-Level-Rise-Maps-2020s-100-year-Floodplain-/ezfn-5dsb)
- [NYC Building Footprints](https://data.cityofnewyork.us/Housing-Development/Building-Footprints/nqwf-w8eh)
- [NYC 1-foot DEM](https://data.cityofnewyork.us/City-Government/1-foot-Digital-Elevation-Model-DEM-/dpc8-z3jc)
    - [Clipped DEM](https://storage.googleapis.com/matt-marketing/external/clipped-dem.tif)
- [NOAA Historical Weather Events](https://www.ncei.noaa.gov/pub/data/swdi/stormevents/csvfiles/)

# Workshop

## Part 1: GeoParquet

- [Link to code](./1-geoparquet/)

## Part 2: PostGIS

- [Link to code](./2-postgis/)

## Part 3: DuckDB

- [DuckDB Docs](https://duckdb.org/docs/installation/index)
- [Link to code](./3-duckdb/)

## Part 4: dbt

- [Installing dbt](https://docs.getdbt.com/docs/core/installation)
- [Link to code](./4-dbt/)

## Part 5: H3

- [Link to code](./5-h3/)
