Travel Behavior Analysis and Business Site Selection in Zurich

This project was developed as part of the Computer Programming & Data Science – An Introduction with Python course at ETH Zurich. It integrates data science, geospatial analysis, and optimization techniques to analyze intra-urban travel behavior and determine optimal locations for new restaurants in the city of Zurich.

The project consists of two main components:
- Travel Behavior Analysis: Modeling how the intensity of social trips decays with distance using exponential, power-law, Newling, and weak decay functions. Results are visualized through decay curves and spatial maps.
- Business Site Selection: Solving a fuzzy Maximum Coverage Location Problem (Fuzzy-MCLP) using Google OR-Tools to identify restaurant locations that maximize weighted coverage, based on residents’ travel tolerance.


Installation Instructions：

Before running the code, install the following Python packages:
pandas geopandas osmnx networkx folium contextily numpy matplotlib ortools tqdm
