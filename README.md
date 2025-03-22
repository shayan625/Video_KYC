# VeriFlow (AI driven Video KYC)   

## 📌 Overview  
This project implements an **AI-powered Video KYC (Know Your Customer) system**, enabling secure and efficient identity verification through real-time video processing. The system leverages **FastAPI for backend services** and **Streamlit for an interactive web interface**, ensuring seamless user experience and compliance with security standards.  

## 🚀 Features  
✔️ **Face Recognition** – Verify user identity through AI-based face matching.  
✔️ **Liveness Detection** – Prevent fraud using real-time movement detection.  
✔️ **OCR Verification** – Extract and validate identity details from official documents.  
✔️ **FastAPI Backend** – Handles authentication, video processing, and OCR verification.  
✔️ **Streamlit Web App** – Provides an intuitive interface for user interaction.  
✔️ **Real-Time Processing** – Ensures quick and accurate verification.  

## 🛠️ Tech Stack  
- **Backend:** FastAPI, Uvicorn  
- **Frontend:** Streamlit  
- **Machine Learning:** OpenCV, Deep Learning models  
- **Database:** MongoDB  
- **Other Tools:** PyTorch  

## ⚡ Setup & Installation  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/shayan625/video-kyc.git
cd video-kyc
```

2️⃣ Install Dependencies :

Run the following command to install all required dependencies:
```bash
pip install -r requirements.txt
pip install "fastapi[all]"
pip install pytesseract easyocr
```

3️⃣ Running the Services :

Start Backend (FastAPI Service)
```bash
uvicorn main:app --reload
```
This will launch the FastAPI server, making APIs available at http://127.0.0.1:8000.

Start Frontend (Streamlit Web App)
```bash
streamlit run webcam_streamlit.py
```
This will open the Streamlit interface in the browser.
