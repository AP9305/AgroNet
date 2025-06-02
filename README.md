# AGRONET
#  AgroNet 🌾

**AgroNet** is a Deep Learning-powered solution designed to recommend the most suitable crop and predict its estimated yield (in tonnes) based on the season, location, and available land size. Developed using **TensorFlow**, **Keras**, and **Streamlit**, AgroNet aims to empower farmers with accurate, data-driven insights to make informed agricultural decisions.

---

## 🚀 Features

- 📊 Intelligent **Crop Recommendation** based on key environmental factors  
- 🌾 Accurate **Yield Prediction** (in tonnes) for recommended crops  
- 🧠 Trained Deep Learning model using **TensorFlow** and **Keras**  
- 💻 User-friendly web interface with **Streamlit**  
- 📈 Interactive visualizations and outputs  

---

## 🛠️ Tech Stack

| Category     | Technologies |
|--------------|--------------|
| **Frontend** | Streamlit    |
| **Backend**  | Python       |
| **ML/DL**    | TensorFlow, Keras, Scikit-learn |
| **Data**     | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |

---

## 📥 Input Parameters

| Parameter   | Type     | Description                          |
|-------------|----------|--------------------------------------|
| `Season`    | String   | E.g., *Kharif*, *Rabi*, *Summer*     |
| `Location`  | String   | State or district name               |
| `Land Size` | Float    | Land area in hectares or acres       |

---

## 📤 Output

- ✅ Recommended **Crop Name**
- 📦 Predicted **Yield** (in tonnes)

---

## 🧪 How It Works

1. User provides **season**, **location**, and **land size** via the web UI  
2. Input is **preprocessed** and passed to the trained deep learning model  
3. The model returns the **best crop** and **estimated yield**  
4. Results are shown with optional visual feedback




