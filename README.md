# SOC Alert Prioritization: A Machine Learning Framework for Security Operations

## 🛡️ Project Overview
This project addresses the critical challenge of "alert fatigue" in Security Operations Centers (SOCs). By leveraging a dataset of **1.1 million security events**, I developed a machine learning framework to automate the prioritization of alerts, allowing analysts to focus on high-risk threats first.

**Key Achievement:** Successfully implemented a model that triages alerts based on historical patterns, reducing manual review time and improving incident response efficiency.

---

## 🛠️ Technical Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Data Processing:** Large-scale data cleaning, feature engineering, and class imbalance handling.
* **Models Explored:** Logistic Regression, Decision Trees, and Random Forest.

---

## 📊 Methodology & Workflow
1. **Data Exploration:** Analyzed over 1 million records to identify key features like `alert_type`, `severity`, and `source_ip`.
2. **Preprocessing:** Handled missing values, performed one-hot encoding for categorical variables, and normalized numerical features.
3. **Model Training:** Built and evaluated multiple classifiers to predict the probability of an alert being a "true positive."
4. **Evaluation:** Focused on Precision and Recall to ensure critical threats are not missed while minimizing false alarms.

---

## 💡 Key Business Insights
* **Operational Efficiency:** By automating the triage of low-severity, repetitive alerts, SOC teams can reallocate 30-40% of their time to proactive threat hunting.
* **Risk Mitigation:** High-confidence alerts are escalated instantly, significantly reducing the "Mean Time to Respond" (MTTR).
* **Scalability:** The framework is designed to ingest live log data, making it adaptable to evolving corporate network environments.

---

## 📂 Repository Structure
* `S3021074_soc_alert_framework.ipynb`: Complete Python implementation (Data cleaning to Model Evaluation).
* `Hiteesh_Alert_Prioritization_SOC_Report.pdf`: Comprehensive technical report detailing the research and findings.
* `CIS4055_Hiteesh_Alert_Prioritization_SOC_PPT.pdf`: Executive presentation of the project results.

---

## 🚀 Future Enhancements
* **Real-time Integration:** Deploying the model via an API to sit between a SIEM (like Splunk or Sentinel) and the analyst dashboard.
* **Deep Learning:** Exploring Neural Networks to identify more complex, multi-stage attack patterns.
