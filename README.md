# Delhivery Supply Chain Intelligence: Graph-Enhanced ETA Optimization 🚛

![Certificate](Delivery_ETA.png)

*Certified by IIT Guwahati Summer Analytics*

## 📌 Project Summary & Business Impact
This project features a complete Graph-Enhanced Machine Learning pipeline and an interactive Executive Digital Twin designed for logistics ETA optimization. The objective was to eliminate warehouse bottlenecks and improve last-mile predictability by utilizing structural network intelligence.

**Key Executive Outcomes:**
* **Model Precision:** Reduced Mean Absolute Error (MAE) by **52.8%** (108.31 mins ➔ 51.10 mins).
* **Operational Stability:** Doubled the SLA Predictability Window to **68.45%**.
* **Financial Strategy:** Delivered a strategic CapEx recommendation of **$2.5M** for automated cross-docking at Hub IND000000ACB to successfully avoid the "FTL Margin Trap."

## ⚙️ The Technical Architecture
* **Data Engineering:** Ingested and processed raw logistics datasets to build an analytical foundation.
* **Graph Intelligence:** Constructed Directed Graphs and engineered **Node2Vec Embeddings** to capture spatial bottlenecks and network velocities.
* **Predictive Algorithm:** Deployed an advanced **XGBoost Modeling** pipeline on top of the graph embeddings to forecast localized delays.
* **Structural Isolation:** Heavy ML training libraries (Node2Vec, XGBoost) were strictly isolated to the Jupyter pipeline to ensure seamless, compilation-free execution of the Streamlit dashboard.

## 💻 Execution Instructions (Local Environment)
This enterprise pipeline has been explicitly packaged for seamless local execution. No cloud authentication or Google Drive mounting is required.

**PHASE A: RUNNING THE CORE ML PIPELINE**
1. Extract the repository files to your local machine.
2. Ensure the `dataset_for_the_project` folder is sitting in the exact same directory as the Jupyter notebook.
3. Open `Delivery_Network_Intelligence.ipynb` using Jupyter, VS Code, or your preferred IDE. *(Note: If using Google Colab, you must manually upload the .csv file into Colab's temporary session storage before running, as the code uses local relative paths).*
4. Execute the cells sequentially. The pipeline will automatically find and ingest the local dataset.

**PHASE B: LAUNCHING THE DIGITAL TWIN DASHBOARD**
1. Open your Command Prompt or Terminal and navigate to this repository folder.
2. Install the required environment dependencies:
```bash
pip install streamlit pandas numpy networkx
```
3. Launch the application dashboard:
   ```bash
   python -m streamlit run dashboard.py
   ```
   
