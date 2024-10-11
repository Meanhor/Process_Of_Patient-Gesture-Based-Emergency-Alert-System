# Patient-Gesture-Based Emergency Alert System

This project is a **real-time emergency alert system** designed to recognize patient gestures and provide immediate alerts to medical personnel. It leverages **computer vision** and **machine learning** to detect hand gestures and facial cues to determine if an emergency situation has occurred. The system is designed specifically for non-verbal patient communication, offering caregivers and medical staff a way to receive alerts through gesture recognition.

## Features
- **Data Collection**: Capture and store gesture data from patients using a camera.
- **Training**: Train the system with a dataset of hand gestures and facial features using machine learning models.
- **Testing**: Test the system's accuracy in detecting gestures and identifying emergency situations.
- **Real-time Alerts**: Provide real-time notifications (including audio alerts) to medical personnel when an emergency is detected.

## Technologies Used
- **TensorFlow**: For hand gesture recognition and model training.
- **OpenCV**: For image processing and video capture from the camera.
- **MediaPipe**: For hand landmark detection and gesture tracking.
- **Audio Alerts**: Integrated audio notifications for emergencies.

## Installation

### Prerequisites
- Python 3.x
- TensorFlow
- OpenCV
- MediaPipe
- Any other required dependencies can be installed using `requirements.txt`.

### Steps to Set Up
1. **Clone the repository**:
   ```bash
   git clone [https://github.com/yourusername/Patient-Gesture-Alert-System.git](https://github.com/Meanhor/Csl_Term2.git)
   cd Csl_Term2
## Usage

### Data Collection
Connect a camera to capture video streams of the patient's hand gestures. The system uses **MediaPipe** and **OpenCV** to process and store these gestures in a dataset.

### Training
The hand gesture recognition model can be trained on custom datasets using **TensorFlow**. Use the provided training scripts to train your model.

### Real-time Monitoring
The system continuously monitors patient gestures. If a gesture matches predefined emergency patterns (e.g., a specific hand sign for "SOS"), the system triggers an alert.

### Testing
Test the system using live or recorded data to ensure accuracy and response time. The application logs detected gestures and alerts to provide feedback on performance.
