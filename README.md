# 🎭 Facial Emotion Recognition (FER)

A deep learning project that detects **human emotions** (Happy, Sad, Angry, Fear, Surprise, Disgust, Neutral) from facial expressions using **Convolutional Neural Networks (CNNs)**.  
Built with **TensorFlow/Keras** and **OpenCV** for real-time emotion recognition from webcam/video feed.

---

## ✨ Features
- 🧠 CNN-based classifier trained on **FER-2013 dataset**  
- 🎥 Real-time emotion detection via **webcam** using OpenCV  
- 🔄 Data augmentation for improved accuracy  
- 🛡️ Dropout + Batch Normalization for reduced overfitting  
- 🌐 Deployable Flask web app for interactive demos  

---

## 📂 Project Structure
```
📁 facial-emotion-recognition
 ┣ 📂 models/             # Saved models
 ┣ 📂 static/             # CSS/JS (for Flask app)
 ┣ 📂 templates/          # HTML templates (for Flask app)
 ┣ 📜 train.py            # Training script
 ┣ 📜 evaluate.py         # Evaluation script
 ┣ 📜 app.py              # Flask app for deployment
 ┣ 📜 realtime.py         # Real-time webcam emotion detection
 ┣ 📜 requirements.txt    # Dependencies
 ┗ 📜 README.md           # Project docs
```

---

## 🚀 Installation & Setup

### 1️⃣ Clone the repo
```bash
git clone https://github.com/YOUR-USERNAME/facial-emotion-recognition.git
cd facial-emotion-recognition
```

### 2️⃣ Create a virtual environment (recommended)
```bash
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run training (optional, pretrained model provided)
```bash
python train.py
```

### 5️⃣ Run real-time recognition
```bash
python realtime.py
```

### 6️⃣ Run Flask app
```bash
python app.py
```
Open [http://localhost:5000](http://localhost:5000) in your browser.

---

## 🎥 Demo
### Real-time Emotion Detection  
![Demo GIF](assets/demo.gif)  
*(Add your screen recording here — recruiters love visuals!)*  

---

## 🧪 Model Performance
- **Training Accuracy**: ~97%  
- **Validation Accuracy**: ~65% (after augmentation + regularization)  
- Evaluated on **FER-2013 dataset**  

---

## 📊 Sample Results
| Image | Predicted Emotion |
|-------|------------------|
| ![](assets/happy.png)   | 😀 Happy |
| ![](assets/sad.png)     | 😢 Sad |
| ![](assets/angry.png)   | 😠 Angry |
| ![](assets/fear.png)    | 😨 Fear |
| ![](assets/surprise.png)| 😲 Surprise |
| ![](assets/disgust.png) | 🤢 Disgust |
| ![](assets/neutral.png) | 😐 Neutral |


---

## 🔮 Future Improvements
- 🔹 Use **Transfer Learning** (ResNet, MobileNetV2) for higher accuracy  
- 🔹 Multi-modal recognition (facial + voice emotion analysis)  
- 🔹 Deploy on **Streamlit / Gradio / HuggingFace Spaces**  

---

## 🧑‍💻 Tech Stack
- **Python**  
- **TensorFlow/Keras**  
- **OpenCV**  
- **Flask**  

---

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.  

---

## 📜 License
This project is licensed under the **MIT License**.  

---

## ⭐ Support
If you like this project, consider giving it a **star ⭐** on GitHub — it helps others find it and motivates me to keep building cool projects!
