# Insight_Alliance/Heart_Disease_Prediction
# Heart Disease Prediction and Health Chatbot

This project provides a **Heart Disease Prediction** system and a **Healthcare Chatbot** powered by machine learning and AI. The application consists of three main features:

1. **Heart Disease Prediction** using clinical data.
2. **Health Chatbot** based on Google Gemini AI.
3. **Heart Disease Prediction from X-ray images** using a Convolutional Neural Network (CNN).

### Project Features

- **Heart Disease Prediction from Clinical Data**: Based on features such as age, blood pressure, cholesterol, and heart rate, the system predicts the likelihood of heart disease using a Random Forest model.
  
- **Health Chatbot**: The chatbot uses Google's Gemini AI (via Langchain API) to provide responses to health-related queries. It ensures the responses are safe and informative, recommending consulting a healthcare professional where necessary.
  
- **Heart Disease Prediction from X-ray Images**: This feature uses a Convolutional Neural Network (CNN) to predict the likelihood of heart disease from a chest X-ray image.

---

### Requirements

- Python 3.x
- TensorFlow 2.x
- Keras
- Gradio
- Langchain Google GenAI
- pandas
- scikit-learn
- Pillow

You can install the required packages using pip:

```bash
pip install -qU langchain-google-genai gradio tensorflow keras pillow pandas scikit-learn
