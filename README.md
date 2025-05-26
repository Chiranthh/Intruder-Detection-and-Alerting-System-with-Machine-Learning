# Intruder Detection and Alerting System with Machine Learning

This project implements an **Intruder Detection and Alerting System** using **Machine Learning** and **Computer Vision** techniques. The system is designed to automatically detect unauthorized individuals and send alerts in real time, enhancing security in sensitive environments such as homes, offices, or restricted areas.

## 🔍 Features

- 🎥 Real-time video stream monitoring  
- 🧠 Intruder detection using machine learning (face recognition)  
- 📧 Alert notification system via email  
- 📸 Face dataset collection and training  
- 🖥️ GUI interface for user interaction  
- 📝 Logging of detection events  

## 🛠️ Technologies Used

- Python  
- OpenCV  
- Tkinter  
- Scikit-learn  
- NumPy  
- Pandas  
- Pickle  
- SMTP (for email alerts)  

## ⚙️ How It Works

1. **Face Dataset Collection**: Capture images of authorized individuals using a webcam.  
2. **Model Training**: Train a face recognition model with the collected face data.  
3. **Live Detection**: Continuously scan the video feed and compare faces with the trained model.  
4. **Alert System**: If an intruder is detected, an email alert with an image is sent to the user.  

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/intruder-detection-system.git
cd intruder-detection-system

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py
