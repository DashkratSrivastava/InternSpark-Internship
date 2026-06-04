# InternSpark Machine Learning Internship Portfolio

Candidate Information
Name: Dashkrat Srivastava
Candidate ID: IS-2026-9899
Domain: Machine Learning Intern
Academic Background: B.Tech – VIT Bhopal University (2028 Cohort)
Internship Cohort: June 2026 (AICTE-Listed Program)

---

Repository Structure
This repository serves as the official project tracking portfolio for my engineering milestones during the InternSpark remote machine learning residency. The workspace is organized into modular task directories containing notebooks, serialized model weights, and performance documentation.

Task 1: Iris Flower Species Classification
Directory Workspace: `/Task1_Iris_Classification`
Core Components:
   `InternSpark_Task1_Iris.ipynb`: Exploratory data analysis notebook implementing statistical multi-variable visualization and baseline structural model fitting.
   `iris_logistic_regression.pkl`: Frozen production-ready serialized model weights containing the learned classification boundaries.
   `Task1_Iris_Report.pdf`: One-page formal executive engineering brief summarizing project goals, data observations, and model evaluation metrics.

---

## 🛠️ System Environment & Core Dependencies
To reliably reproduce the computations, training boundaries, and visual graph layouts without version conflicts, ensure your execution container utilizes the following framework specifications:

* **Runtime Language:** Python `3.10+`
* **Machine Learning Library:** scikit-learn `1.6.1`
* **Data Manipulation Suite:** pandas `2.1.1` | numpy `1.26.0`
* **Data Visualization Engines:** matplotlib `3.8.0` | seaborn `0.13.0`
* **Object Serialization Interface:** joblib `1.3.2`

---

Reproduction & Execution Instructions

### Option A: Cloud Execution via Google Colab (Recommended)
1. Navigate directly into the targeted task directory (e.g., `Task1_Iris_Classification/`).
2. Click on the `.ipynb` notebook file to open the code viewer interface.
3. Click the Open in Colab badge located at the top of the file layout.
4. Once inside the active Google cloud container, select Runtime from the browser navigation window, then click Run all (`Ctrl + F9`) to sequentially execute data engineering steps, chart rendering, and model serialization blocks.

Option B: Local Environment Execution (Jupyter / VS Code Workspace)
1. Open your machine's system terminal or terminal wrapper and clone this public workspace:
   ```bash
  git clone https://github.com/DashkratSrivastava/InternSpark-Internship.git
