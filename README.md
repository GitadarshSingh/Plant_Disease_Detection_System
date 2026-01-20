🌿 Plant Disease Detection System 🧠🌱

A deep learning–powered Plant Disease Detection System built using TensorFlow and Streamlit.
The application analyzes plant leaf images and classifies them into 38 disease and healthy categories.

🚀 Live Application (Streamlit Cloud)

🔗 https://plant-disease-detection-ml-app.streamlit.app

This is the hosted version of the project.
Anyone can test the model directly from the browser without local setup.

📸 Features

Upload plant leaf images (JPG / PNG)

Automatic disease classification

Supports 38 plant disease classes

Interactive Streamlit UI

Fast inference using a trained CNN model

🧠 Model Details

Framework: TensorFlow / Keras

Model Type: Convolutional Neural Network (CNN)

Input Image Size: 128 × 128

Dataset Size: ~87,000 images

Output Classes: 38 (Healthy + Diseased)

📂 Project Structure
Plant_Disease_Detection_System/
│
├── main.py                          # Streamlit application
├── requirements.txt                 # Project dependencies
├── trained_plant_disease_model.keras# Trained CNN model
├── home_page.jpeg                   # UI banner image
├── Train_plant_disease.ipynb        # Model training notebook
├── Test_plant_disease.ipynb         # Model testing notebook
├── training_hist.json               # Training history
├── train/                           # Training dataset (ignored)
├── valid/                           # Validation dataset (ignored)
├── test/                            # Test images (ignored)
└── .gitignore

⚙️ Installation & Local Setup
1️⃣ Clone the Repository
git clone https://github.com/GitadarshSingh/Plant_Disease_Detection_System.git
cd Plant_Disease_Detection_System

2️⃣ Create & Activate Conda Environment
conda create -n tensorflow python=3.10 -y
conda activate tensorflow

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Application
streamlit run main.py


The app will open at:

http://localhost:8501

🧪 Dataset Information

Dataset recreated using offline augmentation

Original dataset sourced from public plant disease datasets

Split ratio: 80% Training / 20% Validation

Includes leaf images of:

🍎 Apple
🍇 Grape
🌽 Corn
🍅 Tomato
🥔 Potato
🍓 Strawberry
🫑 Pepper
🥕 and more

🛑 Important Note

Large datasets and raw images are excluded from GitHub using .gitignore.
Only the trained model is included to allow direct inference and deployment.

📜 License

This project is intended for educational and academic use.

🌱 Empowering agriculture through AI 🤖🌾
