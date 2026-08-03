# 🌿 AI-Based Plant Disease Detection and Treatment Recommendation System

## 📖 Overview

Plant diseases are one of the major causes of reduced agricultural productivity. This project presents an AI-powered system that detects plant diseases from leaf images using a Vision Transformer (ViT) deep learning model. The application predicts the disease affecting the plant and recommends suitable treatment products through an easy-to-use web interface.

The project is developed using Python, PyTorch, Flask, and Google Colab. ngrok is used to make the Flask application accessible through a public URL during development.

---

## 🎯 Objectives

- Detect plant diseases from leaf images.
- Improve the accuracy of disease identification using Deep Learning.
- Recommend suitable treatment products based on the predicted disease.
- Develop a user-friendly web application for disease prediction.
- Assist farmers in early disease diagnosis and treatment.

---

## ✨ Features

- Upload plant leaf images for prediction.
- Automatic plant disease detection.
- Vision Transformer (ViT) based classification.
- Disease prediction with treatment recommendations.
- Flask-based web application.
- ngrok integration for web access from Google Colab.
- Fast and accurate prediction results.

---

## 🛠 Technologies Used

- Python
- PyTorch
- Vision Transformer (ViT)
- Flask
- Google Colab
- ngrok (pyngrok)
- NumPy
- OpenCV
- Pillow
- Matplotlib
- Transformers

---

## 🧠 Model Used

**Vision Transformer (ViT-Base)**

The model is trained to classify plant leaf images into different disease categories and provide treatment recommendations.

---

## 📂 Project Workflow

1. Upload a plant leaf image.
2. Preprocess the image.
3. Verify whether the uploaded image is a plant leaf.
4. Predict the disease using the Vision Transformer model.
5. Display the predicted disease.
6. Recommend suitable treatment products.
7. Show the result through the Flask web application.

---

## 📁 Project Structure

```text
Plant-Disease-Detection/
│
├── Plant_Disease_Detection.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
├── vit_model/
│   ├── plant_vit_base.pth
│   ├── class_names.json
│   └── plant_products/
│
├── templates/
├── static/
└── uploads/
```

---

## 📊 Results

- Accurate plant disease prediction.
- Fast image classification using Vision Transformer.
- Treatment recommendation based on the detected disease.
- Easy-to-use web interface for users.

---

## 🚀 Future Enhancements

- Mobile application development.
- Real-time disease detection using a mobile camera.
- Cloud deployment.
- Support for additional crop species.
- Fertilizer recommendation.
- Multi-language support.

---

## 📌 Applications

- Smart Agriculture
- Precision Farming
- Crop Health Monitoring
- Agricultural Research
- Farmer Assistance Systems

---
## Model File

The trained ViT model (`plant_vit_base.pth`) is not included in this repository because it exceeds GitHub's file size limit.

To run the project, place the trained model file in the project directory before running the notebook.

## 👩‍💻 Author

**Pradeepthi Chamana**

B.Tech – Data Science

---

## 📄 License

This project is licensed under the MIT License.
