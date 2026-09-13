# 📊 Attendance Management System

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)

</p>

<p align="center">
  <b>A Flask-based attendance management system with QR code scanning, Excel/Google Sheets integration, student and trainer dashboards, and automated attendance tracking.</b>
</p>

---

## 📌 Project Overview

The **Attendance Management System** is a web-based application developed using **Python and Flask** to automate and manage student attendance.

The system combines:

- 🌐 Flask web application
- 📱 QR code-based attendance
- 📊 Excel attendance management
- 📋 Google Sheets integration
- 🗄️ SQLite database
- 👨‍🎓 Student dashboard
- 👨‍🏫 Trainer dashboard
- 📝 Student feedback
- 📧 Attendance reminder functionality
- 📄 Resume upload
- 📥 Attendance report downloads

The main goal of the project is to reduce manual attendance work and provide a centralized system for managing student attendance records.

---

# 🎯 Objectives

The main objectives of this project are:

- Automate student attendance recording
- Reduce manual attendance tracking
- Scan student QR codes using a camera
- Store attendance records in Excel
- Synchronize attendance with Google Sheets
- Provide separate student and trainer dashboards
- Maintain student information using SQLite
- Allow trainers to manage students
- Provide attendance reports
- Allow students to submit feedback
- Generate student-specific QR codes
- Support attendance correction
- Provide automated absence reminders

---

# ✨ Key Features

## 📱 QR Code Attendance

Students can be identified using QR codes.

The system:

1. Opens the camera
2. Detects QR codes
3. Reads the student's roll number/PIN
4. Identifies the student
5. Finds the student's course and branch
6. Marks the student as **Present**
7. Marks other registered students as **Absent**
8. Updates the attendance records

QR scanning is implemented using:

```python
OpenCV
pyzbar
