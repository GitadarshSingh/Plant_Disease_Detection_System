# 🌿 Plant Disease Detection System 🧠🌱

A deep learning–powered **Plant Disease Detection System** built using **TensorFlow** and **Streamlit**. This project detects plant leaf diseases from images and classifies them into **38 different categories** with high accuracy.

---

## 🚀 Live Application (Localhost)


🔗 https://plant-disease-detection-ml-app.streamlit.app
```

---

## 📸 Features

✅ Upload plant leaf images

✅ Automatic disease classification

✅ Supports **38 plant disease classes**

✅ Clean and interactive **Streamlit UI**

✅ Fast prediction using trained CNN model

---

## 🧠 Model Details

* Framework: **TensorFlow / Keras**
* Model Type: **Convolutional Neural Network (CNN)**
* Input Image Size: **128 × 128**
* Dataset Size: ~**87,000 images**
* Classes: **38 (Healthy + Diseased)**

---

## 📂 Project Structure

```
Plant_Disease_Detection_System/
│
├── main.py                     # Streamlit application
├── requirements.txt            # Project dependencies
├── trained_plant_disease_model.keras   # Trained CNN model
├── home_page.jpeg              # UI banner image
├── Train_plant_disease.ipynb   # Model training notebook
├── Test_plant_disease.ipynb    # Model testing notebook
├── training_hist.json          # Training history
├── train/                      # Training dataset (ignored in GitHub)
├── valid/                      # Validation dataset (ignored in GitHub)
├── test/                       # Test images (ignored in GitHub)
└── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/GitadarshSingh/Plant_Disease_Detection_System.git
cd Plant_Disease_Detection_System
```

### 2️⃣ Create & Activate Conda Environment

```bash
conda create -n tensorflow python=3.10 -y
conda activate tensorflow
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```bash
streamlit run main.py
```

---

## 🧪 Dataset Information

* Dataset recreated using **offline augmentation**
* Original dataset sourced from public plant disease datasets
* Split ratio: **80% Training / 20% Validation**

Dataset contains images of:

* 🍎 Apple
* 🍇 Grape
* 🌽 Corn
* 🍅 Tomato
* 🥔 Potato
* 🍓 Strawberry
* 🫑 Pepper
* 🥕 And more...

---

## 🛑 Important Note

⚠️ Large datasets and trained model files are **excluded** from GitHub using `.gitignore` to keep the repository clean and lightweight.

---





## ⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork it
📢 Share it

---

## 📜 License

This project is for **educational and academic purposes**.

---

🌱 *Empowering agriculture through AI* 🤖🌾
