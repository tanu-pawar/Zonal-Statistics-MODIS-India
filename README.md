District-Level Vegetation and Land Surface Temperature Analysis (2001–2003 vs 2024–2025)
Project Overview

This project analyzes long-term changes in vegetation and land surface temperature across Indian districts using MODIS satellite datasets. The study compares two time periods:

Early 2000s (2001–2003)

Recent period (2024–2025)

The objective is to understand spatial patterns of vegetation cover and surface temperature and assess environmental changes over time.

Datasets Used

The following MODIS datasets from NASA were used:

MOD44B – Percent Tree Cover

MCD15A3H – Leaf Area Index (LAI)

MOD11A1 – Land Surface Temperature (Daytime LST)

All datasets were accessed and processed using Google Earth Engine.

Study Area

Country: India

Spatial Unit: District boundaries

Projection: WGS 1984 (EPSG: 4326)

District boundary data was used for zonal statistical analysis.

Variables Analyzed

Percent Tree Cover (%)

Leaf Area Index (LAI)

Land Surface Temperature (°C)

Methodology

The analysis was conducted using Google Earth Engine and ArcGIS Pro.

Step 1: Data Processing

Selected MODIS datasets for two time periods.

Generated mean composites for each period.

Converted LST from Kelvin to Celsius.

Step 2: Zonal Statistics

District-level mean values were calculated using zonal statistics.

Results were exported as GeoJSON and CSV files.

Step 3: Comparative Mapping

Created district-level maps for:

Tree Cover (2001–03 vs 2024–25)

LAI (2001–03 vs 2024–25)

LST (2001–03 vs 2024–25)

Change maps were generated to identify increase/decrease patterns.

Step 4: Visualization

Comparative layouts were designed in ArcGIS Pro.

At least one statistical plot was created to compare district averages.

Key Observations

Certain districts show decline in vegetation cover.

Urban regions show noticeable increase in land surface temperature.

Some agricultural regions demonstrate moderate vegetation increase.

Temperature rise is more pronounced in central and western India.
