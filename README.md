# 🌍 Air Quality Prediction & Monitoring (Pune)

A Streamlit-based web application that predicts **Air Quality Index (AQI)** for Pune city using machine learning. The project uses live/simulated pollutant data, provides region-wise AQI visualization, health recommendations, and forecasts pollutant trends.  

---

## 🚀 Features

- 📡 **Live Data Fetching** from APIs (IQAir / CPCB) or manual pollutant entry.  
- 🤖 **Machine Learning Model** (Random Forest) trained on historical AQI dataset (`pune_air_quality.csv`).  
- 🧮 **AQI Prediction** for PM2.5 using pollutant inputs (`pm10`, `no2`, `so2`, `co`, `o3`).  
- 📊 **Interactive Dashboard** built with Streamlit.  
- 🩺 **Health Tips** based on AQI levels.  
- 📈 **PM2.5 Forecasting** (next 3 days).  
- 🌐 **Region-wise Comparison** of AQI across Pune.  
- 🎨 **Custom UI** with animations, color-coded AQI, and professional styling.  

---

## 📂 Project Structure

```
Air-Quality-Prediction/
│── app.py                 # Main Streamlit app
│── model.pkl              # Trained ML model
│── pune_air_quality.csv   # Historical dataset
│── requirements.txt       # Dependencies
│── README.md              # Project documentation
│── notebooks/
│    └── ML hackethon 6.0.ipynb  # Model training notebook
│── assets/
     └── logo.png          # (Optional) Project logo/animations
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/air-quality-prediction.git
   cd air-quality-prediction
   ```

2. **Create virtual environment (recommended)**  
   ```bash
   python -m venv venv
   source venv/bin/activate   # (Linux/Mac)
   venv\Scripts\activate      # (Windows)
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Streamlit app**  
   ```bash
   streamlit run app.py
   ```

---

## 📊 Dataset

- **Source:** Pune Air Quality Dataset (`pune_air_quality.csv`)  
- **Features:**  
  - `pm10`, `no2`, `so2`, `co`, `o3` → pollutants  
  - `pm2.5` → target AQI parameter  
- **Size:** ~ (adjust as per your dataset)  

---

## 🧠 Model

- Algorithm: **Random Forest Regressor**  
- Training Notebook: `ML hackethon 6.0.ipynb`  
- Saved Model: `model.pkl`  

---

## 🎨 UI Screenshots

(Add screenshots of your dashboard here for better presentation)

---

## 🔮 Future Enhancements

- ✅ Add more cities & regions.  
- ✅ Integrate official CPCB API.  
- ✅ Deploy on **Streamlit Cloud / Heroku / AWS**.  
- ✅ Add AQI-based alerts/notifications.  

---

## 🤝 Contributing

Contributions are welcome!  
1. Fork the repo  
2. Create a new branch (`feature-branch`)  
3. Commit changes & push  
4. Open a Pull Request  

---

## 📜 License

This project is licensed under the MIT License. See `LICENSE` for details.  

---

## 👨‍💻 Author

- **Piyush Balode** – MSc Data Science Student, Fergusson College, Pune  
- 📧 [Your Email]  
- 🔗 [LinkedIn / Portfolio link]  
