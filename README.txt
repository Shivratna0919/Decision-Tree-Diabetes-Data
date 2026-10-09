# 🩺 DiabetesAI – Diabetes Risk Intelligence Platform

An interactive Machine Learning web application developed using **Python and Streamlit** to estimate diabetes risk based on patient health parameters. The platform provides real-time predictions, risk probability, interactive visualizations, historical records, and dataset analytics through a modern dashboard.

## 🚀 Features

* 🔮 **Diabetes Risk Prediction** – Estimates diabetes risk using a Decision Tree Classifier.
* 📊 **Risk Probability Analysis** – Displays predicted probability and risk categories.
* 📈 **Interactive Visualizations** – Includes risk gauge, radar charts, and analytics graphs.
* 📜 **Prediction History** – Stores previous predictions with timestamps.
* 🗂️ **Dataset Explorer** – Explore dataset records and feature distributions.
* 🤖 **Model Architecture** – Displays machine learning algorithm details and input features.
* 📥 **CSV Report Export** – Download prediction summaries and historical records.
* 🎨 **Modern Dashboard** – Responsive Streamlit interface with a dark theme and glassmorphism styling.
* 📚 **Clinical Insights** – Provides educational information about important diabetes-related health parameters.

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Frontend / Web Framework:** Streamlit
* **Machine Learning:** Scikit-learn
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Plotly
* **Data Storage:** CSV files
* **Model Serialization:** Pickle

## 🧠 Machine Learning Algorithm

The application uses a **Decision Tree Classifier** to classify input data into two categories:

* `0` – No diabetes predicted by the model
* `1` – Diabetes predicted by the model

The model uses eight input features:

1. Pregnancies
2. Glucose
3. Blood Pressure
4. Skin Thickness
5. Insulin
6. BMI
7. Diabetes Pedigree Function
8. Age

The application also calculates a model-based probability score and categorizes the estimated risk as Low, Moderate, High, or Very High.

## 📂 Project Structure

```text
DiabetesAI/
│
├── app.py
├── diabetes.csv
├── diabetes_model.pkl
├── diabetes_features.pkl
├── prediction_history.csv
├── requirements.txt
└── README.md
```

**Note:** The trained model, feature-order file, and dataset must be provided for all corresponding features to work. The prediction history CSV is created automatically if it does not exist.

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd DiabetesAI
```

### 2. Install Dependencies

```bash
pip install streamlit pandas numpy plotly scikit-learn
```

### 3. Add Required Files

Place `diabetes_model.pkl` and `diabetes_features.pkl` in the project directory. Add `diabetes.csv` to enable dataset exploration.

### 4. Run the Application

```bash
streamlit run app.py
```

The application will open in your default browser.

## 📊 Application Modules

| Module             | Description                                      |
| ------------------ | ------------------------------------------------ |
| Overview           | Introduction to the platform                     |
| Prediction Engine  | Enter health parameters and generate predictions |
| Analytics Hub      | Visualize historical prediction statistics       |
| Prediction History | Review and export previous assessments           |
| Dataset Explorer   | Inspect dataset records and distributions        |
| Model Architecture | View model configuration and input features      |
| Clinical Insights  | Explore educational health information           |
| About              | View application and technology details          |

## 🎯 Project Objectives

* Apply machine learning to a healthcare-related classification problem.
* Build an interactive and user-friendly prediction dashboard.
* Visualize prediction probabilities and historical data.
* Practice Python programming, data processing, and model integration.
* Demonstrate how machine learning can support educational health analytics.

## 🔮 Future Enhancements

* Model performance evaluation using accuracy, precision, recall, and F1-score.
* Improved data validation and model explainability.
* Secure database integration.
* User authentication and personalized dashboards.
* Cloud deployment for online access.
* Integration of additional validated health datasets.

## ⚠️ Disclaimer

This project is intended for **educational, academic, and portfolio demonstration purposes only**. It is not a medical diagnostic tool and must not be used to diagnose or treat diabetes. Prediction results may be inaccurate. Consult a qualified healthcare professional for medical assessment.

## 👨‍💻 Author

Developed as a Machine Learning and Data Science project to demonstrate predictive analytics, data visualization, and interactive web application development.

If you find this project useful, consider giving the repository a ⭐ on GitHub.
