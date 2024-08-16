

**Face Recognition Attendance System**


**Features:**

- **Face Detection:** Utilizes Haarcascade face detection algorithms to accurately detect faces from images and video streams.
  
- **Face Recognition:** Implements pre-trained deep learning models such as OpenCV's Deep Neural Networks for face recognition, enabling accurate recognition of registered individuals.
  
- **Attendance Recording:** Automatically records attendance based on recognized faces, eliminating the need for manual entry and reducing administrative workload.
  
- **User Registration:** Allows administrators to register individuals into the system by capturing their facial features and storing them securely.
  
- **User Interface:** Provides a user-friendly interface for administrators to interact with the system, view attendance records, and manage user profiles.

**Installation:**

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/sarveshsce/face-recognition-attendance-system.git
   ```

2. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Run the application:

   ```
   python main.py
   ```

**TECHNOLOGY USED:**
1) tkinter for whole GUI
2) OpenCV for taking images and face recognition (cv2.face.LBPHFaceRecognizer_create())
3) CSV, Numpy, Pandas, datetime etc. for other purposes.

**Usage:**

1. Register Users: Capture facial features of individuals and register them into the system.
2. Start Attendance: Initiate attendance recording by running the application.
3. View Records: View attendance records and generate reports as needed.







