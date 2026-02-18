# GreenClassify 🥦 - Vegetable Classification System
GreenClassify is an AI-powered web application designed to automatically identify and classify vegetables from uploaded images using Deep Learning.

# 🌟 Project Overview
Model Architecture: MobileNetV2 (Transfer Learning).
Classes: 15 categories (Bean, Brinjal, Tomato, Carrot, etc.).
Backend: Flask (Python).
Frontend: Responsive HTML5/CSS3 UI.

# 📸 Screenshots
# Home Page
<img width="1914" height="956" alt="image" src="https://github.com/user-attachments/assets/91ebb296-8e05-496e-ab0b-ef583596c39e" />

# About Section
<img width="1919" height="953" alt="image" src="https://github.com/user-attachments/assets/8667d3a6-33e6-401d-b6ea-1783404ee306" />

# Prediction Result
<img width="1914" height="957" alt="image" src="https://github.com/user-attachments/assets/471757e1-3d2b-485b-9190-714f452e2026" />

# 🚀 How to Run Locally
Clone the repository: ```bash git clone https://github.com/SamNeuroBytes/vegetable-classification.git cd vegetable-classification

Install dependencies:

Bash pip install -r requirements.txt

Run the Flask application:

Bash python train_model.py (Note: Ensure your model file vegetable_model.h5 is in the root directory)

Access in Browser: Go to http://127.0.0.1:5000/

# 📂 Project Structure static/ - Contains CSS and UI images.

templates/ - Contains HTML views.

screenshots/ - App demo images.

vegetable_model.h5 - The trained CNN model.

train_model.py - Flask server and inference logic.
