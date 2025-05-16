# Restaurant Geographical Analysis Project  

## Overview  
This project analyzes the geographical distribution of restaurants and their characteristics across different cities. It uses geospatial visualization and statistical aggregation to explore restaurant density, average ratings, and price ranges by location.

## Key Features  

### Geospatial Visualization  
- Plots restaurant locations on a world map using latitude/longitude coordinates  
- Visualizes restaurant density and distribution patterns  

### City-Level Statistics  
- Calculates key metrics by city:  
  - Restaurant count (density)  
  - Average aggregate rating  
  - Average price range  
- Identifies top cities by restaurant concentration  

## Dataset  
The dataset contains:  
- Restaurant locations (Latitude/Longitude)  
- City information  
- Aggregate ratings  
- Price ranges  

## Requirements  
- Python 3.x  
- pandas  
- geopandas  
- matplotlib  
- shapely  

## Usage  
1. Clone the repository  
2. Install dependencies:  
   ```bash
   pip install pandas geopandas matplotlib shapely
   ```
3. Run the script to:  
   - Generate geographical distribution plot  
   - Display city-level statistics  

## Sample Output  
The analysis reveals:  
- New Delhi has the highest restaurant concentration (5,473 restaurants)  
- Ghaziabad has the highest average rating (2.85)  
- Gurgaon has the highest average price range (1.86)  

## Future Enhancements  
- Interactive map visualization (Folium/Plotly)  
- Regional clustering analysis  
- Correlation between location and restaurant success metrics  
- Integration with additional geographical data (population density, income levels)
