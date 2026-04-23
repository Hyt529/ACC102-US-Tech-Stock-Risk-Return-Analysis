# US Tech Stock Risk-Return Analysis (2020-2024)
## ACC102 Mini Assignment - Track 2 GitHub Project
### Xi'an Jiaotong-Liverpool University | ACC102 AI-Driven Data Analytics

---

## 1. Analytical Problem & Target Audience
### Core Problem
This project evaluates the risk-return profile of 6 leading US large-cap tech stocks (MSFT, AAPL, AMZN, GOOGL, META, TSLA) over the 2020-2024 period, comparing their performance against the CRSP broad US market benchmark. The goal is to identify optimal risk-adjusted investment opportunities for retail investors and entry-level portfolio managers building a tech-focused equity portfolio.

### Target Audience
- Retail investors looking to allocate capital to the US tech sector
- Entry-level financial analysts and portfolio managers
- Students learning equity investment and financial risk analysis

---

## 2. Data Source
All data is retrieved from **Wharton Research Data Services (WRDS) CRSP (Center for Research in Security Prices) Database**, the authoritative source for US equity market research.
- Data Access Date: 23 April 2026
- Core Tables Used:
  - `crsp.msf`: Monthly Stock File (end-of-month closing prices and dividend-adjusted total returns)
  - `crsp.msfhdr`: Stock Header File (official mapping between ticker symbols and CRSP PERMNO identifiers)
  - `crsp.msi`: Monthly Market Index File (CRSP value-weighted market return, the broad US market benchmark)

---

## 3. Project Structure
```markdown
├── README.md                          # Project overview and user guide
├── ACC102_Tech_Stock_Analysis.ipynb  # Full end-to-end analytical workflow
├── .gitignore                         # File ignore rules for GitHub
├── data/
│   ├── raw_data_source_note.txt       # WRDS data retrieval guidance
│   └── processed/                      # Cleaned and normalized dataset for analysis
├── results/                            # Calculated performance metrics and analysis results
└── visuals/                            # Academic-standard analysis visualizations

