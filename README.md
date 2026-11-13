# SnapClass – No Proxies. Just Presence. 🎓
🚀 **Live Demo:** https://snapclass-landing-page-resume-mu.vercel.app

💻 **GitHub:** https://github.com/pinkbyjiya/snapclass-NO-proxies-just-presence

**AI-Powered Smart Attendance Management System**

SnapClass is an AI-powered classroom attendance system designed to solve one of the most common problems in educational institutions: **proxy attendance**.

Traditional attendance methods are time-consuming, interrupt classroom sessions, and make it easy for students to mark attendance on behalf of absent classmates.

SnapClass aims to eliminate proxy attendance by using AI-powered face recognition and voice-based attendance processing to make classroom attendance faster, smarter, and more reliable.

The goal is simple: **Save classroom time. Reduce manual effort. Ensure genuine attendance.**

---

## 🚀 Key Features

- **AI-Powered Face Recognition:** Uses facial recognition technology to identify enrolled students during attendance.
- **Voice-Based Attendance:** Processes voice input to support an alternative attendance workflow.
- **Proxy Attendance Prevention:** Helps ensure that attendance is associated with the actual enrolled student rather than manual marking by someone else.
- **Automated Attendance Processing:** Reduces repetitive manual work for teachers.
- **Student Enrollment:** Allows students to be enrolled and their relevant information to be managed.
- **Subject Management:** Teachers can create and manage subjects.
- **Attendance Results:** Provides attendance processing results through dedicated interfaces.
- **Interactive Dashboard:** Separate interfaces for teachers and students.

## 🧠 AI & Technical Concepts

SnapClass brings together concepts from Artificial Intelligence, Machine Learning, and application development.

The project involves:

- **Computer Vision:** Processing facial information for student identification.
- **Face Recognition:** Matching captured facial information against enrolled student records.
- **Machine Learning:** Applying recognition and classification techniques as part of the identification workflow.
- **Voice Processing:** Processing voice input for an alternative attendance workflow.
- **Automated Data Processing:** Connecting AI pipelines with attendance management and database operations.

*The exact model architecture and classifier names should be documented according to the implementations in the face and voice pipelines.*

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core application development |
| Streamlit | Interactive web application |
| Computer Vision | Facial recognition workflow |
| Machine Learning | AI-based identification |
| Voice Processing | Voice-based attendance workflow |
| Supabase | Backend database and data management |
| Git & GitHub | Version control and collaboration |

## 📂 Project Structure

```text
SnapClass/
│
├── app.py
├── requirements.txt
├── .gitignore
│
├── src/
│   ├── components/
│   │   ├── dialog_add_photo.py
│   │   ├── dialog_attendance_results.py
│   │   ├── dialog_auto_enroll.py
│   │   ├── dialog_create_subject.py
│   │   ├── dialog_enroll.py
│   │   ├── dialog_share_subject.py
│   │   ├── dialog_voice_attendance.py
│   │   └── subject_card.py
│   │
│   ├── database/
│   │   ├── config.py
│   │   └── db.py
│   │
│   ├── pipelines/
│   │   ├── face_pipeline.py
│   │   └── voice_pipeline.py
│   │
│   ├── screens/
│   │   ├── student_screen.py
│   │   └── teacher_screen.py
│   │
│   └── ui/
│       └── base_layout.py
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/pinkbyjiya/snapclass-NO-proxies-just-presence.git
```

### 2. Navigate to the project directory

```bash
cd snapclass-NO-proxies-just-presence
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Mac/Linux**
```bash
source venv/bin/activate
```

**Windows**
```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure environment secrets

Create a `.streamlit/secrets.toml` file and configure the required credentials:

```toml
SUPABASE_URL = "your_supabase_url"
SUPABASE_KEY = "your_supabase_key"
```

Add any additional API credentials required by your configured AI services.

Never commit your actual credentials or secrets to GitHub.

### 6. Run the application

```bash
streamlit run app.py
```

The application will be available locally at:

```text
http://localhost:8501
```

## 🎯 Problem We Are Solving

Proxy attendance is a recurring problem in classrooms. Teachers spend valuable teaching time calling out names, verifying students, and manually recording attendance.

SnapClass addresses this problem through AI-powered attendance workflows.

Our objectives are to:

- Minimize opportunities for proxy attendance.
- Reduce the time required for attendance.
- Automate repetitive attendance-related tasks.
- Improve the reliability of classroom attendance records.
- Provide a simpler experience for both teachers and students.

## 🔮 Future Scope

- Improve recognition accuracy under different lighting conditions.
- Add liveness detection to strengthen protection against photo-based spoofing.
- Improve voice recognition and verification.
- Generate attendance analytics and detailed reports.
- Introduce additional integrations with educational management systems.
- Improve scalability for larger classrooms and institutions.

## 👩‍💻 Project

**SnapClass – No Proxies. Just Presence.**

Built with Python, Streamlit, AI, Machine Learning, and Supabase.



*Making classroom attendance faster, smarter, and more reliable — one class at a time.*


## What I Learned

Building SnapClass gave me hands-on experience with:

- **Python:** Modular programming, application logic, exception handling and debugging.
- **Computer Vision:** Face detection, image processing and face recognition workflows.
- **Machine Learning:** Integrating AI/ML techniques into real-world applications.
- **Audio Processing:** Working with voice-based attendance workflows.
- **Supabase:** Database connectivity, storing and retrieving records.
- **Streamlit:** Building interactive web applications and managing application state.
- **Software Architecture:** Modular project structure and separation of concerns.
- **Git & GitHub:** Version control, commits and repository management.
- **Deployment:** Deploying applications and managing configuration and secrets.

**Key Takeaway:** Learned how to build, integrate, debug and deploy an end-to-end application while solving a real-world problem.
