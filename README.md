# Carbon-Footprint-Estimator-for-Urban-Households

This project demonstrates a machine learning approach to estimate the **annual carbon footprint (kg CO₂e)** of urban households using synthetic data. It leverages features like household size, dwelling type, vehicle usage, diet, energy consumption, and travel habits to predict carbon emissions.

---

## 📂 Project Structure
├── carbon_footprint_dataset.csv # Synthetic dataset (>100 records)
├── carbon_footprint_estimator.py # Training and prediction script
└── README.md # Project documentation

yaml
Copy code

---

## ⚙️ Features
- Synthetic dataset generation for household carbon emissions  
- Data preprocessing with **OneHotEncoding** and **StandardScaler**  
- Training a **Random Forest Regressor** to estimate household CO₂e footprint  
- Evaluation with **MAE, RMSE, and R²** metrics  
- Feature importance visualization for interpretability  
- Quick estimation example for a sample household  

---

## 🚀 Usage

### 1. Install dependencies
```bash
pip install pandas numpy scikit-learn matplotlib joblib
2. Run the estimator
Make sure carbon_footprint_dataset.csv is in the same folder, then run:

bash
Copy code
python carbon_footprint_estimator.py
This will:

Train the model on the dataset

Print evaluation metrics

Save the trained model as carbon_footprint_model.pkl

Display a bar chart of feature importances

Run a demo prediction for a sample household

📊 Example Output
yaml
Copy code
Loaded dataset with shape: (800, 16)
Test MAE: 421.7 kg CO2e
Test RMSE: 587.3 kg CO2e
Test R^2: 0.89
Saved trained model to: carbon_footprint_model.pkl
Estimated annual footprint for example household: 7,850 kg CO2e
🔍 Notes
The dataset is synthetic, created with plausible assumptions and emission factors, not real-world data.

This project is for educational and demonstration purposes only.

Real applications should use verified household survey and emissions datasets.

📌 Future Work
Replace synthetic data with real household surveys

Add time-series analysis for seasonal variation

Build a simple web app for user-friendly household footprint estimation

pgsql
Copy code

Author Name: Agbozu Ebingiye Nelvin
Email: nelvinebingiye@gmail.com
Github: https://github.com/Nelvinebi/
