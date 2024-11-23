# Driver Drowsiness Detection System  

**Driver Drowsiness Detection System** is a real-time safety application designed to monitor a driver’s alertness and reduce accidents caused by fatigue. The system uses computer vision and machine learning techniques to detect signs of drowsiness, such as prolonged eye closure, and provides timely alerts to the driver.  

## 🚀 Features  
- **Real-Time Monitoring**: Detects driver drowsiness in real-time using a webcam.  
- **Eye Closure Detection**: Differentiates between normal eye blinks and prolonged closures indicative of drowsiness.  
- **Alert System**: Triggers visual or audio alerts when drowsiness is detected.  
- **Scalability**: Can be integrated with vehicle systems or wearables for advanced monitoring.  

## 🛠️ Tech Stack  
- **Programming Language**: Python  
- **Libraries and Frameworks**:  
  - OpenCV: For image processing and video frame analysis.  
  - dlib: For facial landmark detection.  
  - NumPy: For numerical computations.  
- **Shape Predictor Model**: Uses `shape_predictor_68_face_landmarks.dat` for precise facial landmark detection.  
- **Hardware Requirements**: Webcam or camera-enabled device.  

## 📦 Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/driver-drowsiness-detection.git
Navigate to the project directory:
bash
Copy code
cd driver-drowsiness-detection
Download the shape predictor file (shape_predictor_68_face_landmarks.dat) from dlib's model downloads.
Extract the .bz2 file to get shape_predictor_68_face_landmarks.dat.
Place it in the project directory.
Install the required Python libraries:
bash
Copy code
pip install -r requirements.txt
Run the application:
bash
Copy code
python drowsiness_detection.py
🔧 Usage
Ensure the shape_predictor_68_face_landmarks.dat file is in the project directory.
Position the camera to capture the driver’s face.
Run the application, and it will begin real-time monitoring.
Alerts are triggered if signs of drowsiness are detected.
🎯 Future Enhancements
Integration with smartwatches for monitoring stress levels and syncing with the vehicle system.
Optimized algorithms for detecting drowsiness in various lighting conditions.
Advanced alert mechanisms (e.g., vibration feedback or emergency braking).


📄 License
This project is licensed under the MIT License.

💡 Acknowledgments
Special thanks to the open-source community for providing tools and resources to build this project.


This version ensures that the **shape predictor 68 landmarks model** is properly mentioned in the setup process, along with a link to download the file.
