🌾 AgroSense — Crop Recommendation System

AgroSense is an ML-based Crop Recommendation System that predicts the best crop using soil nutrients (N, P, K), temperature, humidity, pH, and rainfall. Built in Python on Google Colab, it compares 6 algorithms — achieving ~99% accuracy with Random Forest — helping farmers make smarter, data-driven decisions.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

DATASET
Rows : 2,200 Features : 7 (N, P, K, Temperature, Humidity, pH, Rainfall) Target : 22 Crops Source : Kaggle — Crop Recommendation Dataset

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

MODELS & ACCURACY
✅ Random Forest → 99.09% Naive Bayes → 99.54% Gradient Boosting → 98.18% Decision Tree → 97.72% SVM → 97.27% KNN → 96.36%

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

ML PIPELINE
Data Loading → EDA → Preprocessing → Model Training → Evaluation → Prediction → Save Model

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

HOW TO RUN
Open Google Colab (colab.research.google.com)
Upload Crop_Recommendation_System.ipynb
Run all cells — dataset loads automatically from GitHub
Local Setup: pip install numpy pandas matplotlib seaborn scikit-learn joblib jupyter notebook Crop_Recommendation_System.ipynb

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

SAMPLE PREDICTION
Input : N=90, P=42, K=43, Temp=20.5, Humidity=82, pH=6.5, Rainfall=202 Output : Recommended Crop → RICE

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

VISUALIZATIONS
Crop distribution bar chart
Feature correlation heatmap
Feature distribution histograms
Boxplots for outlier detection
Model accuracy comparison chart
Confusion matrix (22x22)
Feature importance chart
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

FUTURE SCOPE
Deploy using Streamlit / Flask
Integrate live Weather API
Add Fertilizer Recommendation module
Extend for regional Indian crops
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

LICENSE
MIT License — free to use with attribution.

"Empowering farmers with data, one crop at a time." 🌱
