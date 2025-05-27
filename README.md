# Face_Recognizer

![alt text](https://github.com/Lalith-Akash/Face_Recognizer/blob/master/cover_image.jpg)

A Python-based face recognition application that detects and identifies known individuals from images or webcam video streams. It uses facial embeddings for matching and provides real-time recognition with visual feedback.

1. Create two empty folders named 'dataset' and 'trainer' in your main folder after unzipping.
2. Run 1st file "face dataset.py" and enter id 1.
3. Again run "face dataset.py" with user id 2 with another face.
4. Run file "2. face training.py" and then further run file "3. face recognition.py".

(Note: For more than 2 faces to be recognized change the id number from 2 to any other greater number desired in file "3. face recognition.py")

📌 Features:

Detect and recognize multiple faces in images

Real-time face recognition using webcam

Preprocess and register known faces for identification

Annotate images/video with detected names

Store face data securely in an encoded format

Lightweight and runs offline

🔧 Tech Stack:

Python 3.6+

OpenCV – Image and video processing

face_recognition – Face detection and encoding (built on dlib)

NumPy – Data handling

Pillow – Image format conversion and support

📌 To Do / Extensions

GUI with Tkinter or PyQt

SQLite database to log recognized faces with timestamps

Email or SMS alerts for unknown entries

Add/delete known faces through UI

⚠️ Disclaimer
This project is meant for educational and demonstration purposes. For commercial or security-critical deployments, use professionally trained models and secure APIs.
A real time face recognition system developed in Python using Pillow, OpenCV and NumPy 

(This project took inspiration from several other similar projects available online.)
