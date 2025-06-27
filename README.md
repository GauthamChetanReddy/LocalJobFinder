# LocalJobFinder
Local Job Finder is a Java-based desktop application that connects daily wage workers with local employers. It features login/signup, job posting, application tracking, and job filtering. Built using Swing GUI, it uses file-based storage for managing users, jobs, and applications.



# 🛠️ Local Job Finder for Daily Wage Workers

A Java-based GUI + CLI application that connects **daily wage workers** with **local job providers**. Built using **Swing for GUI**, and includes file-based storage for simplicity.

---

## 📋 Features

### 👷 Worker:
- View available local jobs
- Apply to jobs
- View application status
- Filter jobs by category/location

### 🧑‍💼 Employer:
- Post jobs
- View applicants for posted jobs
- Accept/Reject applicants (optional feature)

---

## 🖥️ Tech Stack

- **Java (JDK 8 or higher)**
- **Swing** for GUI
- **Text files** (`.txt`) for persistence
- **Modular codebase**: OOPs-based with MVC-like structure

---

## 🗂️ Project Structure
LOCALJOBFINDER/
├── model/ # Data classes: User, Worker, Employer, Job, Application
├── service/ # Business logic: AuthService, JobBoard, FileManager
├── ui/ # GUI: LoginPanel, RegisterPanel, Dashboards, etc.
├── data/ # Flat file storage (auto-created): users.txt, jobs.txt, applications.txt
├── TestAuth.java # CLI tester (optional)
└── MainWindow.java # Main GUI launcher



---

## 🚀 Getting Started

### 🧱 Requirements:
- Java JDK 8 or higher
- Text editor or IDE (e.g., VS Code, IntelliJ, Eclipse)

###Make sure you have:
LOCALJOBFINDER/
└── data/
    ├── users.txt
    ├── jobs.txt
    └── applications.txt
    
####Default Login
User ID: U1
Password: pass123

User ID: E2
Password: pass123


### 💻 Run via CLI:
```bash
# Compile
javac --release 8 model/*.java service/*.java ui/*.java MainWindow.java

# Run GUI
java MainWindow

# Or run CLI tester
javac TestAuth.java
java TestAuth
