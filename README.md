# 📚 Study Management System

## 📌 Project Overview

The **Study Management System** is a database-driven project designed to organize and manage students' study activities. It stores user information, tracks study sessions, manages exams and questions, and records exam results.

The project uses an SQLite database to store and retrieve information efficiently.

## 🎯 Objectives

- Manage user information.
- Track daily study activities and duration.
- Organize subjects and topics.
- Maintain study completion status.
- Store exam details and multiple-choice questions.
- Record exam scores and results.

## 🛠️ Technologies Used

- **Database:** SQLite
- **Query Language:** SQL
- **Database File:** `study(1).db`

## 🗄️ Database Structure

The database contains five tables:

| Table Name | Description |
|---|---|
| `users` | Stores user account information. |
| `study_logs` | Records study dates, duration, subjects, topics, and status. |
| `exams` | Stores exam names and associated subjects. |
| `exam_questions` | Stores questions, four options, and correct answers. |
| `exam_results` | Records exam scores, total marks, dates, and users. |

## ⚙️ Key Features

### 1. User Management
Stores user account details and associates study activities with individual users.

### 2. Study Tracking
Maintains study records, including:
- Study date
- Study duration
- Subject name
- Topic name
- Completion status

### 3. Exam Management
Stores exam names and subjects to support exam organization.

### 4. Question Management
Maintains multiple-choice questions with four options and the correct answer.

### 5. Result Management
Stores exam scores, total marks, exam dates, and the usernames associated with results.

## 📂 Project Structure

```text
Study-Management-System/
│
├── study(1).db
└── README.md
```

*Note: This structure represents the files currently identified. Add your application source files if they are part of the project.*

## 🚀 Getting Started

### Prerequisites
- A computer with SQLite support.
- An SQLite database viewer or SQLite command-line tool.

### Steps to Run

1. Clone or download this repository.
2. Open the project folder.
3. Open `study(1).db` using an SQLite database viewer, such as DB Browser for SQLite.
4. Explore the tables and execute SQL queries to retrieve or analyze study records.

## 💡 Learning Outcomes

- Understanding relational database design.
- Creating and managing tables using SQL.
- Storing and retrieving structured data.
- Organizing data using primary keys.
- Designing a database for study tracking and exam management.

## 🔮 Future Enhancements

- Build a web interface for students.
- Add secure user registration and login.
- Generate study progress reports.
- Add exam scheduling and automated evaluation.
- Create dashboards to visualize study hours and exam performance.
- Improve database relationships using foreign keys.

