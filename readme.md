# 🧠 Tumor Detection Web App

This is a Python Flask-based web application that allows users to upload brain MRI scans and detect the presence of a tumor using a trained machine learning model.

the project should run in a venv via the command: python -m venv NameOfYourVenv

## 🚀 Features

- Upload MRI scan images (`.jpg`, `.png`)
- Predict whether a tumor is **Detected** or **Not Detected**
- Display the uploaded image and the result
- Clean and simple web interface with HTML templates

## 🧠 Tech Stack

- Python 🐍
- FastAPI (Web Framework)
- HTML5 (Templates)
- Trained ML Model (e.g., CNN)
- OpenCV or PIL for image processing

## 📂 Project Structure

Tumor_detection/

├── main.py              # FastAPi point entry

├── templates/

│   └── index.html       # Web interface

├── uploads/             # Uploaded images

├── .gitignore

└── README.md
