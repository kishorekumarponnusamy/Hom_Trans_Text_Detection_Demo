# Homophobia and Transphobia Text Detection 🏳️‍🌈

A deep learning model to detect homophobia and transphobia in Tamil and Malayalam 
social media comments, with an interactive Streamlit web application.

---

## 📌 About the Project

This project detects homophobic and transphobic content in **Tamil** and **Malayalam** 
languages using pretrained multilingual BERT (mBERT). Built as part of the 
**LT-EDI@EACL 2024** shared task on Homophobia/Transphobia Detection in social media comments.

---

## ✨ Features

- 🔍 Detects homophobic and transphobic content in Tamil & Malayalam
- 🤖 Powered by pretrained **multilingual BERT (mBERT)**
- 🌐 Supports **code-mixed** social media text
- 🖥️ Interactive **Streamlit web app** for real-time classification
- 📊 Returns classification label with confidence score

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![mBERT](https://img.shields.io/badge/mBERT-0077B5?style=flat&logoColor=white)

---

## 📁 Project Structure
├── Code/
│   ├── model.py          # mBERT model training
│   ├── predict.py        # Inference script
│   └── preprocess.py     # Data preprocessing
├── Dataset/
│   └── data.csv          # Tamil & Malayalam dataset
├── Streamlit_app/
│   └── app.py            # Interactive web application
└── README.md

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/kishorekumarponnusamy/Hom_Trans_Text_Detection.git
cd Hom_Trans_Text_Detection
```

### 2. Install dependencies
```bash
pip install transformers torch streamlit pandas numpy
```

### 3. Run the Streamlit app
```bash
cd Streamlit_app
streamlit run app.py
```

---

## 🚀 Live Demo

<a href="https://homtranstextdetection-45jdwujrjqwbqrd3puw56v.streamlit.app/" target="_blank">
<img src="https://static.streamlit.io/badges/streamlit_badge_black_white.svg"/>
</a>

> 💡 Tip: Right-click the badge and select **"Open in new tab"** for best experience!

---

## 🙋 Author

**Kishore Kumar Ponnusamy**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kishore-kumar-ponnusamy-309037212/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=rUpbYvIAAAAJ&hl=en)
