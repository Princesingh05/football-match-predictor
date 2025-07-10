# ⚽ Football Match Predictor (Premier League)

This project uses machine learning (Random Forest + Linear Regression) to predict the outcome and expected score of football matches based on historical data.  
Originally created by [Erik-Cupsa](https://github.com/Erik-Cupsa), this version includes updates, fixes, and enhancements to improve functionality and readability.

---

## 🔧 Features

- Predict match outcomes (Win/Loss)
- Predict expected goals for two teams
- Rolling average stats per team (last 3 games)
- Real historical match data (`matches.csv`)
- Cleaned and improved script execution and project structure

---

## 🧠 Algorithms Used

- `RandomForestClassifier` → to predict win/loss
- `LinearRegression` → to predict expected goals

---

## 📁 Project Structure

├── PL_Predictor.py # Main script
├── matches.csv # Match dataset
├── requirements.txt # Dependencies
├── .gitignore # Ignore venv, cache, etc.
└── README.md # This file

---

## 🚀 How to Run

1. Clone the repository
    
   ```bash
   git clone https://github.com/Princesingh05/football-match-predictor.git
   cd football-match-predictor
   
3. Create a virtual environment
   
   python -m venv venv
   .\venv\Scripts\
   
4. Install dependencies
   
   pip install -r requirements.txt

5. Run the script
   
   python PL_Predictor.py
   
✅ Sample Output

Prediction:
Chelsea vs Arsenal → 1 : 2
✅ Script executed successfully!

📝 Acknowledgements

Original Author: Erik-Cupsa

Adapted, debugged, and enhanced by: Princesingh05
   

