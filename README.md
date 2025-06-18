# 📱 Smartphone Market Intelligence System – Capstone Project

A complete end-to-end data science project to analyze smartphones, predict smartphone prices and recommend similar phones, built using real-world data scraped from Smartprix. This project involves everything from web scraping to feature engineering, ML modeling, hyperparameter tuning, and building a Streamlit-based interactive web app.

🔗 Live Demo: (https://smartphone-price-and-reco-web.streamlit.app/)

## 🚀 Key Highlights
4500+ Smartphones Scraped from Smartprix using Selenium.

Extensive data cleaning & preprocessing: Extracted structured features (processor, RAM, camera, battery, display) from messy text columns.

Handled 40%+ missing values using grouped mode imputation based on brand, price range, RAM, etc.

Outlier detection based on domain logic: removed outdated or unusual phones using RAM, ROM, battery, clock speed, and price relationships.

Feature selection using ANOVA, Shapiro-Wilk, Recursive Feature Elimination (RFE), and permutation importance.

Trained and tuned Random Forest, Gradient Boost, and XGBoost using Optuna. Combined them into a voting ensemble achieving R² = 0.872.

Developed a Content-Based Recommender System using cosine similarity on encoded + scaled features.

Built an interactive Streamlit app with 3 modules:

📊 Analytics & Insights

💰 Price Prediction

🤝 Phone Recommender System


## 🧠 Tech Stack

Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Optuna, Plotly, Seaborn

Web Scraping: Selenium

Deployment/UI: Streamlit

Similarity: Cosine Similarity (from sklearn)
