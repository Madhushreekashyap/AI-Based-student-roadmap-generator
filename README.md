.

🚀 AI-Based Student Roadmap Generator








📌 Project Overview

The AI-Based Student Roadmap Generator is a Python-based application that dynamically generates personalized learning roadmaps based on a student's selected skill and proficiency level.

The system is designed using Object-Oriented Programming (OOP) principles and stores structured data using JSON for persistence.

This project demonstrates backend logic development, modular programming, and real-world problem-solving skills.

🎯 Problem Statement

Students often struggle to identify a clear and structured path when learning new skills.

This project solves that problem by:

Accepting user details (USN, Name, Phone)

Taking skill and learning level as input

Generating a customized roadmap

Storing structured roadmap data in JSON format

Maintaining persistent student records

🛠️ Technologies Used

Python 3

Object-Oriented Programming (OOP)

JSON Module

File Handling

Datetime Module

Exception Handling

🧠 Key Features

✅ Student profile creation
✅ Skill-based roadmap generation
✅ Beginner / Intermediate / Advanced levels
✅ JSON-based data persistence
✅ Modular class-based design
✅ Supports multiple students
✅ Clean and scalable architecture

🏗️ Project Architecture

The project is divided into three main components:

1️⃣ StudentProfile Class

Stores student details

Converts data into dictionary format

2️⃣ RoadmapGenerator Class

Generates dynamic learning steps

Handles multiple skills (Python, AI, Cybersecurity)

Supports multiple learning levels

3️⃣ DataManager Class

Reads existing JSON data

Saves new roadmap data

Handles file-related exceptions

📂 Project Structure
AI-Roadmap-Generator/
│
├── main.py
├── student_roadmaps.json
└── README.md

▶️ How to Run the Project
🔹 Option 1: Google Colab

Open Google Colab

Create a new notebook

Paste the Python code

Run the cell

Enter required inputs when prompted

🔹 Option 2: Run Locally

Install Python 3

Save the file as main.py

Run:

python main.py

📂 Sample Output
{
    "profile": {
        "usn": "4JT22CS001",
        "name": "Madhushree",
        "phone": "9876543210"
    },
    "roadmap": {
        "skill": "python",
        "level": "beginner",
        "created_at": "2026-02-18",
        "steps": [
            "Learn Python Basics",
            "Practice Data Types",
            "Control Flow",
            "Functions",
            "Mini Project"
        ]
    }
}

📈 Learning Outcomes

Through this project, I strengthened my understanding of:

Real-world application of OOP

Data structuring using JSON

File-based persistence

Clean and modular code design

Backend logic implementation

Dynamic content generation

🔮 Future Enhancements

Integrate SQLite database

Convert into a web application using Flask

Add AI-based skill recommendation logic

Implement authentication system

Deploy as a cloud-hosted service

💼 Use Case Applications

Personalized learning platforms

EdTech applications

AI-powered skill recommendation systems

Backend roadmap management tools

👩‍💻 Author

Madhushree M
Computer Science Engineering Student
CGPA: 9.2
Interested in AI/ML and Backend Development

⭐ Support

If you found this project useful:

Star ⭐ the repository

Fork 🍴 the project

Share your feedback
