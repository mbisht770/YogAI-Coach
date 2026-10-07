🧘‍♂️ YogAI-Coach: AI-Powered Yoga Posture Classification
YOG-AI (by Team Dash 2.0) is an AI-powered real-time yoga posture classification system designed to guide users during their yoga sessions. It uses machine learning to classify yoga poses based on body landmarks and provides audio feedback to help users correct their posture — all through WhatsApp, without the need for a heavy app setup.

🔥 Live Demo
“You raise your hand… but no one tells you it’s 15° too high. That ends now.”

YOG-AI delivers real-time pose correction and coaching. Experience the future of AI fitness — no app needed.

📌 Problem Statement
The goal is to build a machine learning model that:

Classifies yoga postures accurately.
Works well in real-world, variable conditions.
Supports fitness apps, posture tracking, and user wellness.
🏗️ Architecture
Pose Detection: MediaPipe BlazePose (33 body landmarks)
Classification Model: Random Forest (lightweight, scalable)
Interface: WhatsApp + Real-time Audio Feedback
Pipeline:
✅ Green pipes: Correct pose
❌ Red pipes: Incorrect pose
📁 Project Structure
📦 YOG-AI ├── classification.py # ML model for pose classification ├── shankar4.py # Auxiliary logic for processing pose inputs ├── landmarks_dataset.csv # Dataset of 33 body landmark coordinates ├── Untitled.ipynb # Notebook for development/testing ├── feedback.mp3 # Audio feedback file for real-time guidance ├── LICENSE.md # Licensing info └── README.md # Project documentation

🚀 How to Run
Requirements
Python 3.7+
Libraries: scikit-learn, numpy, pandas, mediapipe, opencv-python
Installation
Clone the repository:
git clone https://github.com/yourusername/yog-ai.git
cd yog-ai
Install dependencies:
pip install -r requirements.txt
Run the classifier:
python classification.py
For testing and experimentation:
jupyter notebook Untitled.ipynb
📊 Dataset
Each entry contains 33 body landmark coordinates.
Data collected using MediaPipe BlazePose.
Includes samples for various yoga poses for multi-class classification.
🎯 Features
Real-time yoga posture detection.
Voice-based feedback (feedback.mp3).
Optimized for mobile and web platforms.
No app download required — works seamlessly with WhatsApp.
Expandable for multi-user use cases.
🌱 Future Goals
Yoga-as-a-Service (YaaS) offering.
Introduce a Posture Score as a wellness metric.
Support for multi-pose & multi-user functionality.
Launch a commercial subscription model for coaches and fitness apps.
📚 References
BlazePose – Real-time Pose Estimation
Pose Detection using MediaPipe
Smart HealthCare IoT Integration
