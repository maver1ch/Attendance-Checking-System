# Simple Attendance Checking System


## About The Project
This project focuses on developing an automatic attendance checking system that captures and verifies student attendance through real-time facial recognition. The system utilizes Deep Learning models, specifically **MTCNN** for face detection and **Facenet** for face recognition, to ensure accurate and efficient identification of students.

### Main Steps Involved:

- **Face Detection**: The system uses the MTCNN (Multi-task Cascaded Convolutional Networks) model to detect faces in real time.
- **Face Recognition**: The Facenet model is applied to recognize and verify student identities based on facial features.
- **Attendance Logging**: Once a face is recognized, the system logs the student's attendance in a database along with the timestamp.

### Future Improvements

- **Improved Recognition in Challenging Conditions**: Enhancing the system's robustness to varying lighting and occlusions.
- **Integration with Other School Systems**: Linking the attendance system with broader school management platforms.
- **Scalability**: Testing the system on larger datasets with more diverse student populations.
