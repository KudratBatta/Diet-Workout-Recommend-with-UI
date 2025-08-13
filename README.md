# Diet-Workout-Recommend-with-UI
# 🥗💪 Fit Aura – Personalized Diet & Workout Recommendation System

Fit Aura is a **Flask-based web application** that provides **personalized diet and workout plans** based on user inputs such as age, gender, height, weight, diet preference, exercise preference, and health conditions.  
It also calculates the **BMI** and categorizes the user’s health status, then recommends meal and exercise plans accordingly.

---

## 🚀 Features
- **BMI Calculation & Health Category**
- **Personalized Diet Plans** (Vegetarian, Non-Vegetarian, Vegan)
- **Customized Workout Plans** (Cardio, Strength Training, Yoga)
- **Condition-specific Adjustments**
- **Modern, Responsive UI**
- **Flask Backend with Pre-trained ML Model**

---

## 🖼 UI Overview
- **Left Panel:** Input form for user details  
- **Right Panel:** Motivational message and app description  
- **Results Section:** Displays BMI, category, diet plan, and workout plan  

---

## 🛠 Tech Stack
- **Frontend:** HTML5, CSS3 (Custom Styling)
- **Backend:** Python (Flask)
- **Machine Learning:** Scikit-learn, Joblib
- **Model Files:**  
  - `best_health_model.pkl` – Pre-trained ML model  
  - `label_encoder.pkl` – Encodes/decodes model outputs

---
## 📂 Project Structure
- ├── app.py # Flask backend application
- ├── templates/
- │ └── index.html # Main HTML page
- ├── static/
- │ └── style.css # Custom styles for UI
- ├── best_health_model.pkl # Pre-trained ML model
- ├── label_encoder.pkl # Label encoder for predictions
- ├── README.md # Project documentation

## ⚙️ Installation & Setup

```bash
1️⃣ Clone the Repository
git clone https://github.com/yourusername/fit-aura.git
cd fit-aura

2️⃣ Create Virtual Environment & Install Dependencies
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows

pip install flask joblib numpy scikit-learn
3️⃣ Run the Application
python app.py
