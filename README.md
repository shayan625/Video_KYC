Online Video KYC (VeriFlow) 

📌 Overview
This project implements an AI-powered Video KYC (Know Your Customer) system, enabling secure and efficient identity verification through real-time video processing. The system leverages FastAPI for backend services and Streamlit for an interactive web interface, ensuring seamless user experience and compliance with security standards.

🚀 Features
✔️ Face Recognition – Verify user identity through AI-based face matching.
✔️ Liveness Detection – Prevent fraud using real-time movement detection.
✔️ FastAPI Backend – Handles authentication and video processing efficiently.
✔️ Streamlit Web App – Provides an intuitive interface for user interaction.
✔️ Real-Time Processing – Ensures quick and accurate verification.

🛠️ Tech Stack
Backend: FastAPI, Uvicorn

Frontend: Streamlit

Machine Learning: OpenCV, Deep Learning models

Database: MongoDB

Other Tools: PyTorch/TensorFlow 

⚡ Setup & Installation
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/shayan625/video-kyc.git
cd video-kyc
2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
pip install "fastapi[all]"
3️⃣ Running the Services
Backend (FastAPI Service)
bash
Copy
Edit
uvicorn main:app --reload
Frontend (Streamlit Web App)
bash
Copy
Edit
streamlit run webcam_streamlit.py
