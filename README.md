# 🔐 Face Recognition Login System

This project is a Python-based login system that uses face recognition for user authentication. It leverages **OpenCV**, **dlib**, and the **face_recognition** library to detect and recognize faces via webcam, replacing traditional username/password logins.

## 🚀 Features

- Real-time face detection using webcam  
- Face recognition for login verification  
- Registration of new users with automatic face encoding  
- Logs of login attempts with timestamps  
- User-friendly GUI using `tkinter`  

## 🛠️ Tech Stack

- **Python 3.8+**  
- **OpenCV**  
- **face_recognition**  
- **dlib**  
- **tkinter**

## 📁 Project Structure

FaceRecognitionLogin/
│
├── main.py # Main GUI and application logic
├── face_encoder.py # Face encoding and comparison
├── register_user.py # Register new user with face
├── utils.py # Helper functions (e.g. logging, messages)
├── users/ # Stores encoded face data per user
├── logs/ # Stores login timestamps
└── requirements.txt # Required Python libraries

csharp
Copy
Edit

## ✅ How It Works

1. **Register**: A new user registers their face via webcam, which is encoded and saved.  
2. **Login**: The system captures your current face and compares it with registered encodings.  
3. **Authentication**: If a match is found, the user is granted access and login is logged.

## 🖥️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FaceRecognitionLogin.git
   cd FaceRecognitionLogin
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
📌 Notes
Ensure good lighting for accurate recognition.

The first-time setup may require downloading face recognition models.

Faces are encoded into .npy files and stored securely.

scss
Copy
Edit

Let me know if you want help generating the `requirements.txt` or [GitHub formatting preview](f).








