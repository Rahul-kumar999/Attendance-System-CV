
# 👨‍💼 Face Attendance System

A real-time **Face Recognition Attendance System** built with **Python** and **OpenCV**. This system detects and recognizes faces from a webcam feed and automatically marks attendance with a timestamp.

---

## 🎯 Features

- 📸 **Live Face Detection** using OpenCV.
- 🧠 **Face Recognition** using pre-trained deep learning models.
- 🕒 **Automatic Attendance Marking** with date and time.
- 🖥️ Simple and intuitive CLI/GUI interface ( with Tkinter).

---

## 🛠️ Technologies Used

- Python 3.x
- OpenCV
- face_recognition (dlib-based)
- NumPy
- Pandas
- Tkinter / Streamlit (for GUI)

---

## 🧠 How It Works

1. **Registration**
   Add face images to the `images/` folder with filenames as the person's name (e.g., `John.jpg`). These images are encoded and stored.

2. **Recognition & Attendance**
   The webcam stream is analyzed in real-time. If a registered face is recognized, their attendance is marked in a CSV file (`Attendance.csv`) with:

   * Name
   * Date
   * Time

---

## ▶️ Usage

```bash
python main.py
```

You’ll see the webcam window pop up. When a known face is detected:

* A box is drawn around the face
* The name is displayed
* Attendance is marked

---

## 📂 Project Structure

```bash
Attendance-System-CV/
│
├── images/                  # Registered face images
├── AddDataToDatabase.py     # Add to Database
├── EncodeGenerator.py       # Encode known face images
├── main.py                  # Main attendance app
├── EncodeFile.p             # Helper functions (load/save, timestamp, etc.)
└── README.md                # Project documentation
```

---

## 📈 Future Enhancements

* GUI dashboard (Tkinter)
* Email/SMS alerts
* Face mask detection

---

## 👨‍💻 Author

**Rahul Kumar**
📧 [rahul.3550kumar@gmail.com](mailto:rahul.3550kumar@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/rahul-kumar-98666624b/) | [GitHub](https://github.com/Rahul-kumar999)

---

> “Technology will not replace great teachers, but technology in the hands of great teachers can be transformational.” — George Couros

```
