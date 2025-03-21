# 🚀 Founder-Investor Matching AI using Gemini API
<!-- [![Try on Hugging Face](https://img.shields.io/badge/-HuggingFace-FDEE21?style=for-the-badge&logo=HuggingFace&logoColor=black)](https://huggingface.co/spaces/smit-faldu/Audio_Translation)  -->
[![Open in Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)](https://colab.research.google.com/drive/17mLCRsrMzg8DUz3N9wptQ7JivSrx-aze?usp=sharing)

This project is an **AI-powered web application** that helps match startup founders with the most relevant investors based on industry, funding stage, cheque size, and location. It leverages **Google Gemini API** with **LangChain** and **FAISS vector search** to provide personalized **match scores (0-100)** for each investor.

🔹 **Frontend:** HTML, Tailwind CSS, JavaScript  
🔹 **Backend:** Flask, LangChain, Gemini API  
🔹 **Vector Search:** FAISS (for retrieving similar investors)  
🔹 **Deployment:** Google Colab with Ngrok  

---

## 📌 **Features**
✔ **User Inputs Founder Details (Industry, Stage, Funding, Country)**  
✔ **Finds the Best-Matching Investors Using AI**  
✔ **Assigns an Overall Match Score (0-100)**  
✔ **Breaks Down Compatibility in Key Categories (Industry, Stage, Location, etc.)**  
✔ **Provides a Short Explanation for the Match**  
✔ **Modern UI with Tailwind CSS**  
✔ **Handles Large Investor Datasets with FAISS**  

---

## 📌 **How It Works**
1. **User Inputs Founder Details** (Industry, Stage, Funding, Country).
2. **FAISS Vector Search** retrieves **top 5 most relevant investors**.
3. **Google Gemini API with LangChain** evaluates the alignment:
   - Assigns a **Match Score (0-100)**.
   - Breaks down the score into **Industry Match, Investment Stage, etc.**.
   - Provides a short **explanation** for the score.
4. **Sorted results are displayed** on the frontend with scores and reasoning.
5. **Ngrok exposes the Flask API** when running on Google Colab.

---

## 📌 **Tech Stack & Libraries Used**
### **Frontend**
- `HTML`, `CSS`, `Tailwind CSS` → UI design
- `JavaScript` → Handles API calls & displays results

### **Backend**
- `Flask` → Web framework for API
- `Flask-CORS` → Enable cross-origin requests
- `FAISS` → Vector search for retrieving best-matching investors
- `Google Generative AI` → Uses **Gemini API** for scoring matches
- `LangChain` → Handles structured AI prompting
- `Pandas` → Data processing for investor dataset
- `PyNgrok` → Exposes Flask API for Colab users

### **Deployment**
- `Ngrok` → Expose API on Google Colab

---

## 📌 **Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/smit-faldu/founder-investor-matching.git
cd founder-investor-matching
# Founder-Investor-Matching-AI-using-Gemini-API
