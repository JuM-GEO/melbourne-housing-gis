# Melbourne Housing Market - GIS & Data Science
This project explores Melbourne's rental housing market using open data and geospatial analysis.
It combines Python-based data science with GIS techniques to understand spatial patterns, affordability and accessibility.

## Objectives
- Explore rental prices across Melbourne regions (1999 - 2025)
- Identify spatial patterns and hotspots
- Analyse the relationship between price, location and accessibility
- Build simple predictive models (future stage)

## Current Progress
### ✅ Phase 1: Data Cleaning & Initial EDA
- **Data Source**: Victorian Government Quarterly Median Rents (1999-2025)
- **Focus**: 1-bedroom flats across Melbourne regions
- **Key Steps**:
  - Cleaned and restructured raw Excel data
  - Separated Count and Median rent data
  - Handled missing values and data quality issues
  
### 📝 Initial Findings
- **Overall Trend**: Steady increase in median rents from 1999 to 2025
- **COVID-19 Impact**: Significant drop in Melbourne CBD rents during lockdowns (2020-2021)
  - Pre-COVID (Dec 2019): $438
  - Lowest point (Jun 2021): $310
  - Current (Jun 2025): $550
  - Recovery of 77.4% post-lockdown
- **Regional Variations**: to be explored further
  
## Tools & Technologies
- Python
- Pandas
- GeoPandas
- Folium
- Matplotlib / Seaborn
- Scikit-learn

## Data Sources
- Victorian Government Open Data - https://discover.data.vic.gov.au/dataset/rental-report-quarterly-quarterly-median-rents-by-lga
- Australian Bureau of Statistics

## Project Structure
```
melbourne-housing-gis/
├── data/
│   ├── raw/                    # Original data files
│   └── processed/              # Cleaned CSV files
├── notebooks/
│   └── 1_EDA_MHP_Project.ipynb # Data cleaning and initial analysis
├── images/                     # Exported figures and maps
├── requirements.txt            # Python dependencies
└── README.md
```

## How to Reproduce
1. Clone this repository
2. Create virtual environment: `python -m venv venv`
3. Activate: `.\venv\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Run the notebook: `notebooks/1_EDA_MHP_Project.ipynb`

## Next Steps
- [ ] Add geospatial visualization with maps
- [ ] Expand analysis to 2-bedroom flats
- [ ] Compare Melbourne suburbs vs regional Victoria vs other australian regions
- [ ] Time series forecasting
- [ ] Integrate transport/amenity accessibility data

## Status
**🚧 Active Development** - Phase 1 Complete
