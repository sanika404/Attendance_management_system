# Attendance System

## Overview

This project is a Python-based GUI integrated attendance system. It uses face recognition technology to record attendance.

## Technologies Used

- **Tkinter**: Used for creating the GUI.
- **OpenCV**: Used for capturing images and performing face recognition with the `cv2.face.LBPHFaceRecognizer_create()` method.
- **CSV, Numpy, Pandas, datetime**: Used for various other purposes such as data handling and time recording.

## Features

1. **Password Protection**: The system provides password protection for new person registration.
2. **CSV File Management**: The system creates or updates a CSV file with the details of students upon registration.
3. **Daily Attendance Records**: The system creates a new CSV file every day for attendance, marking each attendance with the proper date and time.
4. **Live Attendance Updates**: The system displays live attendance updates for the day on the main screen in a tabular format. The table includes the ID, name, date, and time of attendance.

## Screenshots
![WhatsApp Image 2023-11-24 at 2 29 09 PM](https://github.com/sanika404/Attendance_management_system/assets/134488939/1b165273-2fb7-430f-a432-b9386fc674fd)

![WhatsApp Image 2023-11-24 at 2 29 43 PM](https://github.com/sanika404/Attendance_management_system/assets/134488939/397921bb-64fd-4c18-a113-383365cf062f)


## Getting Started

1. Clone this repository and open it in Visual Studio Code.
2. Install all the dependencies listed in the `install_commands.txt` file.
3. Run `main.py` in the terminal using the command `python main.py`.
4. When adding a new user, you will be prompted for a password. The default password is "akshit123".
5. You can change the password in the `TrainingImageLabel -> psd.txt` file. There is also an option to do this in the GUI.
6. Add a new user by clicking the "Add New User" button.
7. When you click to take a photo, please wait for a moment as the system captures 100 images of your face and stores them in the `TrainingImage` folder.
8. After your profile is saved, click "Take Attendance". If the camera recognizes your face and displays your name, press 'Q' to end the scanning process.
9. Once scanning is complete, your attendance will be updated in a CSV file and reflected in the GUI interface.
