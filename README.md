# 👤 Face Recognition System in Python

A simple face recognition system built with Python and OpenCV. This project allows users to capture faces, train a recognizer model, and identify people in real-time using their webcam.

## 📁 Project Structure

```bash
Face_Recognition_Python/
├── face_taker.py                  # Capture face images and store them
├── face_train.py                  # Train face recognition model
├── face_recognizer.py             # Recognize faces using the trained model
├── haarcascade_frontalface_default.xml  # Haar Cascade classifier for face detection
├── names.json                     # Stores label-to-name mappings
├── trainer.yml                    # Trained recognizer data
└── README.md                      # Project documentation (this file)
```

##🛠️ Technologies Used
      Python 3.x
      OpenCV
      NumPy
      Haarcascade for face detection
      LBPH (Local Binary Pattern Histogram) for face recognition

## 🚀 How to Use
1. Install Requirements
     ```bash
      pip install opencv-python numpy
     ```
3. Capture Faces
    Run the script and follow on-screen instructions:
   ```bash
     python face_taker.py
   ```
5. Train the Model
    After capturing enough samples:
    ```bash
    python face_train.py
    ```
7. Recognize Faces in Real-Time
   ```bash
    python face_recognizer.py
   ```

## 🧠 How It Works
1. face_taker.py: Uses OpenCV to detect and store face images.
2. face_train.py: Converts images into grayscale, assigns IDs, and trains a recognizer.
3. face_recognizer.py: Detects faces via webcam and matches them with trained data using LBPH algorithm.
4. names.json: Stores mapping between numerical IDs and names.
5. trainer.yml: Saved model data from training phase.

## ✅ Features
1. Real-time face recognition
2. Model training with your own face data
3. Modular scripts for capturing, training, and recognizing
4. Uses Haarcascade and LBPH from OpenCV

## 🧩 Possible Improvements
1. Add a GUI using Tkinter or PyQt
2. Integrate email/SMS alerts when an unknown face is detected
3. Store data in an SQLite or Firebase DB
4. Add face masking detection or emotion recognition

## 👩‍💻 Author
**Shruti Shukla**
Aspiring Data Scientist |https://www.linkedin.com/in/sshukla911/

Feel free to star ⭐ this repo if you found it useful!
