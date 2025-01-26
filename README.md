# Chatbot and Risk Prediction Platform

This project integrates two advanced features to assist pregnant women:

- 🤖 **Chatbot**  
- 🩺 **Risk Prediction Model**  

## 🚀 Features

### 🤖 Chatbot Functionality
- **Model**: Fine-tuned T5 using TensorFlow on 4,825 question-answer pairs.
- **Purpose**: Provides accurate and personalized responses to questions about pregnancy symptoms, precautions, and potential risks.

### 🩺 Risk Prediction Functionality
- **Model**: A deep neural network trained on health-related data.
- **Purpose**: Predict health risks based on user inputs such as:
  - 🌡️ **Temperature**
  - 👩‍🦳 **Age**
  - ❤️ **Heart rate**
  - And more...
- **Output**: Classifies risks into:
  - ✅ **Low Risk**
  - ⚠️ **Medium Risk**
  - ❗ **High Risk**

## 🛠 Technology Stack

- **Component** | **Technology**
  - Backend: Django Framework
  - Frontend: Django Templates
  - Chatbot Model: T5 (fine-tuned)
  - Risk Prediction Model: Deep Neural Networks

## 📋 Implementation Details

### Data Preparation
- **Chatbot**: Trained on 4,825 question-answer pairs.
- **Risk Prediction**: Built using health-related datasets.

### Platform Development
- Developed using **Django** to ensure scalability and ease of deployment.

## User Interaction

Users can:
- 🛂 **Log in or out**.
- 🤖 **Ask the chatbot** about symptoms or precautions.
- 🩺 **Enter personal health details** to classify risk levels.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/fatimahim/Plateforme-d-Assistance-Intelligente-pour-Les-Femmes-Enceintes
   
2. python manage.py migrate:
   ```bash
   python manage.py migrate
   
3. Run the development server:
   ```bash
   python manage.py runserver
##  Interface
![Accueil Page](interface/Acceuil.png)
![Login Page](interface/connexion.png)
![Signup Page](interface/Inscription.png)
![Chatbot Interface](interface/Chatbot.png)
![Risk Prediction Interface](interface/Predictionderisque.png)



