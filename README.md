# ECO-hackathon
# Aravalli Intelligence: Unsupervised Detection of Land-Use Drift

**Team Name:** GeoGuardians  
**Round:** 2 - Prototype Development & Full Solution Submission  
**Focus:** Ecological Monitoring of the Aravalli Hills  

## 🌿 Project Overview
"Aravalli Intelligence" is a specialized monitoring system designed to detect "land-use drift"—subtle, unmonitored environmental degradation such as illegal mining and urban encroachment. Since labeled ground truth for illegal activities is scarce, our solution leverages **Unsupervised and Weakly Supervised Machine Learning** to identify anomalies in spectral and temporal satellite data.

### Key Features:
* **Anomaly Detection:** Identifies spectral shifts that indicate land clearing or mining.
* **Missing Data Masking:** Handles satellite artifacts and cloud cover using binary masking.
* **Severity Classification:** Uses an XGBoost-driven logic to categorize the intensity of land-use change.
* **Actionable Intelligence:** Generates automated reports with coordinates for proactive enforcement.

---

## 📂 Repository Structure
* `/models`: Contains `xgboost_model.pkl` and `scaler.pkl` for inference.
* `/notebooks`: 
    * `train.ipynb`: Model training and evaluation logic.
    * `compare.ipynb`: Image comparison and drift detection pipeline.
* `/data`: Sample satellite imagery (`path1.jpg`, `path2.jpg`) used for the prototype demonstration.
* `requirements.txt`: List of all Python dependencies.

---

## 🚀 Setup & Installation

1. **Clone the repository:**
   git clone [https://github.com/Piyush9940/ECO-hackathon]
   cd [ECO_HACKATHON]
Create a virtual environment (Recommended):


python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies:


pip install -r requirements.txt
