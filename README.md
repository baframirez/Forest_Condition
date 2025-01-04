# Forest_Condition
Forest_Condition is a tool that utilizes Earth observation data from the Google Earth Engine (GEE) API with Python to analyze forest vegetation conditions using the Enhanced Vegetation Index (EVI) available in the MOD13Q1.061 dataset.

An example is included in the code, showcasing its application to key Paraguayan national parks, including Cerro Chovoreca, Defensores del Chaco, and Médanos del Chaco.
#### Key Features:

-   **Setup:**
    
    -   Integration with Google Earth Engine (requires authentication and initialization).
    -   Use of libraries like `ee`, `geemap`, and `pandas`.
-   **Protected Area Analysis:**
    
    -   Loading and exploring boundary data for protected parks using the `WCMC/WDPA` dataset.
    -   Extracting park names and other attributes for visualization and analysis.
