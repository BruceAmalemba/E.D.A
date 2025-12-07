# Melbourne Housing Prices – Exploratory Data Analysis 🏘️

<div align="center">
  <img src="https://images.unsplash.com/photo-1560448204-e02f11c3d0e2?ixlib=rb-4.0.3&auto=format&fit=crop&q=80&w=2000" alt="Melbourne skyline" />
  <br><br>
  <strong>Understanding what drives property prices in Melbourne</strong>
</div>

<br>

**⚠️ Work in Progress – Data Cleaning Not Done Yet**  
This repo is raw, real, and evolving. Expect missing-value chaos, duplicate rows, and quick exploratory plots. Things will get polished soon.

### Dataset
- **Source**: [Kaggle – Melbourne Housing Snapshot](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot)  
- **File**: `melb_data.csv` (~34,857 rows, 21 columns)  
- **Time period**: 2016 – 2018

### Current Notebooks
| Notebook | Description |
|----------|-------------|
| `01_raw_exploration.ipynb` | First look – shape, dtypes, missing values, basic stats |
| `02_price_distribution.ipynb` | Price histograms, log transformations, suburb comparisons |
| `03_geospatial.ipynb` | Price vs distance from CBD, scatter maps, top suburbs |
| `04_correlations_features.ipynb` | Heatmaps, Rooms vs Price, Land size outliers |

### Quick Insights So Far
- Median house price: ~ $1.03M AUD
- Strongest price drivers: Rooms, Distance from CBD, Property Type, Landsize
- Southern & Eastern suburbs dominate high-end sales
- Massive outliers in `Landsize` and `BuildingArea` (still investigating)

### Tools
- Python 3.9+
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- JupyterLab / VS Code

### How to Run
```bash
git clone https://github.com/yourusername/melbourne-housing-eda.git
cd melbourne-housing-eda
pip install -r requirements.txt
jupyter lab
