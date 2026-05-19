# Bayesian Walmart Sales Forecasting 📊
> Hierarchical Bayesian time-series forecasting with uncertainty estimation

This project demonstrates advanced applied Bayesian modelling to predict department-level sales, using PyMC and ArviZ. Unlike traditional forecasting, this method naturally quantifies uncertainty, making it ideal for business planning and inventory management.

---

## ✨ Key Features
✅ **Hierarchical Model**: Shares information across departments for better predictions
✅ **Uncertainty Intervals**: 90% confidence bounds on every forecast
✅ **Covariate Modelling**: Explicitly accounts for holiday effects
✅ **Full Visualisation Suite**: Model diagnostics, fit analysis, and forecast plots
✅ **Reproducible Workflow**: Clean modular code structure

---

## 🛠️ Tech Stack
- Python | PyMC (Probabilistic Programming)
- Pandas | NumPy | Matplotlib | Seaborn
- ArviZ (Bayesian analysis & plotting)

---

## 🚀 Quick Start
```bash
# Clone repo
git clone https://github.com/your-username/bayesian-walmart-sales-forecast.git
cd bayesian-walmart-sales-forecast

# Install dependencies
pip install -r requirements.txt

# Run analysis
jupyter notebook notebooks/analysis.ipynb
