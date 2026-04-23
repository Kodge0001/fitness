# Personal Fitness Tracker 💪

A Streamlit-based web app that predicts calories burned during exercise using machine learning.

## Features
- 🎛️ **Interactive sliders** for Age, BMI, Duration, Heart Rate, Body Temperature
- 🤖 **ML prediction** using Random Forest Regressor
- 📊 **Similar results** comparison from the dataset
- 📈 **General info** — see how you compare to others

## Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

Open the URL shown in the terminal (usually [http://localhost:8501](http://localhost:8501)).

## Dataset
- `exercise.csv` — Exercise data (User_ID, Gender, Age, Height, Weight, Duration, Heart_Rate, Body_Temp)
- `calories.csv` — Calorie data (User_ID, Calories)

## Tech Stack
- Python / Streamlit
- Scikit-learn (Random Forest Regressor)
- Pandas / Matplotlib / Seaborn
