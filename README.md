# Real-Time-Facial-Emotion-Monitoring-System-using-deep-learning
This project implements a Real-Time Facial Emotion Detection System that uses deep learning and computer vision techniques to identify human emotions from live webcam input. The system captures video frames, detects faces, and classifies emotions such as happiness, sadness, anger, surprise, fear, and neutral in real time.
How to Run the Project
Clone the repository from GitHub
Open terminal and run:
git clone https://github.com/your-username/emotion-recognition.git
Then go into the folder:
cd emotion-recognition
Create a virtual environment
python -m venv venv
Activate the virtual environment
On Windows: venv\Scripts\activate
On Mac/Linux: source venv/bin/activate
Install required libraries
pip install -r requirements.txt
(If not available, install manually: pip install opencv-python numpy tensorflow or PyTorch)
Make sure the trained model file is present
Place the model file (like model.h5 or .pt) inside the project folder or /model directory.
Run the program
python src/detect.py
Use the application
Webcam will open
Face will be detected
Emotion will be shown on screen
Press Q to exit
