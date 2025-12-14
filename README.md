Project Description

AI Code Review Assistant is a web-based system designed to automatically analyze source code and provide actionable feedback.
This Phase 1 implementation focuses on static code analysis for bug detection, security vulnerabilities, code quality assessment, and basic optimization suggestions.

The system allows users to register, log in, upload or paste code, and receive structured analysis results through a simple dashboard interface.
It is built as a single integrated application using Flask, SQLite, and Python’s AST and regex-based analysis techniques.

This project demonstrates how automated tools can assist developers in improving code reliability, security, and maintainability during early development stages.

 Features (Phase 1)

User authentication (Register / Login / Logout)

Upload source code files or paste code directly

Bug detection

Syntax errors

Potential runtime issues

Unused variables

Security analysis

SQL injection patterns

Hardcoded secrets

Unsafe eval or shell execution

Code quality assessment

Line length checks

Structural analysis

Basic complexity review

Optimization suggestions

Python best practices

Code smell detection

Clean dashboard UI with result categorization

SQLite-based local database

🛠️ Tech Stack

Backend: Python, Flask

Frontend: HTML, CSS, JavaScript (embedded templates)

Database: SQLite

Project Structure
AI-Code-Review-Assistant/
│
├── main.py                # Complete application (backend + frontend)
├── users.db               # SQLite database (auto-generated)
├── uploads/               # Temporary upload directory
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies (optional)

How to Run the Project 
git clone https://github.com/your-username/AI-Code-Review-Assistant.git
cd AI-Code-Review-Assistant

Install Dependencies
pip install flask
Run the Application
python main.py
Access in Browser
http://localhost:5000
Default Test Login
Username: admin
Password: password123

Phase 1 Scope Clarification

This phase focuses on:

Rule-based static analysis

Local execution

Single-language (Python-focused) support

Monolithic architecture for simplicity

Advanced AI models, ML-based reasoning, cloud deployment, and multi-language support are planned for later phases.

 Future Enhancements (Phase 2 Ideas)

LLM-based code reasoning and explanations

Multi-language support (Java, C++, JavaScript)

PDF and GitHub repo analysis

Dockerized deployment

Role-based access

Report export (PDF/JSON)

CI/CD integration

 Academic Note

This project is developed as a Final Year Engineering Project – Phase 1 and is intended to demonstrate practical software engineering skills, secure coding practices, and applied program analysis concepts.

 License

This project is for academic and educational use.

Code Analysis: Python AST, Regex

Authentication: Session-based login
