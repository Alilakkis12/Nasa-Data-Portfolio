# Nasa-Data-Portfolio

# NASA Meteorite Landings Analysis
## Official NASA Open Data Project

### 1. Introduction
This project analyzes official meteorite landing data provided by NASA. 

### 2. Main Objective:
The goal is to explore patterns in when, where, and what types of meteorites have been found on Earth.

### 3. Tasks To Do:

1. clean and prepare the raw NASA data by handling missing values in mass, year, latitude, and longitude.
   
3. Answer the 3 key questions:
   
   A. When were most meteorites discovered? (Timeline Analysis)
   
   B. What are the heaviest types of meteorites? (Mass by Class Analysis)
   
   C. Where do meteorites land most? (Geospatial Analysis)

### 4. Data Source (100% Official NASA)
- **Official Website:** https://data.nasa.gov/dataset/meteorite-landings
- **Dataset Name:** Meteorite Landings
- **How to download from official site:**
    1. Go to https://data.nasa.gov/dataset/meteorite-landings
    2. Scroll to "Resources" section - you will see 4 unnamed resources: CSV, RDF, JSON, XML
    3. Next to CSV, click **Explore** -> **Go to resource**
    4. The official CSV file downloads automatically
- **Provider:** Data from The Meteoritical Society, hosted and curated by NASA on data.nasa.gov
- **Columns in dataset:**
    - name, id, nametype, recclass, mass (g), fall, year, reclat, reclong, GeoLocation

### 5. Tools Used
- Jupyter Notebook (local PC)
- Python Libraries: pandas, matplotlib

### 6. Steps Performed
1. Downloaded official CSV from data.nasa.gov (via CSV -> Explore -> Go to resource)
2. Loaded dataset in Jupyter Notebook using pandas
3. Cleaned data: Removed rows with missing latitude, longitude, mass, and year
4. Converted year column to datetime format
5. Performed exploratory analysis and created visualizations

### 7. Analysis & Visualizations

#### Chart 1: Meteorite Discoveries Over Time

Shows how many meteorites were discovered each year.

![No of Meteorites Discovered Over Time](Bar_Chart_Quantity_Discovered_by_Time.png)


#### Chart 2: Heaviest Meteorite Classes

Average mass by meteorite type.

![Heaviest TYpes of Meteorites](Bar_Chart_Heaviest_Types.png)


#### Chart 3: Global Map of Landings
Map Chart showing where meteorites landed globally.

![Meteorite WorldMap](World_Map_Meteorites_Density.png)


### 8. Key Findings
- Most meteorites found in Antarctica / deserts
- Heaviest type are the ones associated with Iron ===> Iron typed.

### 9. Repository Files
- `Meteorite_Landings.csv` - Official NASA dataset
- `Meteorite_analysis.ipynb` - Full Jupyter Notebook analysis
- `Chart1_Quantity_Discovered_by_Time.png` - Timeline chart
- `Chart2_Heaviest_Types.png` - Heaviest types chart
- `Chart3_Meteorites_Density.png` - World map chart
- `README.md` - This file

### 8. Conclusion
This project demonstrates working with official NASA open data from data.nasa.gov, from download to analysis and visualization, using only the official NASA source without external mirrors.

### Data Credit
Data Source: NASA Open Data Portal - data.nasa.gov
