 🧠 Employee Performance Predictor

> **Analyze and predict employee productivity using Machine Learning**

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python\&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML%20Library-orange?logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Colab](https://img.shields.io/badge/Run%20on-Google%20Colab-yellow?logo=googlecolab)

---

## 🚀 Overview

The **Employee Performance Predictor** is a Machine Learning web application that predicts **employee productivity** based on organizational and work-related features.
It enables **data-driven decision-making** in workforce management by using past performance data, employee details, and production metrics.

---

## 🎯 Key Features

* 🌐 Interactive Flask web interface
* 🎨 Colorful, modern, and responsive UI
* 🤖 Machine Learning–powered productivity predictions
* 📊 Real-time input form for dynamic predictions
* ⚙️ End-to-end integration (model + web app + UI)
* 🧠 Deployable directly in Google Colab with Ngrok

---

## 🧩 Tech Stack

| Layer          | Technology                          |
| -------------- | ----------------------------------- |
| **Frontend**   | HTML5, CSS3 (Custom Styling)        |
| **Backend**    | Flask                               |
| **ML Model**   | RandomForestRegressor               |
| **Libraries**  | pandas, numpy, scikit-learn, joblib |
| **Deployment** | Flask + Ngrok (for Colab)           |

---

## 🧠 Use Case Scenarios

### 🧍‍♂️ Scenario 1: Talent Retention

Predicts which high-performing employees are at risk of attrition, helping HR implement proactive retention strategies.

### 💪 Scenario 2: Performance Improvement

Managers can identify employees who may require additional training or support to improve productivity.

### ⚖️ Scenario 3: Resource Allocation

Optimizes task assignments by matching employees with roles that align with their strengths.

---

## ⚙️ Workflow

1. **Data Preprocessing**

   * Fill missing values using mean.
   * Encode categorical features with OneHotEncoder.

2. **Model Training**

   * Random Forest Regressor model trained and saved as `.pkl` file.

3. **Prediction Interface**

   * Flask app accepts user input via HTML form.
   * Data is reshaped and fed into the model for prediction.
   * Output displayed instantly with styled results section.

---

## 📊 Dataset

**Source:** [Garments Worker Productivity Dataset – Kaggle](https://www.kaggle.com/datasets)

**Features:**

* Quarter
* Department
* Day
* Targeted Productivity
* Number of Workers

**Target:**

* `Actual Productivity`

---

## 💻 Installation & Setup

### 🔹 1. Clone the Repository

```bash
git clone https://github.com/your-username/Employee-Performance-Prediction.git
cd Employee-Performance-Prediction
```

### 🔹 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 🔹 3. Train the Model

```bash
python model_train.py
```

### 🔹 4. Run the Flask App

```bash
python app.py
```

### 🔹 5. (Optional: For Colab)

```python
!pip install flask-ngrok
from flask_ngrok import run_with_ngrok
from app import app
run_with_ngrok(app)
app.run()
```

Visit the generated **Ngrok URL** to open your live colorful web app 🎨.

---

## 📸 UI Preview

Below is a preview of your beautiful Flask UI:

![App Screenshot](https://cdn-icons-png.flaticon.com/512/3135/3135715.png)

---

## 📂 Folder Structure

```
Employee-Performance-Prediction/
│
├── app.py                        # Flask web app
├── model_train.py                # Model training script
├── employee_performance_model.pkl # Trained ML model
├── templates/
│   └── index.html                # Web UI
├── static/
│   └── styles.css                # (Optional) CSS styles
├── requirements.txt
└── README.md
```

---

## 🧰 Requirements

```
flask
flask-ngrok
scikit-learn
pandas
numpy
joblib
```

---

## 📈 Example Output

```
Predicted Productivity: 0.78
(Employee expected to achieve ~78% efficiency)
```

---

## 👩‍💻 Author

**Girija Kavuri**
🎓 *Machine Learning & Web Developer*
MAIL-girijakanna220f@gmail.com
github-girija4224

## 🌟 Acknowledgements

* Kaggle (Dataset Provider)
* Scikit-learn (ML Toolkit)
* Flask (Web Framework)
* Google Colab (Runtime Environment)

---

## 🏁 Project Highlights

✅ Real-time prediction
✅ Enhanced gradient UI
✅ Fully functional Flask integration
✅ Ready for Colab deployment

---

Would you like me to **generate a small `requirements.txt`** file that matches your Colab environment (so you can upload both together to GitHub)?
