# Face-Recognition-Attendance-System

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.0+-red.svg)](https://streamlit.io/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.0+-green.svg)](https://opencv.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://github.com/yourusername/Face-Recognition-Attendance-System)

BECM101P: Introduction To Engineering Coursework

The website provides functionality for faculty to take attendance for each student.
Works by placing a camera at the door of the class and student is marked present if the system detects the student. 
Time of arrival is also marked.

## Requirements
* streamlit 
* pandas
* opencv-python
* streamlit_webrtc
* face_recognition

## Prerequisites
* List of students enrolled in the class
* Each Students's facial data has to be registered during first run.

## Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Face-Recognition-Attendance-System
   ```

2. **Install Python dependencies**
   ```bash
   pip install -r requirements.txt
   ```

   **Note:** If you encounter issues with `face_recognition` on Windows, you may need to install Visual Studio Build Tools first, or use a pre-compiled wheel.

## Setup

1. **Configure the system**
   - Ensure your webcam is connected and accessible
   - Check that all required packages are installed correctly

2. **Register students (first-time setup)**
   - Use the "Attendance Register" page to add new students
   - Take photos of students during the registration process
   - Photos are automatically captured and stored by the system

## Running the Application

1. **Start the Streamlit app**
   ```bash
   streamlit run Welcome.py
   ```

2. **Access the application**
   - The app will open in your default web browser
   - If it doesn't open automatically, navigate to `http://localhost:8501`

3. **Using the application**
   - **Welcome Page**: Main entry point with navigation
   - **Attendance Register**: Register new students and capture their photos for face recognition
   - **Take Attendance**: Use camera to detect registered students and mark attendance

## Troubleshooting

- **Camera not working**: Ensure your webcam is not being used by other applications
- **Face recognition errors**: Check that student images are clear and properly formatted
- **Package installation issues**: Try upgrading pip: `pip install --upgrade pip`

## Contributors
* Pranesh Shivaachalam R M
* Muthuram M
