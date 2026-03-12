# India Drug Price Analysis 2025 – NPPA DPCO Insights

**Exploratory analysis of 299 ceiling prices under Drugs (Prices Control) Order 2025**  
**Focus:** Price distribution, therapeutic category variation, manufacturer concentration, dosage form impact, and policy implications for essential medicines in India.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Data%20Source-NPPA%20Official-success" alt="Source: NPPA">
  <img src="https://img.shields.io/badge/Analysis%20Date-March%202026-orange" alt="March 2026">
</p>

## ✨ Key Highlights

- **Extreme price skew**: Top 10% of formulations represent >96% of total price value  
- **Only 11 drugs** (3.7%) priced > ₹1,000/unit — yet one (Trastuzumab) reaches **₹54,750/vial**  
- **60.5%** of NLEM drugs cost **< ₹10/unit** (median ₹6.25)  
- **Anti-cancer drugs** average **~3,000×** more expensive than dermatology products  
- **Injections** cost **114×** more on average than tablets  
- Strong success in cardiovascular, anti-TB, anti-HIV & respiratory affordability  
- Major affordability challenge remains in **biologics**, **liposomal formulations** & **immunoglobulins**

## 📊 Project Structure

```text
india-drug-price-analysis-2025/
├── data/
│   ├── raw/                    # Original NPPA files (if included)
│   └── processed/              # Cleaned dataset (drug_prices_2025.csv or similar)
├── notebooks/
│   └── 01_price_analysis.ipynb # Main analysis notebook
├── insights.md                 # Polished key findings (the document you provided)
├── charts/                     # Exported visuals (price distribution, category comparison, etc.)
├── requirements.txt
└── README.md
