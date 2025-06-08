# 🚶 Human Step Detection for Binary Classification

**Author:** Pranav Kumar Sah  

This project aims to predict the **start** and **end points of human steps** using time-series signals from accelerometer and gyroscope sensors.  
It involves training different deep learning models to accurately detect step events from sequential sensor data.

---

## 📂 Project Structure  

The project consists of the following components:

- 📓 **Jupyter Notebook**
  - `HSD.ipynb` — End-to-end implementation including:
    - Data loading and preprocessing  
    - Feature engineering  
    - Model definitions (MLP, GRU, LSTM)  
    - Model training  
    - Evaluation and result saving  

- 📄 **Dataset**
  - `./data/` — Folder containing:
    - Training and test CSV files  
    - Step labels  
    - Cleaned data for model input  

- 📁 **Predictions**
  - Saved prediction CSV files for each model type:
    - `predicted_labels_MLP.csv`
    - `predicted_labels_GRU.csv`
    - `predicted_labels_LSTM.csv`

- 📁 **PDF**
  - `HSD.pdf` — Full printout of the entire notebook code and results.

---

## ⚙️ How to Use  

1. **Open and Run the Notebook:**
   - Launch `HSD.ipynb` in **Jupyter Notebook**, **JupyterLab**, or **Visual Studio Code**.
   - Execute each cell in sequence to preprocess data, train models, and evaluate results.

2. **Modify and Experiment:**
   - Try adjusting:
     - Model hyperparameters (hidden size, batch size, learning rate)
     - Number of training epochs
     - Model architectures (add/drop layers, experiment with different RNN variants)

3. **View Predictions:**
   - After testing, predictions are saved as CSV files in the working directory for each model.

---