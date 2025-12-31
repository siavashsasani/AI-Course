# Group 30
# 🏠 Tehran Housing Price Analyzer

**Course Project – Artificial Intelligence / Data Analysis**

A desktop application for analyzing and estimating housing prices in Tehran using real housing data and similarity-based filtering.

---

## 📌 Project Information

- **Project Title:** Tehran Housing Price Analyzer
- **Team Name:** AI Students Lab
- **Project Topic:** Housing Price Analysis & Estimation
- **Programming Language:** Python
- **GUI Framework:** Tkinter
- **Data Analysis:** Pandas

---

## 👥 Team Members

- مهدی پور  
- شمسایی  
- محمدنژاد  
-  ساسانی  

---

## 🎯 Project Objective

The goal of this project is to analyze Tehran housing market data and estimate property prices based on **similar listings** using the following criteria:

- Neighborhood
- Area (±10 square meters)
- Building age (±5 years)
- Number of rooms
- Parking availability

The application provides:
- Average price
- Minimum and maximum price
- Number of similar listings
- Sample similar properties

---

## 🧠 How It Works

1. User selects property features via a graphical interface.
2. The program filters similar properties from the dataset.
3. Statistical analysis is performed on filtered data.
4. Results are displayed in a readable GUI with tables and metrics.

Similarity score is calculated using:


---

## 🖥️ Application Features

- Modern dark-themed GUI
- Neighborhood dropdown selection
- Smart similarity filtering
- Price formatting in **Toman**
- Statistical summary (Average / Min / Max)
- Display of top 20 similar listings
- Error handling and empty-result feedback

---

## 📊 Dataset

- **File name:** `tehran_housing.csv`
- **Required Columns:**
  - `neighborhood`
  - `area`
  - `rooms`
  - `age`
  - `parking`
  - `price`

> ⚠️ Dataset must be placed in the same directory as the Python file.

---

## ▶️ How to Run the Project

### 1️⃣ Install requirements
```bash
pip install pandas

python تحلیل‌گر مسکن.ipynb

Project Structure
Tehran-Housing-Analyzer/
│
├── main.py
├── tehran_housing.csv
├── README.md
└── screenshots/
<img width="1918" height="1014" alt="image" src="https://github.com/user-attachments/assets/80865a0f-55cf-4b49-94ab-2ff572205369" />

🏁 Conclusion

This project demonstrates the practical use of data analysis and GUI development in Python to solve a real-world problem. It provides an interactive and user-friendly way to analyze housing prices using similarity-based logic.


Developed by AI Students Lab
