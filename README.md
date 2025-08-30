# Face-Recognition-Attendance-System
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

1. **Prepare student images**
   - Place student photos in the `pages/student_images/` directory
   - Use clear, front-facing photos for best recognition accuracy
   - Supported formats: JPG, JPEG, PNG

2. **Configure the system**
   - Ensure your webcam is connected and accessible
   - Check that all required packages are installed correctly

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
   - **Take Attendance**: Use camera to detect and mark student attendance
   - **Attendance Register**: View and manage attendance records

## Troubleshooting

- **Camera not working**: Ensure your webcam is not being used by other applications
- **Face recognition errors**: Check that student images are clear and properly formatted
- **Package installation issues**: Try upgrading pip: `pip install --upgrade pip`

## Contributors
* Pranesh Shivaachalam R M
* Muthuram M
