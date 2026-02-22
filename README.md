Project Overview
This project explores how upstream bioprocess parameters influence biologics production yield. The goal is to build a model for optimizing mixing time, temperature, pH, and dissolved oxygen (DO) to improve batch performance. Due to proprietary / confidential challenges of obtaining and using real data from the biotech industry, real manufacturing data cannot be used. As a result, a synthetic dataset will be generated to simulate representative upstream manufacturing conditions in fermentation and cell culture.

Research Question
Can we use a regression model to identify the optimal upstream (fermentation and cell culture stage) process parameters (mixing time, temperature, pH, and dissolved oxygen) that are most likely to increase the yield of a biologic drug product?

Expected Data Source
Due to the proprietary nature of the biologics manufacturing industry, real process data was not available for this project. Instead, a synthetic dataset will be generated to reflect realistic upstream conditions in fermentation and cell culture. The dataset will simulate batch-level production records, structured in a table format, where each row represents a batch. 

Data Structure
	• Input features: mixing time, temperature, pH, dissolved oxygen
	• Target variable: final batch yield

The synthetic data will be generated considering domain knowledge of biologics operations to ensure realistic parameter ranges and biologically plausible relationship.

Methods
This milestone includes the following components:
  • Synthetic data generation  
  • Data cleaning (missing values, duplicates, outliers)  
  • Exploratory Data Analysis (EDA)  
  • Feature engineering  
  • Baseline regression model (e.g., Linear Regression or Random Forest)  
  • Evaluation using metrics such as RMSE, MAE, and R²  

All analysis will be performed in the Jupyter notebook.

Techniques I Expect to Use
	• Exploratory Data Analysis (EDA): to assess parameter distributions, correlations, and identify potential outliers.
	• Linear Regression with LASSO regularization: to measure the relationship between process parameters and yield, and to eliminate non-contributing variables.
	• Random Forest Regression: to capture potential non-linear effects and parameter interactions.
	• Model evaluation: using train/test split and cross-validation with metrics such as RMSE and (R^2).
	• Visualization: including yield vs. parameter plots.

Expected Results
	• A model capable of predicting upstream process parameters that are most likely to increase yield.
	• Identification of the most influential process variables to increase yield.
	• Insight into optimal parameter ranges associated with higher yield.
	• Comparative performance analysis between linear and non-linear models.
	• Visual tools to support decision-making and process optimization.

Why This Question Is Important
In the biotech industry, upstream operations (fermentation and cell culture) are critical to determining final yield. These manufacturing stages involve complex biological systems where small deviations in process parameters can lead to significant yield variability. This question is important because currently, many decisions around mixing time, temperature, pH, and dissolved oxygen are mostly based on experience, conservative ranges, and limited experimentation.

This project intends to address how to use historical process inputs and outputs into actionable, data-driven guidance. By modeling the relationship between upstream parameters and yield, we can:
	• Reduce reliance on trial-and-error which can potentially lead to a faster time to market (from clinical to commercial) and to higher yield
	• Improve efficiency
	• Enable digitalization strategies
  • Support Pharma 4.0 initiatives, including digital twins and automated process control

Ultimately, answering this question supports a shift in the development process, which is from a reactive troubleshooting mindset to proactive / predictive process control enabling biologics manufacturers to deliver high-quality products more efficiently and reliably at a lower cost.

Results
This section will summarize:
• Relationship between key parameters and yield  
• Outlier and distribution insights  
• Feature engineering outcomes  
• Baseline model performance and interpretation
