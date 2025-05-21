# Computational Techniques in Meteorology

This repository contains coursework completed for the *Computational Techniques in Meteorology* course. It showcases the use of Python, Jupyter Notebooks, and scientific libraries such as `matplotlib`, `numpy`, and `pandas` for data analysis and visualization in meteorological and climatological contexts.

Each assignment folder includes:
- A Jupyter Notebook (`.ipynb`)
- Supporting plots and figures (`.png`)
- A short `README.md` describing the assignment and methods used
  

## Assignments

- [Assignment 04](assignment04) – Time Series and Bar Chart Visualization
- [Assignment 05](assignment05) – SST Anomalies and Topographic Visualization
- [Assignment 06](assignment06) – Climatological Comparison of U.S. Cities (2022 vs. 1991–2020)
- [Assignment 07](assignment07) – Atmospheric Sounding Visualization with Skew-T
- [Assignment 08](assignment08) – Visualization of GOES-16 RGB, 300K Isentropic Fields, and Gridded MSLP from Surface Data
- [Assignment 09](assignment09) – Synoptic-scale analysis using 300 hPa wind fields and 850–1000 hPa thickness
  

## Python Libraries Used

The following libraries were used throughout this coursework portfolio:

- `numpy` – Numerical array operations
- `pandas` – Data manipulation and time series handling
- `matplotlib` – Plotting and figure generation
- `cartopy` – Geospatial mapping and projections
- `geopandas` – Reading and analyzing shapefiles and geospatial vector data
- `xarray` – Multidimensional gridded data (e.g., NetCDF)
- `scipy` – Scientific computing (e.g., interpolation, filtering, stats)
- `metpy` – Meteorological calculations, unit handling, Skew-T diagrams, and hodographs
- `siphon` – Accessing meteorological data from remote servers (e.g., THREDDS, Wyoming Soundings)
- `datetime` – Handling time formats and time series
- `cftime` – Support for non-standard calendar time in climate datasets
- `mpl_toolkits` – 3D and advanced plot utilities (e.g., inset axes, specialized map layouts)
  

## File Formats Used

The following file formats were used for data input, processing, and analysis throughout this coursework:

- **`.csv` – Comma-Separated Values**  
  Used for tabular meteorological and observational data.

- **`.nc` – NetCDF (Network Common Data Form)**  
  Used for multidimensional scientific datasets, such as gridded model output and satellite data.

- **`.txt` – Plain Text File**  
  Used for raw atmospheric sounding data (e.g., from the Wyoming upper-air archive).

- **`.xml` – Extensible Markup Language**  
  Accessed indirectly via THREDDS catalogs when downloading remote datasets.

- **`.zip` – ZIP Archive**  
  Used to bundle and extract shapefiles and other related geospatial data files.

