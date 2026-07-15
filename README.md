# Humanoid-Robot-as-an-Assistant-Physiotherapist-project
# 🤖 Humanoid Robot as an Assistant Physiotherapist

An interactive rehabilitation system developed using the **NAO Humanoid Robot** to assist patients recovering from upper-limb fractures through guided physiotherapy exercises.

The robot acts as an assistant physiotherapist by demonstrating rehabilitation exercises, interacting with patients through speech, and providing motivational feedback throughout the therapy session.

---

## 📖 Project Overview

Physiotherapy is essential after bone fractures, especially for restoring elbow and finger movement. However, many patients struggle with:

- Limited access to physiotherapists
- Lack of motivation
- Performing exercises incorrectly
- Repetitive and monotonous rehabilitation sessions

This project addresses these challenges by using the **NAO Humanoid Robot** to provide an interactive rehabilitation experience.

The robot guides patients through rehabilitation exercises, communicates naturally using voice interaction, and provides encouragement and feedback to improve engagement during recovery.

---

## 🎯 Objectives

- Assist patients during post-fracture rehabilitation
- Demonstrate upper-limb exercises safely
- Improve patient motivation through interactive communication
- Simulate a physiotherapy session using a humanoid robot
- Explore the use of social robotics in healthcare

---

## 🦾 Features

- Interactive patient greeting
- Voice-guided rehabilitation session
- Finger stretching exercise
- Elbow and finger rehabilitation exercise
- Leg exercise demonstration
- Real-time verbal encouragement
- Patient feedback interaction
- Yes/No decision making using Choice Blocks
- Smooth robotic movements using Timeline animation
- Session completion message with feedback reminder

---

## 🏗️ System Workflow

```
Patient Arrives
        │
        ▼
NAO Greets Patient
        │
        ▼
Ask: "Are you ready?"
        │
   Yes / No
        │
        ▼
Exercise Demonstration
        │
        ▼
Robot Encourages Patient
        │
        ▼
Session Complete
        │
        ▼
Feedback & QR Code Reminder
```

---

## ⚙️ Technologies Used

| Technology | Purpose |
|------------|----------|
| NAO Humanoid Robot | Rehabilitation Assistant |
| Choregraphe | Robot Programming |
| Timeline Editor | Motion Design |
| Say Text | Speech Output |
| Text Editor | Dialogue Management |
| Choice Block | User Interaction |
| Switch Case | Decision Flow |

---

# 📂 Project Structure

```
Humanoid-Robot-as-an-Assistant-Physiotherapist/
│
├── Choregraphe Project
├── Exercise Timelines
│   ├── Finger Exercise
│   ├── Elbow + Finger Exercise
│   └── Leg Exercise
│
├── Robot Dialogues
├── Feedback Module
├── Images
├── Documentation
└── README.md
```

---

# 🚀 Setup

## Requirements

- NAO Humanoid Robot
- Choregraphe Software
- NAOqi SDK
- Windows or Linux
- Same network connection for PC and NAO

---

## Installation

### Clone the repository

```bash
git clone https://github.com/berry1200/Humanoid-Robot-as-an-Assistant-Physiotherapist-project.git
```

```bash
cd Humanoid-Robot-as-an-Assistant-Physiotherapist-project
```

---

### Open in Choregraphe

1. Launch Choregraphe.
2. Open the project (.pml or project folder).
3. Connect Choregraphe to the NAO Robot.
4. Verify the robot connection.

---

### Deploy

Click **Run** inside Choregraphe to upload and execute the project on the robot.

---

## ▶️ Running the Project

1. Power on the NAO robot.
2. Connect the robot to the same network.
3. Launch Choregraphe.
4. Connect to the robot.
5. Open the project.
6. Press **Run**.

The robot will:

- Welcome the patient
- Ask if they are ready
- Demonstrate exercises
- Encourage the patient
- Complete the session
- Request feedback

---

# 🧠 Exercise Flow

### Greeting

```
Hello!
Welcome to the Physiotherapy Center.
I am NAO.
```

↓

### Readiness Check

```
Are you ready to begin?
```

↓

### Exercise Demonstration

- Finger Stretching
- Elbow Movement
- Finger Movement
- Leg Exercise

↓

### Motivation

```
Great job!
Keep going.
You're doing well.
```

↓

### Session Completion

```
Thank you for completing today's rehabilitation session.
Please remember to leave your feedback.
```

---

# 💡 Key Contributions

This project includes:

- Rehabilitation exercise design
- Human-Robot Interaction (HRI)
- Motion programming using Timeline
- Interactive dialogue system
- Decision-based conversation
- Patient feedback workflow

---

# 📊 Applications

- Physiotherapy Clinics
- Hospitals
- Rehabilitation Centers
- Home-Based Therapy
- Elderly Care
- Healthcare Robotics Research

---

# 🔒 Ethical Considerations

- Safe joint movement
- Respectful patient interaction
- No personal data collection
- Simple and accessible language
- Privacy-aware feedback process

---

# 🔮 Future Improvements

- AI-based motion analysis
- Computer vision for posture tracking
- Real-time correction of exercises
- Emotion recognition
- Multiple language support
- Personalized rehabilitation plans
- Cloud-based patient progress tracking
- Integration with wearable sensors

---

# 👨‍💻 Team

- **Berry James**
- Devika Gopalakrishnan Pillai
- Abhishek Devaraj

---

# 📚 References

This project was developed as part of the **Applications for Social and Service Robots (ENG7007)** module and is based on research in:

- Human-Robot Interaction
- Socially Assistive Robotics
- Physiotherapy Robotics
- Healthcare Automation

---

# 📹 Demo

YouTube:

https://youtu.be/Hj2WT37rekw?si=4ZJZFAEtGXLTvUbG

---

# ⭐ Repository

https://github.com/berry1200/Humanoid-Robot-as-an-Assistant-Physiotherapist-project

---

## 📄 License

This project is intended for academic and research purposes.
