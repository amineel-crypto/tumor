# 🧠 Tumor Detection Web App

This is a Python FastAPI-based web application that allows users to upload brain MRI scans and detect the presence of a tumor using a trained machine learning model.

the project should run in a venv via the command: python -m venv NameOfYourVenv

don't forget to activate the virtaul env with: NameOfYourVenv/Scripts/activate #in Windows

source myenv/bin/activate #in Linux

then install the requirements file via: pip install -r requirements

don't forget to run the web app with :

uvicorn main:app --reload

its nessecary to run the app in a verion python with 3.10.x

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
