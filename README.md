# Walmart_Sales_Forecasting
🛒 Walmart Sales Forecasting – Time Series Analysis (SARIMA, Prophet, Ensemble)
Project Overview

This project focuses on forecasting Walmart’s weekly sales using advanced time-series forecasting models – SARIMA, Facebook Prophet, and an Ensemble model combining their strengths.
The goal was to predict future sales trends, compare model performance, and visualize results through Power BI dashboards.

🧠 Objectives

Perform time-series forecasting using SARIMA and Prophet models.

Compare model accuracy using RMSE and MAPE metrics.

Visualize forecast outcomes and trends using Power BI.

Provide actionable insights for sales and inventory planning.

🧰 Tools & Technologies
Category	Tools Used
Programming	Python (Jupyter Notebook / .ipynb)
Libraries	Pandas, NumPy, Matplotlib, Statsmodels, Prophet
Visualization	Power BI
Dataset Source	Kaggle – Walmart Weekly Sales Dataset
⚙️ Steps & Methodology

Data Preprocessing

Cleaned and transformed the raw dataset.

Aggregated sales by weekly intervals.

Handled missing and inconsistent values.

Modeling

Implemented SARIMA (Seasonal ARIMA) model.

Built Prophet model for additive trend-seasonality forecasting.

Created an Ensemble Model combining both forecasts.

Evaluation

Compared performance using:

RMSE (Root Mean Square Error)

MAPE (Mean Absolute Percentage Error)

Final results:

SARIMA → RMSE: 29.53M | MAPE: 4.65e+27%
Prophet → RMSE: 21.80M | MAPE: 4.87e+27%


Visualization (Power BI)

Built an interactive dashboard showing:

Model performance comparison (SARIMA, Prophet, Ensemble)

Sales trends over time

Forecast error summaries

📊 Power BI Dashboard Preview

Key Visuals:

Line chart: SARIMA vs Prophet vs Ensemble forecast comparison

Bar charts: Model-specific sales predictions

KPI cards: RMSE, MAPE, Best Model

Clean layout with unified color coding and metrics at the top

🏁 Results & Insights

Prophet model achieved the lowest RMSE, making it the most accurate among the three.

Ensemble modeling provided stable and smoother predictions.

Power BI visualizations enabled better business insights for decision-making.

🗂️ Repository Structure
📁 Walmart-Sales-Forecasting/
├── walmart_sales_forecasting.ipynb     # Jupyter Notebook (JSON format okay)
├── weekly_forecast_output.csv          # Model outputs
├── PowerBI_Dashboard.pbix              # Power BI file
├── README.md                           # Project documentation
└── /images                             # Dashboard screenshots (optional)

📈 Future Enhancements

Add XGBoost / LSTM models for improved accuracy

Automate data pipeline using Power BI Service

Deploy forecast insights to a dashboard app

🧑‍💻 Author

Gourab Kumar Dash
Data Analyst | BI & Forecasting Enthusiast
📧 gourabdash@gmail.com

📍 Gurugram, India

✅ License

This project is for educational and portfolio purposes. Feel free to fork and build upon it with proper credit.

🔸 Regarding .ipynb in JSON Format

Yes — that’s completely okay.
Jupyter Notebooks are JSON-formatted by default, so uploading the file as .ipynb (even if it looks like JSON when opened in a text editor) is perfectly fine.
Once uploaded to GitHub or Kaggle, it will automatically render as an interactive notebook.
