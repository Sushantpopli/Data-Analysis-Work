# 🚗 Automobile Sales Statistics Dashboard

This project is an **interactive dashboard** built using **Dash, Plotly, and Pandas** to analyze historical automobile sales data.  
It provides insights into **yearly trends** and **recession period statistics** with dynamic charts.

---

## 📊 Features
- **Yearly Statistics**:  
  - Average yearly automobile sales  
  - Monthly sales trends  
  - Vehicle type sales distribution  
  - Advertisement expenditure breakdown  

- **Recession Period Statistics**:  
  - Sales trends during recession years  
  - Average sales by vehicle type  
  - Advertisement expenditure share by vehicle type  
  - Impact of unemployment rate on vehicle sales  

---

## 🛠️ Tech Stack
- Dash  
- Plotly  
- Pandas  
- Gunicorn  

---

## 🚀 Deployment
This dashboard is hosted on **Render**.  
👉 [Live Demo](https://your-app-name.onrender.com)  

---

## 📂 Project Structure
```plaintext
automobile-sales-dashboard/
│
├── app.py                # Main application
├── requirements.txt       # Dependencies
├── Procfile              # For deployment
├── README.md              # Documentation
└── data/
    └── historical_automobile_sales.csv  # Local dataset
```

## ⚙️ Setup Instructions

### Clone the repository:
```
git clone https://github.com/your-username/automobile-sales-dashboard.git
cd automobile-sales-dashboard
```

### Run the app locally:

```
python app.py
```


Visit http://127.0.0.1:8050/ in your browser.

📈 Dataset

The dataset used is included in the data/ folder:
```
data/historical_automobile_sales.csv
```