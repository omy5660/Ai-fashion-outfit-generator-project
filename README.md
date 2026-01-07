# 👗 AI-Driven Cross-Brand Fashion Fit & Outfit Recommendation System

Personalized, cross-brand outfit and size-fit recommendations powered by **Generative AI** and delivered through an interactive **Streamlit dashboard**.

---

## 📌 Project Overview

This project presents a **Generative AI–powered fashion recommendation system** designed to solve real-world challenges in online fashion retail, especially **size inconsistency across brands**.

The application guides users through a structured onboarding flow, analyzes body measurements and preferences, and delivers **personalized outfit recommendations**, **cross-brand size suggestions**, and **AI-generated outfit visuals**.

It is suitable for:

* Academic evaluation (MCA / AI & DS projects)
* Portfolio showcase (Data Science / GenAI roles)
* Fashion-tech proof-of-concept applications

---

## ✨ Key Features

* 👤 Guided multi-step user onboarding
* 📏 Cross-brand size & fit intelligence
* 👗 AI-generated outfit descriptions
* 🎨 AI-generated outfit images
* 📊 Interactive visual analytics dashboard
* 🧠 Occasion & weather-aware recommendations
* 🔐 Privacy-first, session-based personalization

---

## 🧠 System Workflow

1. User logs in or selects demo mode
2. Step-by-step onboarding collects:

   * Personal details
   * Body measurements
   * Style preferences
   * Preferred brands
   * Occasion & weather context
3. System computes **cross-brand size mapping**
4. Generative AI produces:

   * Outfit description (text)
   * Outfit visualization (image)
5. Results are displayed in a multi-tab Streamlit dashboard

---

## 🖥️ Application Architecture

```
├── app.py                 # Main Streamlit application
├── utils/
│   ├── size_mapper.py     # Cross-brand size logic
│   ├── prompt_engine.py   # LLM prompt construction
│   └── image_gen.py       # AI image generation
├── data/
│   └── brand_sizes.csv    # Brand-specific size charts
├── ss_fashionapp/         # Application screenshots
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Application

### ✅ Prerequisites

* Python **3.8+**
* Active internet connection
* OpenAI API Key

### 📦 Install Dependencies

```bash
pip install -r requirements.txt
```

*or*

```bash
pip install streamlit openai pillow pandas plotly
```

### ▶️ Run the App

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 🧠 Technologies Used

| Component        | Technology              |
| ---------------- | ----------------------- |
| Frontend         | Streamlit               |
| Language         | Python                  |
| LLM (Text)       | GPT-4o-mini             |
| LLM (Image)      | GPT Image Model         |
| Visualization    | Plotly                  |
| State Management | Streamlit Session State |

---

## 🧩 Functional Modules

### 👤 User Onboarding

* Multi-step guided form
* Personal details, measurements, styles & brands

### 📏 Cross-Brand Size Intelligence

* Brand-specific size charts
* Automatic size mapping
* Visual size comparison (charts & tables)

### 👗 Generative AI Outfit Engine

* Prompt-driven outfit generation
* Occasion & weather-aware styling
* AI-generated outfit images

### 📊 Interactive Dashboard Tabs

* Quick Outfit Generator
* Outfit History
* Brand Size Table
* Size Comparison Charts
* User Profile Viewer

---

## 🖼️ Application Screenshots

### 🏠 Home & User Input Dashboard

<img src="ss_fashionapp/ss_fashionapp/s_fashionapp/Screenshot 2025-12-01 160625.png" width="900" />

### 👗 Outfit Recommendation Results

<img src="ss_fashionapp/ss_fashionapp/Screenshot 2025-12-01 161303.png" width="900" />

### 📊 Brand Comparison & Fit Insights

<img src="ss_fashionapp/ss_fashionapp/Screenshot 2025-12-01 160756.png" width="900" />
<img src="ss_fashionapp/ss_fashionapp/Screenshot 2025-12-01 160809.png" width="900" />
<img src="ss_fashionapp/ss_fashionapp/Screenshot 2025-12-01 160858.png" width="900" />
<img src="ss_fashionapp/ss_fashionapp/Screenshot 2025-12-01 160921.png" width="900" />

### ⚙️ Additional UI Flow

<img src="ss_fashionapp/ss_fashionapp/Screenshot 2025-12-01 160947.png" width="900" />
<img src="ss_fashionapp/ss_fashionapp/Screenshot 2025-12-01 161212.png" width="900" />

---

## 🔐 Privacy & Ethics

* No permanent user data storage
* Session-based personalization only
* API keys managed locally
* Designed for non-sensitive fashion use cases

---

## 🌱 Future Enhancements

* Image-based user input for outfit matching
* ML-based body measurement prediction
* User accounts & cloud storage
* E-commerce platform integration
* Fashion trend & seasonal analytics

---

## 👨‍💻 Author

**OM Arun Yadav**
MCA Student | AI & Data Science Enthusiast

---

⭐ If you find this project useful, please consider **starring the repository** to support the work!
