# 📈 MacroQuant: Global Liquidity & Asset Prediction Engine

**MacroQuant** is an advanced analytical framework designed to decode the complex relationships between **U.S. Public Debt dynamics**, **Global Liquidity cycles**, and the price action of major financial assets (**Bitcoin, Equities, and Bonds**).

Using a blend of **Econometrics** and **Machine Learning**, this project aims to quantify how the "Invisible Hand" of central bank liquidity dictates market regimes.

---

## 🔬 Core Research Pillars

### 1. The Liquidity Proxy (The "Global Tide")
* **Central Bank Balances:** Tracking the Fed, ECB, and BoJ to calculate global net liquidity.
* **TGA & Reverse Repo:** Analyzing the U.S. Treasury General Account and RRP facility to predict short-term market stress.

### 2. Debt Dynamics & Macro Regimes
* **Fiscal Dominance:** Modeling the impact of U.S. Public Debt expansion on long-term Treasury yields and inflation expectations.
* **Correlations:** Quantifying how Bitcoin and Gold act as "Liquidity Barometers" compared to traditional Equities.

### 3. Predictive Modeling (Time-Series)
* **Feature Engineering:** Extracting alpha from macro-indicators (CPI, PMI, Yield Curves).
* **Algorithms:** Utilizing LSTM (Long Short-Term Memory) networks and XGBoost for non-linear price prediction.

---

## 🛠️ Tech Stack & Methodology

| Field | Technologies |
| :--- | :--- |
| **Data Science** | Python, Pandas, NumPy, Scipy |
| **Machine Learning** | Scikit-learn, TensorFlow/PyTorch (LSTMs), XGBoost |
| **Data Sourcing** | FRED API, Yahoo Finance, Glassnode (On-chain) |
| **Visualization** | Plotly (Interactive Charts), Matplotlib, Seaborn |

---

## 📂 Project Architecture

* `data/` : Multi-source datasets (Macro, On-chain, and TradFi).
* `notebooks/` : **Exploratory Data Analysis (EDA)** and Correlation Heatmaps.
* `models/` : Serialized predictive models and backtesting results.
* `scripts/` : Modular pipelines for automated feature scaling and training.

---

## 🏗️ Development Roadmap

- [x] **Phase 1:** Multi-asset data ingestion pipeline (BTC, SPX, GOLD, DXY).
- [x] **Phase 2:** Correlation matrix analysis under different liquidity regimes.
- [ ] **Phase 3:** (In Progress) Integration of **U.S. Debt Cycle** & Net Liquidity indicators.
- [ ] **Phase 4:** Deployment of the Price Prediction Engine and Backtesting framework.

---
