# Melbourne Housing Prices – Exploratory Data Analysis 🏠

<div align="center">
  <img src="https://images.unsplash.com/photo-1524814684765-6b7b75e758f7?ixlib=rb-4.0.3&auto=format&fit=crop&q=80&w=2160" alt="Aerial view of Melbourne suburbs" width="100%"/>
  <br><br>
  <h3>Diving into Melbourne's real estate market (2016–2017)</h3>
</div>

<br>

**⚠️ DATA CLEANING NOT DONE YET**  
Raw data with missing values, outliers, and unpolished visuals. Progressing step by step—stay tuned for refinements.

### Dataset
- **Source**: [Kaggle – Melbourne Housing Snapshot](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot)  
- **File**: `melb_data.csv` (13,580 rows, 21 columns)  
- **Key Features**: Suburb, Rooms, Type (house/unit/townhouse), Price, Distance from CBD, Bathroom, Car spots, Landsize, BuildingArea, YearBuilt, Regionname.

### Current Explorations
- `01_initial_overview.ipynb`: Data shape, types, missing values summary, basic descriptives.  
- `02_price_distributions.ipynb`: Histograms, boxplots by type, log-transformed prices.  
- `03_location_analysis.ipynb`: Price vs. distance from CBD, suburb medians, scatter plots with latitude/longitude.  
- `04_feature_correlations.ipynb`: Heatmap of numeric features, rooms/bathrooms vs. price.  
- `05_outlier_detection.ipynb`: Identifying extreme land sizes and old buildings.

### Early Insights (Raw Data)
- Median sale price: ~$903,000 AUD  
- Mean sale price: ~$1,075,000 AUD  
- Most common: 3-bedroom houses, ~10km from CBD  
- Strong correlations: Rooms and price, distance negatively impacts value  
- Data issues: ~47% missing BuildingArea, outliers like 9,000+ m² landsizes  

### Tools & Libraries
- Python 3.8+  
- Pandas, NumPy for data handling  
- Matplotlib, Seaborn, Plotly for visualizations  

### Roadmap
- [ ] Data cleaning: Handle missing values, remove/fix outliers  
- [ ] Feature engineering: Price per m², property age, seasonal trends  
- [ ] Advanced viz: Interactive maps with Folium  
- [ ] Modeling: Baseline regression for price prediction  

Open to suggestions, corrections, and collaborations—drop an issue or PR!

Last updated: December 07, 2025 | MIT License
