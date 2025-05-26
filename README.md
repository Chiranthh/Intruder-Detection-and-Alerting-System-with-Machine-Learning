Intruder Detection and Alerting System with Machine Learning
This project implements an Intruder Detection and Alerting System using Machine Learning and Computer Vision techniques. The system is designed to automatically detect unauthorized individuals and send alerts in real time, enhancing security in sensitive environments such as homes, offices, or restricted areas.

Features
Real-time video stream monitoring

Intruder detection using machine learning (face recognition)

Alert notification system via email

Face dataset collection and training

GUI interface for user interaction

Logging of detection events

Technologies Used
Python

OpenCV

Tkinter

Scikit-learn

NumPy

Pandas

Pickle

SMTP (for email alerts)

How It Works
Face Dataset Collection: Capture images of authorized individuals using a webcam.

Model Training: Train a face recognition model with collected face data.

Live Detection: The system continuously scans the video feed and compares faces with the trained model.

Alert System: If an intruder is detected, an email alert is sent to the registered user with an image of the intruder.

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/intruder-detection-system.git  
cd intruder-detection-system
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the application:

bash
Copy
Edit
python main.py
Project Structure
bash
Copy
Edit
├── dataset/                 # Collected face images  
├── recognizer/              # Trained model files  
├── screenshots/             # Captured images of intruders  
├── main.py                  # Main application file  
├── train_model.py           # Script to train face recognition model  
├── collect_dataset.py       # Script to collect face images  
├── send_mail.py             # Script to send email alerts  
├── utils.py                 # Utility functions  
└── README.md                # Project description  
Usage
Run collect_dataset.py to capture authorized users' face data.

Train the model using train_model.py.

Start the intruder detection with main.py.

Alert System
Email alerts are sent using SMTP.

Configure your email credentials in send_mail.py before use.

Screenshots
Screenshots of intruders are saved in the screenshots/ directory for record-keeping.

License
