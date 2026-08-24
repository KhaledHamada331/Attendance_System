
# Face Recognition Attendance System 👁️🧑‍💼

An automatic attendance system using face recognition via webcam. It offers a secure and fast way to record attendance without the need for manual signing or ID cards.

## 🧠 Project Idea

The system recognizes a person’s face using a live webcam feed. If the face matches a previously stored image, it records the attendance along with the current date and time into a CSV file.

## 🛠️ Technologies Used

- Python 🐍
- [face_recognition](https://github.com/ageitgey/face_recognition)
- OpenCV 🎥
- Tkinter (for GUI) 🖼️
- CSV (for attendance records)

## 📦 Requirements

Make sure you have Python 3 installed and install the required libraries:


pip install opencv-python
pip install face_recognition
Note: face_recognition depends on Dlib, which may require cmake, boost, and other build tools (especially on Linux).

## How to Run
Make sure Python 3 is installed.

Place your known face images in the faces directory.

Run the main Python file:

python main.py
Use the GUI buttons:

"Verify Face" to take attendance.

"Exit" to close the app.

## 📝 Attendance Format
Attendance is stored in attendance.csv with the format:

Name,Time,Date
Duplicate entries for the same person on the same day are prevented.

## License

This project is not licensed. All rights reserved.
