# InternSpark Machine Learning Internship Portfolio

###  Candidate Information
* **Name:** Dashkrat Srivastava
* **Candidate ID:** IS-2026-9899
* **Domain:** Machine Learning Intern
* **Academic Background:** B.Tech – VIT Bhopal University (2028 Cohort)
* **Internship Cohort:** June 2026 (AICTE-Listed Program)

---

###  Repository Structure
This repository serves as the official project tracking portfolio for my engineering milestones during the InternSpark remote machine learning residency. The workspace is organized into modular task directories containing production notebooks, serialized weights, and performance briefs.

---

##  Task 1: Iris Flower Species Classification
* **Directory:** `/Task1_Iris_Classification`
* **Core Objective:** Implemented an end-to-end Supervised Classification Pipeline to classify Iris species based on morphometric features.
* **Pipeline Infrastructure:** Built a baseline Logistic Regression model using `scikit-learn`. Implemented `StandardScaler` feature normalization to neutralize feature dominance.
* **Key Results:** Achieved an overall classification accuracy of **96.67%**. Serialized operational model states into portable `iris_logistic_regression_model.pkl` formats using `joblib`.

---

##  Task 2: California House Price Prediction
* **Directory:** `/Task2_House_Price_Prediction`
* **Core Objective:** Engineered a Supervised Continuous Regression workflow to predict median real estate property valuations using regional demographic and socioeconomic features.
* **Pipeline Infrastructure:** Benchmarked an Ordinary Least Squares (OLS) Linear Regression baseline against a robust, non-linear Random Forest Regressor ensemble (`max_depth=15`).
* **Key Results:** The Random Forest ensemble successfully captured spatial geographic coordinates and wealth density profiles, drastically outperforming the linear baseline by maximizing the variance explanation ratio ($R^2$). Exported compressed, deployment-ready production artifacts as `house_price_random_forest_model.pkl`.

---

*Maintained by [DashkratSrivastava](https://github.com/DashkratSrivastava).*
