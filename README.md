## END TO END MACHINE LEARNING PROJECT

# 🎓 Student Exam Performance Prediction (End-to-End ML Project)

An end-to-end Machine Learning project that predicts a student’s **Math score**
based on demographic and academic features using a trained regression model.
The project follows **industry-standard ML engineering practices**, including
modular coding, pipelines, and a deployable Flask web application.

---

## 🚀 Features

- End-to-End ML pipeline (Data Ingestion → Transformation → Model Training)
- Multiple regression models with hyperparameter tuning
- Best model selection based on R² score
- Trained model & preprocessor saved as artifacts
- Flask web app for real-time predictions
- Clean project structure (production-oriented)
- Ready for cloud deployment (Render)

---

## 🧠 Tech Stack

**Programming Language**
- Python

**Machine Learning & Data Science**
- NumPy
- Pandas
- Scikit-Learn
- CatBoost
- XGBoost

**Visualization**
- Matplotlib
- Seaborn

**Web Framework**
- Flask

**Model Serving**
- Gunicorn

---

## 📂 Project Structure

```text
End-to-End-ML-Project/
│
├── app.py
├── requirements.txt
├── README.md
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │   ├── train_pipeline.py
│   │   └── predict_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│   ├── index.html
│   └── home.html
│
├── notebook/
│   └── EDA.ipynb
│
└── .gitignore


📊 Input Features

| Feature                 | Description                |
| ----------------------- | -------------------------- |
| Gender                  | Student gender             |
| Race/Ethnicity          | Student ethnic group       |
| Parental Education      | Parent’s highest education |
| Lunch                   | Lunch type                 |
| Test Preparation Course | Completed / Not            |
| Reading Score           | Reading exam score         |
| Writing Score           | Writing exam score         |


🎯 Target Variable

Math Score

⚙️ How to Run Locally
1️⃣ Clone the repository
git clone https://github.com/debarnabdas007/End-to-End-ML-project.git
cd End-to-End-ML-project
2️⃣ Create virtual environment
python -m venv ml-venv
ml-venv\Scripts\activate   # Windows

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the application
python app.py

5️⃣ Open in browser
http://127.0.0.1:5000

🌐 Deployment

Platform: Render

Server: Gunicorn

No credit card required

Free tier supported

📌 Key Learning Outcomes

Building production-ready ML pipelines

Modular ML system design

Model training & evaluation at scale

Serving ML models using Flask

Real-world deployment practices

👨‍💻 Author

Debarnab Das
Computer Science Undergraduate
Machine Learning & Backend Enthusiast

🔗 GitHub: https://github.com/debarnabdas007

⭐ If you like this project

Give it a star ⭐ and feel free to fork!

---

## 🔥 Next Action (Very Important)
👉 Send me:
1️⃣ `app.py`  
2️⃣ `src/pipeline/predict_pipeline.py`

I’ll **upgrade your app to production-grade error handling** without touching your ML logic.
