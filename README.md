# AED Access in Liverpool

An interactive geospatial dashboard analysing access to public defibrillators (AEDs) 
across Liverpool, and how that access changes by time of day and access type.

## Live dashboard
You can view the live dashboard here: https://maryam-sulayman.github.io/liverpool-aed-access/

## What it shows
The dashboard maps walking-distance access to Liverpool's 499 registered AEDs across 
245 neighbourhoods, with filters for availability (all AEDs vs 24/7 only) and access 
type (public vs restricted). Access changes depending on which defibrillators 
are actually usable:

- All AEDs: 67% of areas within a 5-minute walk; 37% of over-65s live more than 5 minutes away.
- 24/7 only: drops to 38% of areas within a 5-minute walk; 63% of over-65s are underserved.
- 24/7 + restricted access (worst case): only 8% of areas within a 5-minute walk.

## Built with
Python, Panel, Folium/Leaflet, GeoPandas, OSMnx, NetworkX, matplotlib

## Data sources
- AED locations: The Circuit (British Heart Foundation national defibrillator registry)
- Boundaries & population: ONS 2021 Census
- Deprivation: MHCLG Index of Multiple Deprivation (IMD) 2019

All data is publicly available.

![Dashboard screenshot](dashboard.png)
