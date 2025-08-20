# EEG-Based Focus and Mental State Tracker

## 📌 Project Goal
Build a real-time software system that classifies mental states (e.g., focused, relaxed, drowsy) from EEG signals using public datasets and provides live visualization and productivity feedback via a dashboard.

## 🛠 Tech Stack
- **Language:** Python 3.10+
- **Libraries:** NumPy, SciPy, Matplotlib, Pandas, scikit-learn, MNE-Python, Streamlit
- **Environment:** venv
- **IDE/Notebook:** Jupyter Notebook for prototyping, VS Code for integration

## 📂 Project Structure
eeg-focus-tracker/
│── data/ # raw EEG files (excluded from repo)
│── notebooks/ # Jupyter notebooks for exploration, preprocessing, model training
│── src/ # Python scripts for reusable functions
│── models/ # saved ML models (.pkl, .joblib)
│── dashboard/ # Streamlit app code
│── .gitignore
│── README.md
