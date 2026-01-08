🔐 AI-ML Crypto Primitive Identification in Firmware
📌 Overview

AI-ML Crypto Primitive Identification in Firmware is a project focused on automatically identifying cryptographic primitives embedded inside firmware binaries using Artificial Intelligence and Machine Learning techniques.

The system is designed to assist in firmware security analysis, malware detection, and reverse engineering by detecting cryptographic algorithms such as AES, SHA, etc., without requiring full manual analysis.

🎯 Problem Statement

Firmware often contains cryptographic implementations that are:

Obfuscated

Hard to detect manually

Embedded deep inside binaries

Traditional signature-based methods fail against modern firmware.
This project uses ML models and graph-based analysis to accurately detect cryptographic primitives.

🚀 Features

✅ Automatic crypto primitive detection

✅ Supports firmware binary analysis

✅ ML-based classification

✅ Graph-based feature extraction

✅ Modular & scalable architecture

✅ Web interface support (HTML/CSS/JS)

✅ Secure email configuration support

🧠 Technologies Used
🔹 Programming & Scripting

Python

JavaScript

HTML / CSS

🔹 AI / ML

Machine Learning models (PyTorch)

Graph-based data representation

Feature extraction & classification

🔹 Tools & Libraries

PyTorch

NetworkX

NumPy

Flask (API server)

Git & GitHub

🗂️ Project Structure
AI-ML_Crypto_Primitive_Identification_in_Firmware/
│
├── ByteMeX_PS_ID_25239/
│   ├── data/                     # Dataset files
│   ├── loaders/                  # Data loading modules
│   ├── models/                   # ML models
│   ├── preprocessing/            # Preprocessing scripts
│   ├── api_server.py             # Backend API
│   ├── classify.py               # Classification logic
│   ├── train.py                  # Model training
│   ├── evaluate.py               # Model evaluation
│   ├── predict_crypto.py         # Prediction script
│   ├── utils.py                  # Utility functions
│
├── .gitignore
├── requirements.txt
├── start_server.bat
├── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/ShryCreates/AI-ML_Crypto_Primitive_Identification_in_Firmware.git
cd AI-ML_Crypto_Primitive_Identification_in_Firmware

2️⃣ Create Virtual Environment
python -m venv venv
venv\Scripts\activate   # Windows

3️⃣ Install Dependencies
pip install -r requirements.txt

▶️ Running the Project
🔹 Start Backend Server
python api_server.py


or

start_server.bat

🔹 Run Model Prediction
python predict_crypto.py

📊 Dataset

Graph-based crypto datasets

AES, SHA and other cryptographic algorithm samples

Preprocessed for ML training and inference

🔐 Use Cases

Firmware malware analysis

Cybersecurity research

Reverse engineering automation

Embedded system security audits

Academic & SIH hackathon research

👩‍💻 Author

Shreya Kumari (ShryCreates)
GitHub: https://github.com/ShryCreates

📜 License

This project is developed for academic and research purposes.
All rights reserved © 2026.

⭐ Acknowledgements

Smart India Hackathon (SIH) 2025

Open-source ML & security research community

Mentors and collaborators