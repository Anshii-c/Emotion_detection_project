AI-Based Attendance System with Emotion Detection

This project is an intelligent, real-time attendance system that uses facial recognition and emotion analysis to automate and enhance traditional student tracking. It captures live video from a webcam, identifies students based on pre-enrolled facial data, detects their emotions, and logs this information with timestamps in a CSV file.

Features
- Face recognition using DeepFace
- Emotion detection during attendance
- Real-time webcam integration with OpenCV
- Time-restricted attendance window (09:30–10:00 AM)
- Automatic saving of attendance with name, status, emotion, and timestamp
- Handles unknown or undetected faces gracefully

Technologies Used
- Python
- OpenCV
- DeepFace
- Pandas
- NumPy

 How It Works
- Student Registration: Place student images (named as <Name>.jpg/.png) in the students/ directory.
- Start Time Window: The system only records attendance between 09:30 AM and 10:00 AM.
- Live Detection:
- Captures frames from webcam
- Identifies student using DeepFace
- Detects the student's dominant emotion
- Marks them as “Present” if identified
- Attendance Logging:
- Creates attendance.csv with attendance status and emotion
- Absent students are also logged

Notes
- Use a good-quality webcam for better detection.
- Make sure DeepFace models are pre-downloaded for faster execution.
- Run the script only within the allowed time window, or it will exit with a message.




