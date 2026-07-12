# 🏏 IPL Match Winner Prediction

> **A Machine Learning application that predicts the winning probability of IPL teams during a live match based on match conditions such as batting team, bowling team, target, current score, overs, and wickets.**

---

## 🎯 Project Goal

Cricket is a game of uncertainties, where the outcome can change dramatically with every ball. This project leverages historical **Indian Premier League (IPL)** match data to estimate the winning probability of both teams during an ongoing match.

The trained model is deployed through an interactive web application, allowing users to simulate match scenarios and view real-time win predictions.

---

## 📌 Project Highlights

◈ Live match winner probability prediction

◈ Trained using historical IPL match data

◈ Interactive prediction interface

◈ Data preprocessing and feature engineering

◈ End-to-end Machine Learning workflow

◈ Probability-based predictions instead of binary classification

---

## 📊 Dataset

The project uses historical IPL data containing match-level and ball-by-ball information.

| Dataset | Purpose |
|---------|---------|
| `matches.csv` | Match information |
| `deliveries.csv` | Ball-by-ball match data |

---

## 🧩 Repository Structure

```text
📦 IPL Match Winner Prediction
│
├── 📄 IPL_model.ipynb          # Model development and training
├── 📄 app.py                   # Streamlit application
├── 📂 data
│   ├── deliveries.csv
│   └── matches.csv
└── 📄 requirements.txt
```

---

## ⚙️ Prediction Factors

The prediction model considers multiple match parameters, including:

◆ Batting Team

◆ Bowling Team

◆ Host City

◆ Target Score

◆ Current Score

◆ Overs Completed

◆ Wickets Lost

◆ Runs Required

◆ Balls Remaining

---

## 🛠 Built With

| Category | Technology |
|----------|------------|
| Programming | Python |
| Machine Learning | Scikit-learn |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Deployment | Streamlit |
| Development | Jupyter Notebook |

---

## 🎮 Use Cases

🏏 Live Match Win Prediction

📈 Cricket Analytics

🤖 Machine Learning Demonstration

📊 Sports Data Analysis

🎓 Educational Project

---

## 👨‍💻 Author

**Harshil Kothiya**

- GitHub: https://github.com/Harshilkothiya
- LinkedIn: https://www.linkedin.com/in/harshil-kothiya/