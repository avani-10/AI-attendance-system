# 📸 Attendify

A face recognition-based attendance system built with Python and OpenCV.

## 🚀 Features
- Real-time face detection and recognition
- Register faculty using webcam
- Auto-generate attendance logs
- Stores face encodings for fast recognition
- Attendance exported as CSV files

## 🛠 Tech Stack
- Python, OpenCV
- NumPy, Pandas
- Local file storage (CSV, images)

## 📂 Folders
- `train_images/` – Training images
- `encodings/` – Stored face encodings
- `exports/` – Attendance CSVs
- `db/` – Local data (if any)

## ▶️ How to Use
```bash
python register_faculty.py      # Register a new face
python attendance.py            # Mark attendance
