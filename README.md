🔐 Network Security Intrusion Detection System

An end-to-end Machine Learning–based Network Security system designed to detect malicious network traffic using a structured ML pipeline. The project follows industry-standard practices including data validation, transformation, model training, and API-based inference using FastAPI.

🚀 Project Overview

This project builds a Network Intrusion Detection System (IDS) that classifies network traffic as normal or malicious.
It implements a modular ML pipeline with artifact tracking, exception handling, logging, and scalable design.

Key goals:

Detect network intrusions accurately
Maintain clean, production-style ML architecture
Enable real-time predictions via REST API
🧠 Key Features
✅ Data Ingestion & Validation
✅ Data Transformation using KNN Imputer
✅ Model Training & Evaluation
✅ Artifact-based pipeline architecture
✅ Custom logging & exception handling
✅ FastAPI for real-time inference
✅ Modular, scalable, and production-ready design
🛠️ Tech Stack
Programming Language: Python
ML Libraries: NumPy, Pandas, Scikit-learn
Backend: FastAPI
Pipeline Design: Custom ML pipeline architecture
Utilities: Logging, Exception Handling
Deployment (Local): Uvicorn
📂 Project Structure
networksecurity/
│
├── components/
│   ├── data_ingestion.py
│   ├── data_validation.py
│   ├── data_transformation.py
│   ├── model_trainer.py
│
├── constant/
│   └── training_pipeline.py
│
├── entity/
│   ├── config_entity.py
│   └── artifact_entity.py
│
├── exception/
│   └── exception.py
│
├── logging/
│   └── logger.py
│
├── utils/
│   └── main_utils/
│
├── final_model/
│   └── preprocessor.pkl
│
├── app.py        # FastAPI app
├── main.py       # Pipeline trigger
└── README.md
⚙️ ML Pipeline Flow
Data Ingestion
Loads raw network traffic data
Data Validation
Schema validation
Data drift checks
Missing value checks
Data Transformation
Feature-target separation
KNN-based missing value imputation
Saving transformed datasets & preprocessing objects
Model Training
Trains classification model
Saves trained model artifacts
Inference
FastAPI serves predictions via REST endpoints
▶️ How to Run the Project Locally
1️⃣ Clone the Repository
git clone https://github.com/your-username/network-security-ml.git
cd network-security-ml
2️⃣ Create Virtual Environment
conda create -n network python=3.9 -y
conda activate network
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run Training Pipeline
python main.py
5️⃣ Start FastAPI Server
uvicorn app:app --reload
6️⃣ Open API Docs
http://127.0.0.1:8000/docs
📌 API Usage
Upload network traffic data
Get real-time intrusion prediction
Fully REST-compliant endpoints
📈 Learning Outcomes
Practical MLOps-style pipeline development
Real-world ML project structuring
FastAPI-based ML deployment
Clean coding with logging & exception handling
🙌 Acknowledgement

This project is inspired by and developed as part of Krish Naik’s Machine Learning & MLOps Udemy Course, adapted and extended for learning and portfolio purposes.

📬 Contact

If you have suggestions or want to collaborate, feel free to connect!
