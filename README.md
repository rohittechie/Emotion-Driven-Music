# emotion-driven-music
<h1>Emotion-Driven-Music</h1>
<a href="https://github.com/rohittechie/Emotion-Driven-Music/edit/main/README.md">Emotion based music | ai | deep learning project | with code | ml project</a>

<h1>Description</h1>

## 🎵 Emotion-Driven Music Recommender

An **AI-powered real-time web application** that detects your facial emotion through the webcam and plays music that perfectly matches your mood. This project blends **computer vision**, **deep learning**, and **interactive web technologies** to create a truly personalized listening experience.

### 🌟 Key Highlights

* **Real-Time Emotion Detection** – Uses your webcam feed to analyze facial expressions instantly.
* **AI-Driven Mood Classification** – A pre-trained deep learning model classifies emotions such as *happy, sad, neutral, angry, surprised*, etc.
* **Personalized Music Suggestions** – Plays songs that align with your detected mood for an immersive experience.
* **Interactive & User-Friendly** – Built using **Streamlit** with **streamlit-webrtc** for smooth live video streaming directly in your browser.

### 🛠️ Tech Stack & Tools

* **Computer Vision:** OpenCV, Mediapipe
* **Machine Learning:** Keras (TensorFlow backend), NumPy
* **Web Framework:** Streamlit + Streamlit-webrtc for real-time media streaming
* **Model Assets:**

  * `model.h5` – Pre-trained CNN model for emotion recognition
  * `labels.npy` – Emotion label mappings for classification results

### 🚀 How It Works

1. **Capture Input:** The application uses your webcam to capture live video frames.
2. **Process & Detect:** Mediapipe extracts facial landmarks, and the trained Keras model predicts your current emotion.
3. **Match & Play:** Based on the detected emotion, the system selects a playlist or track designed to match your mood.

### 💡 Why This Project is Special

* Showcases a **practical application** of AI in entertainment and personalization.
* Demonstrates **end-to-end integration** of machine learning models into a live, user-facing application.
* Can be extended for **therapeutic music**, **gaming experiences**, or **interactive marketing campaigns**.

---

