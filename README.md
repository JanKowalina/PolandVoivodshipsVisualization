# Visualization of Poland Voivodships Data

This project focuses on visualizing data related to Poland's voivodships (administrative subdivisions) using the Leaflet package in R. The goal is to create an interactive map displaying information about the population and the number of cities in each voivodship.

## Installation

Before running the project, make sure to install the required packages:
- geojsonio
- readxl
- leaflet
- stats

You can uncomment the `install.packages()` lines in the code to install these packages.

## Data

The project utilizes two datasets:
- "poland-with-regions_.geojson": GeoJSON file containing the polygons of Poland's voivodships.
- "population.xlsx" and "number_of_cities.xlsx": Excel files containing data on population and the number of cities in each voivodship.

## Usage

To run the project, follow these steps:

1. Download the project from GitHub.
2. Set the working directory by modifying the `main_dir_path` variable in the code to match the path to the main project folder on your system.
3. Open the project in RStudio and run chunks in order.

The code chunks can be executed by placing the cursor inside each chunk and pressing the "Run" button in RStudio or by using the keyboard shortcut (Ctrl + Shift + Enter). Make sure to install the required R packages (`geojsonio`, `readxl`, `leaflet`, `stats`) if they are not already installed.

The resulting interactive map displaying the voivodships of Poland will be generated and shown in the RStudio viewer.