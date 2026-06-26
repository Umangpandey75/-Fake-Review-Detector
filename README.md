<!-- ═══════════ ANIMATED HEADER ═══════════ -->

# 🕵️‍♂️ Fake Review Detector

<div align="center">
<!-- ═══════════ TYPING ANIMATION ═══════════ -->

<br/>

<!-- ═══════════ BADGES ═══════════ -->
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
&nbsp;
![Machine Learning](https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge&logo=scikitlearn&logoColor=white)
&nbsp;
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
&nbsp;
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

<br/>

[![Streamlit App](https://img.shields.io/badge/Live_Demo-Streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://fakereviewdetectorv1.streamlit.app/)
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Umangpandey75/Fake-Review-Detector?style=flat-square&color=6AD3F7&label=Repo+Size)
&nbsp;
![Last Commit](https://img.shields.io/github/last-commit/Umangpandey75/Fake-Review-Detector?style=flat-square&color=58A6FF&label=Last+Commit)
&nbsp;
![License](https://img.shields.io/github/license/Umangpandey75/Fake-Review-Detector?style=flat-square&color=27AE60)
&nbsp;
![Stars](https://img.shields.io/github/stars/Umangpandey75/Fake-Review-Detector?style=social)
&nbsp;
![Forks](https://img.shields.io/github/forks/Umangpandey75/Fake-Review-Detector?style=social)

</div>

---

## 🌊 What is Fake Review Detector?

**Fake Review Detector** is a Machine Learning application designed to identify fraudulent online consumer reviews. It utilizes Natural Language Processing (NLP) to distinguish between genuine and fake reviews using an Amazon dataset.

Whether you're safeguarding business credibility or protecting customers from review fraud — **Fake Review Detector** has you covered.

> *"Analyze. Detect. Protect. — Safeguarding the authenticity of online feedback."*

### ✨ Core Philosophy
- 🎯 **Accuracy first** — multiple classifiers trained for high precision
- ⚡ **Speed** — efficient deployment via Streamlit
- 🔌 **Accessibility** — simple user interface for instant text classification

---

## 🚀 Features

<div align="center">

| Feature | Description | Status |
|---------|-------------|--------|
| 🕵️ **Fraud Detection** | Identifies fake reviews vs. real reviews | ✅ Active |
| 🤖 **Supervised Learning** | Utilizes Logistic Regression (85% Accuracy) | ✅ Active |
| 💡 **Text Preprocessing** | Advanced NLP pipelines with TextBlob & NLTK | ✅ Active |
| 🌐 **Web Frontend Interface** | Interactive Streamlit application | ✅ Active |
| 📓 **Jupyter Notebooks** | Full EDA and model training pipelines provided | ✅ Active |

</div>

---

## 🛠️ Tech Stack

<div align="center">

### 🧠 AI / Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-22522?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### 🌐 Frontend
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### 🔧 Tools & DevOps
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 🗂️ Project Structure

```
📦 Fake-Review-Detector/
├── 📓 1.Inital_Data_Exploration (Notebook One).ipynb        ← Data analysis
├── 📓 2.Text_EDA_&_PreProcessing (Notebook Two).ipynb       ← Text processing
├── 📓 3.Model Implementation and Evaluation (Notebook Three).ipynb ← ML Modeling
├── 📄 4.Deployment.py                                      ← Streamlit App
├── 📁 data and pickle files/                               ← Models & Data
└── 📖 README.md                                            ← Project documentation
```

---

## ⚙️ Architecture Overview

```mermaid
%%{init: {
  "theme": "base",
  "themeVariables": {
    "background":         "#0a0e1a",
    "primaryColor":       "#1a1a2e",
    "primaryTextColor":   "#6AD3F7",
    "primaryBorderColor": "#58A6FF",
    "lineColor":          "#58A6FF",
    "secondaryColor":     "#16213e",
    "tertiaryColor":      "#0f3460",
    "fontFamily":         "Fira Code, monospace"
  }
}}%%
flowchart LR
    A["📝 User Review Input"] --> B["Streamlit UI\n4.Deployment.py"]
    B --> C{"NLP Preprocessing\nNLTK / TextBlob"}
    C --> D["Count Vectorizer"]
    D --> E["🤖 Logistic Regression Model"]
    E --> F["📊 Prediction"]
    F --> G["✅ Genuine / ❌ Fake"]
```

---

## 🚦 Quick Start

### Prerequisites

```bash
# Make sure you have Python installed
python --version

# Clone the repository
git clone https://github.com/Umangpandey75/Fake-Review-Detector.git
cd Fake-Review-Detector

# Install required packages
pip install -r requirements.txt
```

### 🖥️ Run the Web Interface

```bash
# Start the Streamlit application
streamlit run 4.Deployment.py
```

### 📓 Explore the AI Pipeline (Jupyter Notebooks)

```bash
# Start Jupyter Notebook
jupyter notebook

# Follow the notebooks in order:
# 1 -> 2 -> 3
```

---

## 🎮 How to Use

<div align="center">

```
  Step 1             Step 2              Step 3              Step 4
     🌐                 📝                  🧠                  📊
Open Browser  →  Enter Review    →  Click 'Check'  →  View Prediction
 Streamlit UI      "Great product!"    Processing      Genuine / Fake
```

</div>

### 📊 Model Performance

| Metric | Score |
|--------|-------|
| **Accuracy** | 85% |
| **Precision** | 80% |
| **Recall** | 92% |
| **F-1 Score** | 85% |

---

## 📸 Interface Preview

<div align="center">

> 🌙 **Minimalist Streamlit UI** — simple, clean, and focused

```
┌──────────────────────────────────────────┐
│                                          │
│  Fraud Detection in Online Consumer...   │
│                                          │
│   [+] Abstract                           │
│   [+] Related Links                      │
│                                          │
│  Fake Review Classifier                  │
│  ┌────────────────────────────────────┐  │
│  │ Enter Review:                      │  │
│  │ "This product broke on day one."   │  │
│  └────────────────────────────────────┘  │
│                                          │
│          [   Check   ]                   │
│                                          │
│   ✅ The review entered is Legitimate.   │
│                                          │
└──────────────────────────────────────────┘
```

</div>

---

## 🔬 NLP Pipeline

The core text preprocessing lives inside the app:

```python
import streamlit as st
import pickle

# 1. Load trained models
model = pickle.load(open('data and pickle files/best_model.pkl','rb')) 
vectorizer = pickle.load(open('data and pickle files/count_vectorizer.pkl','rb')) 

# 2. Text preprocessing (Spelling correct, stemming, stopwords)
cleaned_review = text_preprocessing(text)

# 3. Vectorization and Classification
process = vectorizer.transform([cleaned_review]).toarray()
prediction = model.predict(process)

if prediction == 'True':
    st.success("The review entered is Legitimate.")
else:
    st.error("The review entered is Fraudulent.")
```

---

## 🔮 Future Enhancements

- 🌍 **Diversified Dataset:** Expand beyond UK grocery reviews to multiple regions and product categories.
- 📉 **Bias Reduction:** Address the predominantly positive sentiment bias in the current dataset.
- 🧠 **Standardized Benchmark:** Contribute to developing a standardized dataset for detecting fraudulent reviews, similar to modern email spam detection systems.

---

## 🤝 Contributing

Contributions are what make the open-source community amazing! Here's how you can help:

```bash
# 1. Fork the repository on GitHub
# 2. Create your feature branch
git checkout -b feature/AmazingFeature

# 3. Commit your changes
git commit -m '✨ Add AmazingFeature'

# 4. Push to the branch
git push origin feature/AmazingFeature

# 5. Open a Pull Request 🎉
```

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 👨‍💻 Author

<div align="center">

### **Umang Pandey**
*Python Developer · Data Analyst · ML Engineer*

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:umangpandey.co@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/umang-pandey-01b486273)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Umangpandey75)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-6AD3F7?style=for-the-badge&logo=vercel&logoColor=black)](https://umangpandey.vercel.app)

*"Query the data. Build the insight. Ship the WOW. ✨"*

</div>

---

## ⭐ Show Your Support

If **Fake Review Detector** helped you, please give it a ⭐ — it means the world!

<div align="center">

[![Star this repo](https://img.shields.io/badge/⭐_Star_this_repo-FFD700?style=for-the-badge)](https://github.com/Umangpandey75/Fake-Review-Detector/stargazers)
&nbsp;
[![Fork this repo](https://img.shields.io/badge/🍴_Fork_it-58A6FF?style=for-the-badge)](https://github.com/Umangpandey75/Fake-Review-Detector/fork)
&nbsp;
[![Share on Twitter](https://img.shields.io/badge/Share_on_Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/intent/tweet?text=Check+out+Fake-Review-Detector+by+%40Umangpandey75!+%F0%9F%95%B5%EF%B8%8F%E2%80%8D%E2%99%82%EF%B8%8F%F0%9F%A4%96&url=https://github.com/Umangpandey75/Fake-Review-Detector)

</div>
---
<!-- ═══════════ FOOTER WAVE ═══════════ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,40:16213e,70:1a1a2e,100:0d1117&height=120&section=footer" width="100%"/>

<div align="center">

*Made with ❤️ by [Umang Pandey](https://github.com/Umangpandey75) · © 2026 Fake Review Detector*

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Umangpandey75.Fake-Review-Detector&left_color=1F6FEB&right_color=6AD3F7&left_text=Visitors)
</div>
