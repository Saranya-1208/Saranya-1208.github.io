# Data Visualization Portfolio | Saranya Anand

**LSE MPA 2027 | PP434 Data Visualization**

Live site: [https://saranya-1208.github.io/](https://saranya-1208.github.io/)

## 📊 Overview

This repository contains my data visualization portfolio for PP434 (LSE Autumn 2025), featuring 10 coding challenges and a comprehensive project on India's digital transformation.

**Portfolio Structure:**
- `index.html` - Landing page with introduction
- `portfolio.html` - 10 coding challenges (CC1-CC10)
- `project/` - Digital India: Main visualization project

## 🎯 Portfolio Challenges (CC1-CC10)

### CC1: Hosting
- GitHub Pages setup
- Two embedded Vega-Lite charts

### CC2: Building
- Custom visualizations using Economics Observatory tools
- UK economic indicators

### CC3: Debate
- Policy-focused visualization on women's parliamentary representation in India
- 25-word thesis + commentary

### CC4: Replication
- Replicated Financial Times IPO visualization
- Improved version with interactive legend

### CC5: Accessing Data
- **API:** World Bank GDP data for India
- **Web Scraper:** Wikipedia population data extraction
- Linked Google Colab notebooks

### CC6: Loops
- Batch downloaded 6 countries' internet data via World Bank API
- JavaScript loop for chart embedding
- Dashboard layout (3×2 grid)

### CC7: Maps
- Scotland: Coordinate-based Universal Credit map
- Wales: Population choropleth

### CC8: Big Data
- UK Long Run Prices Database (48M+ observations)
- Two charts analyzing bread prices (1988-2025)
- Regional price variations

### CC9: Interactive Charts
- UK Unemployment with brush selection zoom
- Women in Parliament with dropdown country selector

### CC10: Advanced Analytics & ML
- **Part 1:** UPI transaction timing heatmap (250K transactions)
- **Part 2:** Machine learning forecast using exponential regression

---

## 🇮🇳 Digital India Project

**Research Question:**  
Has India's digital expansion led to equitable access across geographic and socioeconomic dimensions?

### Key Findings

1. **The 7× Divide**: Maharashtra processes 7 times more UPI transactions per capita than Bihar
2. **Foundation Failures**: Even Aadhaar enrollment reflects existing geographic inequality
3. **Intervention Works**: 700-village pilot shows targeted investment closes digital gaps

### Visualizations (9 charts)

1. **Global Internet Comparison** - Interactive line chart showing India's growth vs. 7 countries
2. **McKinsey Digital Adoption** - Lollipop chart from scraped PDF data
3. **UPI Explosion Timeline** - 116 months of transaction data with annotations
4. **Transaction Timing Heatmap** - 250K transactions by hour/day pattern analysis
5. **UPI Per Capita Map** - Interactive choropleth with dropdown metrics
6. **Digital Villages** - Dot plot showing intervention impact across 700 villages
7. **Aadhaar Diverging Bar Chart** - State-level enrollment vs. national average
8. **5G Infrastructure Map** - Choropleth of village coverage by state
9. **ML Forecast** - Exponential regression predicting 2026 UPI volumes

### Technical Implementation

**Data Sources:**
- World Bank API (internet penetration)
- NPCI monthly reports (UPI transactions - manually reconstructed)
- India Open Data Portal API (5G infrastructure)
- McKinsey PDF (web scraping)
- Aadhaar enrollment records (236K+ records)
- 250K transaction sample (behavioral analysis)

**Tools:**
- **Visualization:** Vega-Lite v5
- **Data Processing:** Python (pandas, scikit-learn)
- **Environment:** Google Colab
- **Hosting:** GitHub Pages

**Key Challenges:**
- State name matching across inconsistent datasets
- Date parsing across multiple format conventions
- Coordinate mapping for 5,000 pincodes
- Log-scale transformation for exponential growth visualization

---

## 📂 Repository Structure
```
saranya-1208.github.io/
├── index.html              # Landing page
├── portfolio.html          # CC1-CC10 challenges
├── project/
│   ├── index.html         # Digital India project
│   └── data/              # CSV files for visualizations
├── saranya-photo.jpg      # Profile photo
└── README.md              # This file
```

## 🔗 Google Colab Notebooks

All data processing workflows are documented in public Colab notebooks:

1. [McKinsey PDF Scraper](https://colab.research.google.com/drive/1gATdy9GXodFZ3frY4EcZPblWWhY8wjjd?usp=sharing)
2. [5G API Data Collection](https://colab.research.google.com/drive/1QtUWVis71ktzU9Q0QunUYPdOelLgGbOm?usp=sharing)
3. [UPI Timeline Analysis](https://colab.research.google.com/drive/1Xq7Skj4NDEpDbI4DQfJdTikyRcti-Rmo?usp=sharing)
4. [Transaction Heatmap](https://colab.research.google.com/drive/1Q44vOtYM3mhGSNu7MAh7m4ABtdJ38EKI?usp=sharing)
5. [Aadhaar Pincode Processing](https://colab.research.google.com/drive/1NGX3234tj8Io1uvPtOEYybf3NSRTeCBl?usp=sharing)
6. [CC6 Dashboard Loop](https://colab.research.google.com/drive/13PjXGgk2bv2u-ziZh_pZjWhRcfhLv0g9?usp=sharing)
7. [CC8 Big Data Processing](https://colab.research.google.com/drive/1lWK4IRn_GYHQYDwXK-BEmUkKD7yqTf8j?usp=sharing)

## 🎨 Design Choices

**Color Palette:**
- Primary: Coral Pink (#FF6B9D), Teal (#4ECDC4), Lavender (#C7B8EA)
- Accent: Soft pastels for data visualization
- Typography: Garamond (elegant serif for readability)

**Aesthetic:**
- Soft gradients throughout
- Frosted glass effects for depth
- Consistent 1.3rem body text
- Interactive hover states
- Mobile-responsive design

## AI Usage Statement

This project was developed with assistance from Claude (Anthropic) for:
- Code syntax and debugging
- Vega-Lite specification structure
- Visual design iteration
- Technical problem-solving

**All analytical decisions** (research questions, data selection, interpretation, policy conclusions) were made independently. I collected all data, executed all code, verified all results, and made all substantive project decisions.

## Contact

**Saranya Anand**  
LSE MPA 2027  
[GitHub](https://github.com/Saranya-1208)

## 📄 License

This project is part of academic coursework at the London School of Economics.

*Last updated: January 2026*
