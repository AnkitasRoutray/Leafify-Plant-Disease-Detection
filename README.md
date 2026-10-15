# 🌿 Leafify – AI-Based Plant Disease Detection

Leafify is an AI-powered web application that helps identify plant diseases
from leaf images using deep learning.

The project combines a React frontend, a Python backend, and a trained
deep-learning model to analyze uploaded leaf images and assist in plant
disease identification.

## 🎯 Project Objective

The objective of Leafify is to make plant disease identification easier
by using artificial intelligence and image classification.

The application allows users to provide leaf images for analysis and
receive disease predictions from the trained model.

## ✨ Features

- 🌱 AI-based plant disease detection
- 📷 Leaf image input for analysis
- 🧠 Deep-learning-based image classification
- ⚛️ Interactive React user interface
- 🐍 Python backend using FastAPI
- 🔍 Model-based disease prediction

## 🛠️ Technologies Used

### Frontend
- React.js
- Vite
- Tailwind CSS
- JavaScript

### Backend
- Python
- FastAPI

### Machine Learning
- PyTorch
- Deep Learning
- Image Classification
- Image Preprocessing

## 📁 Project Structure

```text
Leafify-Plant-Disease-Detection/
│
├── backend/
│   ├── main.py
│   ├── fast_plant_model.pth
│   ├── leafify_model_train.py
│   └── requirements.txt
│
├── leafify frontend/
│   └── React frontend files
│
├── leafify_ml_part/
│   └── Machine learning-related files
│
├── .gitignore
└── README.md
```

## ⚙️ How It Works

1. The user provides a plant leaf image.
2. The frontend sends the image to the backend for analysis.
3. The backend preprocesses the image as required by the model.
4. The trained deep-learning model analyzes the image.
5. The application returns the predicted plant disease class.

## 🚀 Getting Started

### Prerequisites

Install the following software:

- Python
- Node.js and npm
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/AnkitasRoutray/Leafify-Plant-Disease-Detection.git
```

Navigate into the project directory:

```bash
cd Leafify-Plant-Disease-Detection
```

### 2. Set Up the Backend

Open a terminal in the project root and run:

```bash
cd backend
python -m venv venv
```

Activate the virtual environment.

**Windows:**

```powershell
.\venv\Scripts\Activate.ps1
```

**Linux/macOS:**

```bash
source venv/bin/activate
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Start the FastAPI server:

```bash
uvicorn main:app --reload
```

The backend is expected to run at:

http://127.0.0.1:8000

### 3. Set Up the Frontend

Open a second terminal in the project root:

```bash
cd "leafify frontend"
npm install
npm run dev
```

Open the local URL displayed in the terminal.

**Note:** The frontend and backend must be configured to communicate
with each other. Follow the API endpoint configuration in the source code.

## 🧠 Machine Learning Model

Leafify uses a trained PyTorch model for plant leaf image classification.

The repository includes the model file:

`backend/fast_plant_model.pth`

The backend loads this model to generate predictions from input images.

## 🎓 Learning Outcomes

This project demonstrates practical experience with:

- Integrating machine learning into a web application
- Image classification using deep learning
- Building REST APIs with FastAPI
- Developing interactive interfaces using React
- Connecting a frontend to a Python backend
- Managing source code using Git and GitHub

## 🔮 Future Enhancements

- Deploy the application online
- Improve prediction accuracy using additional training data
- Add more plant species and disease classes
- Improve prediction explanations and treatment recommendations
- Enhance the user interface and user experience


**Ankita Routray**

GitHub: https://github.com/AnkitasRoutray

---

⭐ If you find this project interesting, consider starring the repository!
