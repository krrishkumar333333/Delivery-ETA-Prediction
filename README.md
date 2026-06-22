# Optimizing Delivery ETAs with Graph-Based Network Intelligence 📦

![Certificate](Delivery_ETA.png)

*Certified by IIT Guwahati Summer Analytics*

## 📌 The Business Constraint
In supply chain logistics and last-mile delivery, inaccurate Estimated Times of Arrival (ETAs) lead to massive operational inefficiencies, warehouse bottlenecks, and degraded customer satisfaction. The objective of this project was to architect a predictive model that leverages temporal and spatial intelligence to forecast delivery times with extreme precision.

## ⚙️ The Technical Architecture
* **Algorithm:** Advanced Regression Ensembles (XGBoost / LightGBM)
* **Feature Engineering:** Synthesized graph-based network features, extracting geographic nodes, delivery transit velocities, and temporal congestion patterns.
* **Evaluation Metric:** Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) to strictly penalize large ETA deviations.

## 🚀 Key Results & Impact
* Developed a robust ETA pipeline capable of dynamically adjusting predictions based on network-level intelligence.
* Successfully isolated spatial and temporal bottlenecks, providing actionable intelligence for routing optimization and supply chain management.

## 📂 Repository Contents
* `Delivery_Network_Intelligence.ipynb`: The end-to-end data processing, feature synthesis, and model training pipeline.
* `Delhivery_ETA_Whitepaper_IIT_Guwahati.pdf`: Comprehensive breakdown of the architectural strategy and business impact.
* `dashboard.py`: Interactive dashboard script for real-time ETA visualization and monitoring.
