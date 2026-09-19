# Face Attendance System

A Python-based automated attendance management system using OpenCV and Face Recognition. The system captures live video feed via webcam, matches faces with pre-stored images in a directory, and automatically logs the recognized student's attendance along with the current date and time into an Excel file (`attendance.xlsx`).

## Features

- **Webcam Image Capture**: Captures real-time frames using OpenCV on keypress (`Space` key).
- **Facial Recognition**: Utilizes the `face_recognition` library to generate facial encodings and compare them with known face records.
- **Automated Attendance Logging**: Uses `pandas` to dynamically create or update `attendance.xlsx` with Student Name, Date (`YYYY-MM-DD`), and Time (`HH:MM:SS`).
- **Error Handling**: Gracefully handles missing excel files and unrecognized faces.

## Tech Stack & Libraries

- **Python 3.x**
- **OpenCV (`cv2`)**: For video capture and GUI window management.
- **`face_recognition`**: For deep learning-powered face detection and matching.
- **`pandas`**: For reading and updating attendance records in Excel.
- **`datetime` & `os`**: For timestamps and file system management.

## Prerequisites & Installation

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/lakshay-shukla/Face_Attendance_system.git](https://github.com/lakshay-shukla/Face_Attendance_system.git)
   cd Face_Attendance_system
