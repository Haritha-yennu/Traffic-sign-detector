# 🚦 Traffic Sign Identifier using YOLOv8 + Gemini AI

This project helps identify traffic signs using a custom-trained YOLOv8 model. If the model cannot confidently detect a sign, Gemini AI is used to describe it based on the uploaded image or user's input.

## 🔍 Features

- Upload any traffic sign image
- Detects sign using a YOLOv8 object detection model
- If confidence is low (<50%), Gemini AI confirms the prediction
- If no object is detected, Gemini AI tries to describe the sign from the image
- Option to describe the sign manually and get a response from Gemini
- Built with **Streamlit**, **YOLOv8**, and **Gemini 1.5 Flash API**

## 🧠 Technologies Used

- YOLOv8 (`ultralytics`)
- Streamlit
- Gemini 1.5 Flash (Generative AI)
- OpenCV
- Python

## 📁 Files

- `app.py`: Main Streamlit app
- `traffic.ipynb`: Notebook used for development/testing
- `best_yolov8m.pt`: Custom trained YOLOv8 model (not included due to size)
- `README.md`: You're reading it!

## 🔐 Note

To use Gemini AI features, you’ll need your own API key from [Google AI Studio](https://aistudio.google.com/app/apikey).

## 🚀 How to Run Locally

1. Clone this repo:
   ```bash
   git clone https://github.com/Haritha-yennu/Traffic-sign-detector.git
   cd Traffic-sign-detector
   
2. Install required packages
   
3. Run the app:
   streamlit run app.py

4. Enter your Gemini API key when prompted.
