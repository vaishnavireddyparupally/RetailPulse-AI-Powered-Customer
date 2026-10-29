# RetailPulse — AI-Powered Customer Analytics & Demand Forecasting

A runnable Streamlit demo with six analytics pages, using synthetic demo data:
1. Executive Overview
2. Sales & Demand Forecast
3. Customer Segmentation (K-Means)
4. Churn Prediction (Random Forest)
5. Inventory Optimization
6. Data Explorer (CSV upload)
7. Model Monitoring & Data Quality

## Run locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Run in Google Colab
Open `RetailPulse_Colab.ipynb` in Google Colab and run the cells in order. The notebook installs dependencies, starts Streamlit, and opens a public temporary tunnel using LocalTunnel. If LocalTunnel asks for a tunnel password or is unavailable, run locally or use a trusted tunnel provider.

## Important
- The built-in data is synthetic, generated for demonstration. Results are not real business outcomes.
- Forecasting is a Random Forest baseline, not a Prophet + LSTM ensemble.
- Model monitoring is a demonstration checklist, not live MLflow/Evidently telemetry.
- No real reduction in stockouts, churn, or revenue is claimed.
- Do not upload personal or confidential customer data to a public demo tunnel.
