# 🔥 Forest Fire Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Flask](https://img.shields.io/badge/Flask-Web%20App-black?logo=flask)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-blue?logo=numpy)
![GitHub](https://img.shields.io/github/license/Anujku007/Testforestfire)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📖 Overview

Forest fires are one of the leading causes of environmental destruction, causing severe damage to ecosystems, wildlife, and human life. Predicting the severity of forest fires based on environmental and meteorological conditions can help authorities take preventive actions and allocate resources effectively.

This project is an **end-to-end Machine Learning application** that predicts the **Forest Fire Index (FWI)** using historical environmental data. The application includes data preprocessing, model training, evaluation, and deployment through a Flask web application.

---

## ✨ Features

- 📊 Data preprocessing and feature engineering
- 🤖 Multiple Machine Learning models trained and evaluated
- 📈 Performance comparison using evaluation metrics
- 💾 Model serialization using Pickle
- 🌐 Interactive Flask web application
- 📱 User-friendly prediction interface
- ⚡ Real-time prediction based on user inputs

---

## 🛠 Tech Stack

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Web Framework
- Flask

### Deployment
- HTML
- CSS
- Bootstrap
- Render / Localhost

### Tools
- Git
- GitHub
- VS Code

---

# 📂 Project Structure

```text
Testforestfire/
│
├── artifacts/
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── notebook/
│   └── ForestFirePrediction.ipynb
│
├── src/
│   ├── exception.py
│   ├── logger.py
│   ├── utils.py
│   ├── pipeline/
│   └── components/
│
├── templates/
│   ├── index.html
│   └── home.html
│
├── static/
│
├── application.py
├── requirements.txt
├── setup.py
└── README.md
```

---

# ⚙️ Machine Learning Workflow

```text
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Train Test Split
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Model Selection
        │
        ▼
Model Serialization
        │
        ▼
Flask Deployment
```

---

# 📊 Dataset Features

The model uses meteorological parameters such as:

- Temperature
- Relative Humidity
- Wind Speed
- Rainfall
- FFMC
- DMC
- ISI
- Classes
- Region

These features are used to predict the **Fire Weather Index (FWI)**.

---

# 📈 Model Evaluation

Several regression algorithms were trained and compared.

Examples include:

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet

Evaluation Metrics:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

The best-performing model was selected for deployment.

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Anujku007/Testforestfire.git
```

Move into the project

```bash
cd Testforestfire
```

Create Virtual Environment

```bash
python -m venv venv
```

Activate

Windows

```bash
venv\Scripts\activate
```

Linux / Mac

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

```bash
python application.py
```

Open your browser

```
http://127.0.0.1:5000
```

---

# 💻 Application Preview

## Home Page

> *(Add Screenshot Here)*

---

## Prediction Page

> *(Add Screenshot Here)*

---

## Prediction Result

> *(Add Screenshot Here)*

---

# 📊 Example Prediction

| Temperature | RH | Wind | Rain | Prediction |
|------------|----|------|------|------------|
| 29 | 57 | 18 | 0 | Moderate Fire Risk |

---

# 🧠 Skills Demonstrated

✔ Machine Learning

✔ Data Preprocessing

✔ Feature Engineering

✔ Regression Models

✔ Model Evaluation

✔ Flask Development

✔ Model Deployment

✔ Python Programming

✔ Git & GitHub

---

# 🔮 Future Improvements

- Deploy using Docker
- CI/CD Pipeline
- Cloud Deployment on AWS/Azure
- Model Monitoring
- Explainable AI (SHAP)
- REST API using FastAPI
- Database Integration

---

# 📸 Screenshots

| Home | Prediction | Result |
|------|------------|--------|
| Add Image | Add Image | Add Image |

---

# 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# 👨‍💻 Author

**Anuj Kumar**

📧 LinkedIn: *(Add your LinkedIn URL)*

💻 GitHub: https://github.com/Anujku007

---

# ⭐ Support

If you found this project useful,

⭐ Star this repository

🍴 Fork it

📢 Share it with others

---

## 📜 License

This project is licensed under the MIT License.

---

## 🌟 Acknowledgements

Special thanks to **Krish Naik** for providing valuable guidance and practical insights into building end-to-end Machine Learning applications.