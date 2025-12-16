### 📘 ` `

This repository provides the full Python implementation for the paper **"AIRSPAN-X: Federated XGBoost with Sequential Anomaly Detection for Explainable Urban Air Quality Prediction."** It presents a scalable, interpretable, and privacy-preserving framework for urban air quality prediction using distributed IoT sensor data.

Key components include:

* **Federated Learning with Adaptive Aggregation:** XGBoost models are trained locally at edge nodes, and aggregated using performance-aware weights to handle non-IID data.
* **SHAP Explainability:** SHapley Additive exPlanations are used to provide both global and instance-level feature importance for AQI predictions.
* **PrefixSpan Anomaly Detection:** A sequential pattern mining algorithm is applied to identify temporal irregularities in pollutant patterns.
* **Real-world Deployment:** Evaluated across 22 districts in Tehran with accuracy reaching **98.64%**, MSE as low as **15.52**, and explainability insights highlighting PM2.5, NO₂, and PM10 as key contributors.

🔸🔸🔸🔸🔸🔸🔸🔸🔸
🌬️This repository contains the code accompanying the paper:

**AIRSPAN-X: Federated XGBoost with Sequential Anomaly Detection for Explainable Urban Air Quality Prediction**
DOI: ([https://doi.org/10.1109/ICCKE68588.2025.11273819](https://doi.org/10.1109/ICCKE68588.2025.11273819))

If you use this code in your research and find it helpful, please cite:

> S. Shafaati and S. H. Erfani, "AIRSPAN-X: Federated XGBoost with Sequential Anomaly Detection for Explainable Urban Air Quality Prediction," 2025 15th International Conference on Computer and Knowledge Engineering (ICCKE), Mashhad, Iran, Islamic Republic of, 2025, pp. 1-6, doi: 10.1109/ICCKE68588.2025.11273819.

**Keywords:** Data privacy; Pollution; Accuracy; Federated learning; Atmospheric modeling; Urban areas; Air quality; Data models; Internet of Things; Anomaly detection; Air Quality Prediction; Federated Learning; XGBoost; SHAP Explainability; PrefixSpan; Internet of Things (IoT).

A publicly accessible version of the full paper and the presentation file are also available on my ResearchGate profile.
🔸🔸🔸🔸🔸🔸🔸🔸🔸

📊 **Dataset Access**
The dataset used in this study, titled *“Anomaly-Aware Air Quality Monitoring with SHAP and PrefixSpan in Federated IoT Networks”*, is publicly available on Kaggle:
🔗 [https://www.kaggle.com/datasets/saghar001/air-quality-prediction-case-study](https://www.kaggle.com/datasets/saghar001/air-quality-prediction-case-study)
🔗 Saghar Shafaati. (2025). Air quality Prediction: Case Study [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/10564886 
