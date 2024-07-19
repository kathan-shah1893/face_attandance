# face_attendance 👥

face_attendance is a face recognition-based attendance system built with Python and Flask.

## Features

- 📷 **Face Detection**: Detects faces in images or live video streams.
- 🎯 **Face Recognition**: Recognizes faces based on pre-trained models or user-defined datasets.
- 📅 **Attendance Management**: Records attendance based on recognized faces.
- 📊 **Reporting**: Generates attendance reports for users or administrators.
- 🔐 **Authentication**: Secure login system for administrators to manage system settings.
- 🌐 **Web Interface**: Provides a user-friendly interface using Flask web framework.
- 📱 **Responsive Design**: Supports both desktop and mobile devices.

## Technologies Used

- **Python**: Core language for development.
- **Flask**: Lightweight web framework for backend development.
- **OpenCV**: Library for computer vision tasks like face detection and recognition.
- **SQLite**: Database for storing attendance records and user information.
- **HTML/CSS/JavaScript**: Frontend development technologies for interface design and functionality.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kathan-shah1893/face_attendance.git
   cd face_attendance
   ```

2. Set up a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:

   ```bash
   flask run
   ```

5. Access the application at `http://localhost:5000` and start managing attendance!

## Usage

1. Sign in as an administrator to set up the system parameters and add employees/students.
2. Upload images or use live video for face detection and recognition.
3. Track attendance records and generate reports as needed.
4. Monitor system logs and manage user access and settings.

## Contributing

Contributions are welcome! If you'd like to add features, improve existing ones, or fix issues, please fork the repository and submit a pull request.

## Acknowledgments

- Built with Python and Flask, leveraging OpenCV for robust face detection and recognition capabilities.
- Inspired by the need for efficient attendance management systems using modern technologies.

---

Enjoy using face attendance for attendance management! 🚀
