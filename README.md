# Realtime Video AI Gym Coach 🏋️‍♂️

An AI-powered fitness application built with **Streamlit**, **OpenCV**, and **MediaPipe** that provides real-time exercise tracking and posture correction using your webcam.  
The app helps users perform workouts correctly by analyzing body movements and giving instant feedback.

---

## 🚀 Features
- Real-time video capture using OpenCV
- Pose detection and tracking with MediaPipe
- Exercise-specific video processing (e.g., squats, push-ups, curls)
- Streamlit interface for easy deployment and usage
- Cloud-ready with Streamlit Sharing

---

## 📂 Project Structure
realtime-video-ai-gym-coach/
│
├── main.py                          # Streamlit entry point
├── services/
│   └── vision/
│       └── exercise_video_processor.py  # Video processing logic
├── requirements.txt                 # Dependencies
└── README.md                        # Project documentation


---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AdityaJadkar21/Realtime-Video-AI-Gym-Coach.git
   cd Realtime-Video-AI-Gym-Coach

2. Create and activate a virtual enviornment:
   python -m venv venv
   venv\Scripts\activate   # On Windows
   source venv/bin/activate # On macOS/Linux

3. Install dependencies:
   pip install -r requirements.txt

## ▶️ Running Locally
Start the Streamlit app:
streamlit run main.py
Open your browser at http://localhost:8501 to use the app.

## ☁️ Deploying on Streamlit Cloud
- Push your code to GitHub.
- Go to Streamlit Cloud.
- Connect your GitHub repo.
- Deploy the app — Streamlit will install dependencies from requirements.txt.

## 📦 Requirements
streamlit
mediapipe
numpy
opencv-python-headless==4.9.0.80
protobuf==3.20.*

## 🛠️ Troubleshooting
- If you see ImportError: cv2, ensure you’re using opencv-python-headless in requirements.txt.
- Always clear Streamlit Cloud cache after updating dependencies.
- Add .venv/ and other large files to .gitignore before pushing to GitHub.

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

## 📜 License
This README gives your repo a professional look and makes it easy for others (and future you) to set up and run the app.  
