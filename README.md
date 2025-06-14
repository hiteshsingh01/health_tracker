# 🏃‍♂️ HealthTracker - Personalized Wellness Dashboard

**HealthTracker** is a dynamic and interactive Streamlit application designed to help users monitor and enhance their physical wellness through daily tracking, personalized feedback, and actionable health recommendations.

## 📸 Demo

> Insert a GIF or screenshot of your app here.

## 🚀 Features

* 🔢 **Calculate BMI and BMR** based on user profile
* 📊 **Track daily health data** – Steps, Water Intake, and Sleep
* 📈 **Visualize trends** with interactive graphs
* 📋 **Get personalized feedback** based on daily averages
* 🥗 **Receive full-day diet plans** tailored to BMI
* 🧘‍♂️ **Yoga and exercise recommendations** based on BMI category
* 🎨 Stylish, responsive layout with custom CSS

---

## 🛠️ Tech Stack

* **Frontend**: Streamlit
* **Backend/Data**: Pandas, Matplotlib
* **Design**: Custom HTML + CSS for theme and animations

---

## 🧑‍💻 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/hiteshsingh01/HealthTracker.git
cd HealthTracker
```

### 2. Create and activate a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
```

### 3. Install required packages

```bash
pip install -r requirements.txt
```

**Sample `requirements.txt`:**

```txt
streamlit
pandas
matplotlib
```

### 4. Run the Streamlit app

```bash
streamlit run app.py
```

> Replace `app.py` with your actual filename if different.

---

## 🖼️ App Layout Overview

### Sidebar:

* User inputs for weight, height, age, and gender
* Real-time BMI and BMR calculation

### Main Page:

* Daily data entry for steps, water, sleep
* Metrics display and data trends
* Personalized health advice
* Diet and fitness recommendations tailored to BMI

---

## 📁 File Structure

```
HealthTracker/
│
├── app.py                  # Main Streamlit app
├── requirements.txt        # Python dependencies
└── README.md               # You are here
```

---

## 📌 Future Enhancements

* ✅ Add authentication (login/signup)
* ✅ Store data in database or cloud (Firebase, MongoDB, etc.)
* ✅ Export health report as PDF
* ✅ Integrate with wearable APIs (Fitbit, Apple Health, etc.)

---

## 🧑‍🎓 Author

**Hitesh Singh**
🔗 [LinkedIn](https://linkedin.com/in/hiteshsingh01) | 📧 [Mail](hiteshsingh2k4@gmail.com)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).


