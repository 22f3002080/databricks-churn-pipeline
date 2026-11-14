**Customer Churn Prediction Pipeline on Databricks**

*1. Overview*

Telecom companies lose revenue when customers leave. This project builds an end-to-end, rerunnable data and ML pipeline on Databricks Free Edition. It ingests raw customer data, cleans it through a bronze/silver/gold (medallion) architecture, trains and tracks churn models with MLflow, registers the best model in Unity Catalog, and scores every customer so a retention team can see who is most at risk.

*2. Problem statement*

Given a customer’s contract, services, billing and tenure, predict whether they will churn, then turn those predictions into a ranked list of customers to contact. The aim is not only model accuracy. It is a reliable, explainable pipeline tied to a business outcome.
