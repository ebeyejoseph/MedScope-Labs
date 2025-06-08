# 🧬 MedScope Labs - MEDSCOPE HEALTH SCREENER

MedScope Health Screener is a futuristic web-based health diagnostic platform that enables users to assess their risk for silent killer disease (eg. diabetes) using basic lifestyle and clinical indicators. The frontend is built with **HTML, CSS, and JavaScript**, and it connects to a Flask-powered machine learning backend hosted on Render.

## 🚀 Live Demo

👉 [Visit MedScope Labs](https://ebeyejoseph.github.io/medscope-frontend/)

---

## 🗂️ Repositories

- **Frontend Repository:** [medscope-frontend](https://github.com/ebeyejoseph/medscope-frontend)
- **Backend Repository:** [medscope-backend](https://github.com/ebeyejoseph/medscope-backend)

---

## ⚙️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Flask
- **Machine Learning:** Scikit-learn (with `DecisionTreeClassifier`)
- **Deployment:**
  - Frontend: GitHub Pages
  - Backend: Render

---

## 📊 How It Works

1. The user fills out a health survey form.
2. The frontend sends the data to the Flask backend.
3. The backend:
   - Scales the input using `scaler.pkl`
   - Feeds the scaled input into the ML model (`model.pkl`)
   - Returns the predicted risk level.
4. The result is displayed instantly on the frontend.

---

## 📁 Key Files in Backend

- `model.pkl`: Trained machine learning model for diabetes prediction.
- `scaler.pkl`: Used to normalize incoming data before prediction.

---

## 🧪 Status

✅ Diabetes prediction is fully working.  
🚧 Additional conditions like heart disease and hypertension are marked **"Coming Soon"** in the interface.

---

## 📌 Author

**Ebeye Joseph Chukwuemeka**  
Electrical and Electronic Engineering, 300 Level  
Redeemer's University, Ede  
📧 josephebeye105@gmail.com  
🔗 [GitHub](https://github.com/ebeyejoseph) | [LinkedIn](https://www.linkedin.com/in/ebeye-joseph-87b53b235/)

