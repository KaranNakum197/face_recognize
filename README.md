# 👤 Face Recognition Attendance System with Flask

A Python-based attendance system that uses **real-time face recognition** to mark attendance and provides a **Flask-based web interface** to view attendance records.

---

## 🔍 Overview

This system captures faces using a webcam, recognizes known individuals using pre-encoded face data, and logs their attendance with timestamps. Attendance logs are stored in a CSV or database, and a **Flask web app** displays the records in a browser.

---

## 🚀 Features

- 🎥 Real-time face recognition using webcam
- 🧠 Face encoding using `face_recognition` library
- 📝 Attendance logging with name, date, and time
- 🖼️ New user face registration with image capture
- 🌐 Flask web app to view attendance records
- 💾 Attendance stored in CSV or SQLite/MySQL database
- 📊 Attendance filtering by date, name, or status (via Flask UI)

---

## 🛠️ Tech Stack

- **Python 3.x**
- **OpenCV**
- **face_recognition**
- **Flask** (Web Interface)
- **Pandas** (CSV handling)
- **SQLite / MySQL** (optional DB backend)
- **HTML/CSS/Jinja2** (Flask templating)
