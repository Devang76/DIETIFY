
# Dietify 🍽️ – AI Based Diet & Nutrition Consultation App

## 📌 Overview

**Dietify** is an AI-powered mobile application designed to offer real-time, personalized dietary and fitness consultation. It helps users make smarter health choices by generating adaptive meal plans, tracking nutrition and hydration, and delivering intelligent, interactive recommendations—all based on individual profiles.

This project was developed as the final-year B.Tech capstone by students of the **Artificial Intelligence & Data Science** department at **K.J. Somaiya Institute of Technology**, Mumbai.

---

## 🎯 Features

* 📊 **Personalized Diet Plans** using AI (BMR, TDEE, BMI analysis)
* 📷 **Barcode-based Food Logging** with USDA/Open Food Facts integration
* 🧠 **AI Chatbot** powered by Gemini LLM for interactive diet queries
* 📈 **Real-time Progress Tracking** (nutrition, weight, goals)
* 🥗 **Diverse Diet Support** (Vegan, Keto, Gluten-Free, Diabetic-friendly)
* 💬 **Community Forum** for sharing recipes, challenges & tips
* 📉 **Deficiency Detection** and goal-based dietary nudging
* 🔐 **GDPR-Compliant** data security and privacy architecture

---

## 🛠️ Tech Stack

| Layer         | Technology Used                                   |
| ------------- | ------------------------------------------------- |
| **Frontend**  | Flutter (Dart)                                    |
| **Backend**   | Django (Python) + Django REST Framework           |
| **Database**  | SQLite (dev) → PostgreSQL (prod)                  |
| **AI Models** | Gemini LLM, Scikit-learn, planned TensorFlow Lite |
| **Cloud**     | AWS (S3, EC2, RDS) – planned integration          |
| **Analytics** | AWS SageMaker – predictive models (future scope)  |

---

## 🚀 Getting Started

### 📋 Prerequisites

* Flutter SDK (v3.10.5 or later)
* Python 3.11
* Android Studio / Xcode
* Django 4.2
* Node.js (for any frontend testing)

### 🔧 Installation Steps

```bash
# Clone the repository
git clone https://github.com/your-username/dietify.git
cd dietify

# Frontend Setup
cd mobile_app/
flutter pub get
flutter run

# Backend Setup
cd backend/
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py runserver
```

### 📁 Environment Variables

Create a `.env` file in the `backend/` directory with:

```env
SECRET_KEY=your_django_secret_key
DEBUG=True
ALLOWED_HOSTS=127.0.0.1,localhost
```

---

## 📸 Screenshots

| Dashboard                            | Food Logger                    | AI Chatbot                       |
| ------------------------------------ | ------------------------------ | -------------------------------- |
| ![Dashboard](docs/img/dashboard.png) | ![Logger](docs/img/logger.png) | ![Chatbot](docs/img/chatbot.png) |

---

## 📈 Evaluation Metrics

| Metric                | Benchmark |
| --------------------- | --------- |
| SUS (Usability Score) | 84/100    |
| API Response Time     | < 800ms   |
| Goal Achievement Rate | ≥ 65%     |
| Diet Adherence Rate   | > 70%     |

---

## 🔐 Security & Compliance

* Encrypted user data storage
* GDPR compliant architecture
* Role-based access controls

---

## 🧪 Future Scope

* Integration with Wearables & IoT (Fitbit, Google Fit)
* Predictive Analytics with LSTM & AWS SageMaker
* Food image recognition via CNN
* Deep Learning for advanced personalization
* Integration with EHR & healthcare providers
* Multi-language & accessibility support
* Gamified challenges, badges, habit-loop design

---

## 👨‍💻 Authors

* [Devang Mestry](https://github.com/devangmestry)
* [Vedant Sawant](https://github.com/vedantsawant)
* [Aasttha Bhatt](https://github.com/aasthabhatt)

Project Guided by: **Dr. Vaishali Wadhe**

---

## 📜 License

This project is licensed under the **MIT License** 

---

## 📚 References

Research references and sources used in the project are listed in the `references.md` file or inside the final [PBL Report PDF](Dietify_PBL_Report.pdf).

---

