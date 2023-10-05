# Smart Attendance System using Face Recognition

## Overview

This Python-based Smart Attendance System automates attendance tracking using face recognition technology. The system captures facial data from a camera feed, matches it with the images stored in the database, and updates attendance records in real-time. If a match is found, the student is marked as present in an Excel file. If a student's face is missing, they are marked as absent. If the face doesn't match any stored records, it's marked as unknown.

## Features

- **Face Data Capture:** The system captures facial data from a live camera feed.
- **Face Matching:** Captured faces are compared with images stored in the database.
- **Attendance Update:** If a match is found, the student's attendance is marked as present in an Excel file.
- **Absence Handling:** If a student's face is missing, they are marked as absent in the attendance record.
- **Unknown Faces:** If a face doesn't match any stored records, it is marked as unknown.

## Requirements

- Python 3.x
- face recognition
- OpenCV
- NumPy
- Pandas
