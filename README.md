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
- **Source**:  
- **File**: `melb_data.csv` 
- **Key Features**: Suburb, Rooms, Type (house/unit/townhouse), Price, Distance from CBD, Bathroom, Car spots, Landsize, BuildingArea, YearBuilt, Regionname.

### Current Explorations
-  Data shape, types, missing values summary, basic descriptives.  
- Histograms, boxplots ,Heat maps,displots,displots by type ...    
- Heatmap of numerical variables  
   Identifying extreme land sizes and old buildings.

### Early Insights (Raw Data)
- Medians  
- Mean 
- Most common: 3-bedroom houses 
- Strong correlations: Rooms and price, distance negatively impacts value  
- Data issues: 

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
