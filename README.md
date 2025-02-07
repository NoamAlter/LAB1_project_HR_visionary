# LAB1_project_HR_visionary

Welcome to The HR Visionary README.

Introduction
In a competitive job market, HR teams and recruiters need data-driven insights to track industry
trends, benchmark salaries, standardize job roles, and anticipate workforce demands. Our
project tackles these challenges by integrating multi-source data-including LinkedIn, and web-
scraped job listings from Indeed. Leveraging advanced machine learning and NLP techniques,
such as Prophet for time-series forecasting and XGBoost for predictive modeling, we provide
actionable insights that help organizations optimize recruitment strategies and make informed,
evidence-based HR decisions.

privet link to the scrapet data: https://drive.google.com/file/d/1Cp2yRhNgrSb-yc2toZ0lP9YuDf0TaMr_/view?usp=drive_link


The main files you should run are: 

Scraping_data_EDA&XG_BOOST.ipynb
Before running the notebook follow the next steps: 
1. For predicting Future Demand (raw views) for job title go to cell 34 and insert under the comment "5. Predict on a New Job Title (without time considerations)" the job title and normalized salery.
2. For salary prediction go to cell 35 and insert your job title.
3. Run all the cells by clicking Run button on the tool bar, then 'Run and debug' then 'Run all'.



Meta_Industry_Eda&Prophet
Before running the notebook follow the next steps:
1. In order to forecast growing industries go to cell 37 and under the comment "Forecasting for top growing industries" insert the top industries of your choosing.
2. For prophet-based job market forecasting go to cell 46, choose the number of top jobs to see prediction and forecast period and insert them in num_top_jobs, and forecast_period_months respectively.
3. in order to choose specific job to predict go to cell 49, choose the job title you want prediction of and number of months to predict and insert them in chosen_title and forecast_period_months respectively.
4. Run all the cells by clicking Run button on the tool bar, then 'Run and debug' then 'Run all'.
