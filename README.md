# Melbourne Housing Prices  
Exploratory Data Analysis (2016–2018)

<div align="center">
  <img src="https://images.unsplash.com/photo-1621905252507-b35492cc74b4?ixlib=rb-4.0.3&auto=format&fit=crop&q=80&w=2160" alt="Melbourne real estate" width="100%"/>
  <br><br>
  <h3>Raw, honest, and very much in progress</h3>
</div>

<br>

**⚠️ DATA CLEANING NOT DONE YET**  
Missing values everywhere. Landsize has 9-million-m² mansions. BuildingArea has 777-year-old houses. You’ve been warned.

### What’s inside right now
- `melb_data.csv` – the original Kaggle snapshot (34,857 rows)
- `01_first_look.ipynb` – shape, dtypes, % missing, insane outliers
- `02_price_analysis.ipynb` – distribution before/after log, top 20 suburbs, price growth by year
- `03_distance_vs_price.ipynb` – the classic “further from CBD = cheaper” scatter (with outliers that break physics)
- `04_rooms_bath_car.ipynb` – how many rooms, baths, and car spots actually move the needle
- `05_suburb_deep_dive.ipynb` – boxplots of the most expensive vs cheapest postcodes

### Early observations (pre-cleaning)
- Median sale price: $1,033,000 AUD
- 75th percentile distance from CBD: 13.6 km
- 14% of rows missing `BuildingArea`, 22% missing `YearBuilt`
- Some properties have 10+ bedrooms and sell for <$300k (data entry errors confirmed)
- House > Unit > Townhouse in median price, as expected

### Next on the list
- Proper outlier treatment
- Impute/fix/drop the big missing columns
- Price per square metre
- Interactive map with Folium/Plotly
- Eventually: simple prediction baseline

Contributions, suggestions, and “dude you missed this” issues are more than welcome.

December 2025 | MIT License
