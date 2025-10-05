Walmart Sales Forecasting – Time Series Analysis (SARIMA, Prophet, Ensemble)
📌 Project Overview

This project focuses on forecasting Walmart’s weekly sales using advanced time-series models — SARIMA, Facebook Prophet, and a combined Ensemble model.
The aim is to predict future sales trends, evaluate model performance, and visualize results using Power BI dashboards for strategic decision-making.

🧠 Objectives

Forecast future Walmart weekly sales.

Compare model accuracy using RMSE and MAPE.

Build an interactive Power BI dashboard to visualize forecast trends.

Generate actionable insights for business and inventory planning.

🧰 Tools & Technologies
Category	Tools Used
Programming	Python (Jupyter Notebook / .ipynb)
Libraries	Pandas, NumPy, Matplotlib, Statsmodels, Prophet
Visualization	Power BI
Data Source	Kaggle – Walmart Weekly Sales Dataset
⚙️ Steps & Methodology

Data Preparation

Cleaned and preprocessed the Walmart dataset.

Aggregated weekly sales and handled missing values.

Created new features and date-based groupings for time series modeling.

Modeling & Forecasting

Applied SARIMA (Seasonal ARIMA) for seasonal sales prediction.

Used Facebook Prophet for trend-seasonality modeling.

Built an Ensemble Model averaging both forecasts for better stability.

Evaluation Metrics

RMSE (Root Mean Square Error) and MAPE (Mean Absolute Percentage Error) were used.

Final results obtained:

SARIMA → RMSE: 29,530,191.97 | MAPE: 4.65e+27%
Prophet → RMSE: 21,803,724.05 | MAPE: 4.87e+27%


Visualization (Power BI)

Created an interactive dashboard comparing SARIMA, Prophet, and Ensemble results.

Key visuals include:

Line chart comparing forecast outputs.

Individual bar charts for each model.

Metrics summary section showing RMSE & MAPE values.

📊 Power BI Dashboard Overview

Dashboard Components:

📈 Sales Forecast Comparison Chart (SARIMA vs Prophet vs Ensemble)

📊 Model-wise Forecast Trends

🧮 Top summary section displaying RMSE & MAPE metrics

🎨 Custom color scheme for a professional visual layout

The dashboard provides a clear comparison of model forecasts and helps in identifying the best-performing model for future predictions.

🗂️ Repository Structure
📁 Walmart-Sales-Forecasting/
├── walmart_sales_data.csv              # Original dataset (input)
├── weekly_forecast_output.csv          # Forecasted output file
├── walmart_sales_forecasting.ipynb     # Jupyter Notebook (JSON format okay)
├── PowerBI_Dashboard.pbix              # Power BI file
├── Dashboard_Screenshot.png            # Final dashboard snapshot
└── README.md                           # Project documentation

🏁 Results & Insights

The Prophet model achieved the lowest RMSE, making it the most reliable among the models tested.

The Ensemble model produced smoother, more consistent predictions over time.

The Power BI dashboard adds powerful business interpretability to technical results.

📈 Future Improvements

Introduce XGBoost or LSTM models for deeper learning-based forecasting.

Automate data ingestion and refresh via Power BI Service.

Include external variables (holidays, promotions, etc.) for improved accuracy.

🧑‍💻 Author

Gourab Kumar Dash
Data Analyst | BI & Forecasting Enthusiast
📧 gourabdatanalyst@gmail.com

📍 Gurugram, India

✅ License

This project is for educational and portfolio purposes.
Feel free to fork, improve, and reference it with proper credit.

💡 Note

The .ipynb file appears in JSON format — that’s completely normal.
When uploaded to GitHub or Kaggle, it will automatically render as a readable Jupyter Notebook.
