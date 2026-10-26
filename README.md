# AED Access in Liverpool

If someone has a cardiac arrest, how close is the nearest defibrillator to them? And does that access depend on where in Liverpool they live?

I built this dashboard to explore that question, looking at how access changes when you account for opening hours and whether defibrillators are open to the public.

[View the live dashboard](https://maryam-sulayman.github.io/liverpool-aed-access/)

## About the project

The dashboard brings together defibrillator locations, census data and deprivation data to compare access across Liverpool neighbourhoods. You can filter by availability and access type to see how the results change.

## Main finding

Across all registered devices in the analysis, 67% of neighbourhoods are within an estimated five-minute walk of a defibrillator. When only devices recorded as publicly accessible and available 24/7 are included, this falls to 8%.

This highlights how much opening hours and access restrictions affect coverage, beyond simply where defibrillators are located.

## Data sources

- The Circuit — national defibrillator registry
- ONS Census 2021
- MHCLG Index of Multiple Deprivation (IMD) 2019

## Tools used

Python, Panel, Folium/Leaflet, GeoPandas, OSMnx, NetworkX and Matplotlib.

## Dashboard preview

![Dashboard screenshot](dashboard.png)
