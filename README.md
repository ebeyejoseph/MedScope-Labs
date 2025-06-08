# 🧬 MedScope Labs - MEDSCOPE HEALTH SCREENER

MedScope Health Screener is a futuristic web-based health diagnostic platform that enables users to assess their risk for silent killer disease (eg. diabetes) using basic lifestyle and clinical indicators. The frontend is built with **HTML, CSS, and JavaScript**, and it connects to a Flask-powered machine learning backend hosted on Render.

## 🚀 Live Demo

👉 [Visit MedScope Labs](https://ebeyejoseph.github.io/medscope-frontend/)

---

## ⚙️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Flask
- **Machine Learning:** Scikit-learn (with `DecisionTreeClassifier`)
- **Deployment:**
  - Frontend: GitHub Pages
  - Backend: Render
  - Model hosting: Google Drive

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

## 🧰 How to Run Locally

### Clone the Repositories

```bash
# Clone backend
git clone https://github.com/ebeyejoseph/medscope-ml-backend
# Or download the root folder manually from the link 
cd medscope-backend 
pip install -r requirements.txt
python app.py  # Start the Flask server

# Clone frontend
git clone https://github.com/ebeyejoseph/medscope-frontend
cd medscope-frontend
# Open index.html in your browser
# Don't forget to edit the API link to the backend address in the script file (e.g http://127.0.0.1:5000/predict)

---

## 📚 References

- **Dataset**: The dataset used for training the model was obtained from the [Behavioral Risk Factor Surveillance System (BRFSS) 2015](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset) on Kaggle.
- **Modeling Tools**: Machine learning model was built using [Scikit-learn](https://scikit-learn.org/).
- **Web App Backend**: Built with [Flask](https://flask.palletsprojects.com/).
- **Frontend**: Built using basic HTML, CSS, and JavaScript, and deployed via [GitHub Pages](https://pages.github.com/).
- **Backend Deployment**: Hosted on [Render](https://render.com/).
- **Model Hosting**: Model file (`model.pkl`) was stored using [Google Drive](https://drive.google.com/).

---

## 📌 Author

**Ebeye Joseph Chukwuemeka**  
Electrical and Electronic Engineering, 300 Level  
Redeemer's University, Ede  
📧 josephebeye105@gmail.com  
🔗 [GitHub](https://github.com/ebeyejoseph) | [LinkedIn](https://www.linkedin.com/in/ebeye-joseph-87b53b235/)

