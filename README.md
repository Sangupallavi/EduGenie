**Edugenie**

**Repository Structure**

1.Brainstorming & Ideation

2.Requirement Analysis

3.Project Design Phase

4.Project Planning Phase

5.Project Development Phase

6.Project Testing

7.Project Documentation

8.Project Demonstration

Replace the placeholder files with your team's project deliverables.


# 🚀 EduGenie – AI-Powered Educational Assistant

EduGenie is an AI-powered educational assistant developed using **Python**, **FastAPI**, **Google Gemini AI**, **HTML**, **CSS**, and **JavaScript**. The application is designed to help students learn more effectively by providing intelligent answers to academic questions, generating quizzes, summarizing study materials, and recommending personalized learning resources.

EduGenie combines Artificial Intelligence with a clean and user-friendly interface to make learning interactive, efficient, and engaging.

---

# 📖 Table of Contents

- Project Overview
- Features
- Technology Stack
- Project Architecture
- Project Structure
- Installation Guide
- Configuration
- Running the Application
- Application Workflow
- Screenshots
- Future Enhancements
- Challenges Faced
- Learning Outcomes
- Author
- Acknowledgements

---

# 📌 Project Overview

Education is becoming increasingly digital, and students often need quick access to reliable explanations, summaries, and self-assessment tools.

EduGenie addresses this need by integrating Google's Gemini AI into a web application that allows users to:

- Ask academic questions
- Understand difficult concepts
- Generate quizzes
- Summarize lengthy study materials
- Receive personalized learning recommendations

The application is built using FastAPI for the backend and Jinja2 templates for rendering dynamic web pages.

---

# ✨ Features

### 🤖 AI Question Answering

Students can ask any educational question and receive intelligent AI-generated responses.

---

### 📝 AI Quiz Generator

Generate multiple-choice quizzes by entering:

- Topic
- Difficulty Level (Easy / Medium / Hard)

The AI creates questions with multiple options and answers.

---

### 📄 AI Text Summarizer

Convert lengthy notes or study material into concise summaries for quick revision.

---

### 🎯 Personalized Learning Recommendations

Receive AI-generated suggestions including:

- Topics to study
- Learning roadmap
- Recommended concepts
- Study guidance

---

### 🎨 Modern User Interface

- Responsive Design
- Attractive Layout
- Easy Navigation
- Professional Color Theme

---

### ⚡ FastAPI Backend

The backend is built using FastAPI with modular routing and service architecture.

---

# 🛠 Technology Stack

## Frontend

- HTML5
- CSS3
- JavaScript
- Jinja2 Templates

## Backend

- Python
- FastAPI
- Uvicorn

## Artificial Intelligence

- Google Gemini API

## Environment

- python-dotenv

---

# 🏗 Project Architecture

```
                 User

                   │

                   ▼

            HTML + CSS + JS

                   │

                   ▼

              FastAPI Router

                   │

                   ▼

           Gemini Service Layer

                   │

                   ▼

            Google Gemini API

                   │

                   ▼

             AI Generated Output
```

---

# 📂 Project Structure

```
EduGenie/

│

├── routers/
│   ├── chat.py
│   ├── quiz.py
│   ├── summary.py
│   └── recommendation.py
│
├── services/
│   └── gemini_service.py
│
├── static/
│   ├── css/
│   │   ├── style.css
│   │   ├── ask.css
│   │   ├── quiz.css
│   │   ├── summary.css
│   │   └── recommendation.css
│   │
│   ├── js/
│   │
│   └── images/
│
├── templates/
│   ├── home.html
│   ├── ask.html
│   ├── quiz.html
│   ├── summary.html
│   └── recommendation.html
│
├── main.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

---

# ⚙ Installation Guide

## 1. Clone the Repository

```bash
git clone https://github.com/Sangupallavi/EduGenie.git
```

---

## 2. Open the Project

```bash
cd EduGenie
```

---

## 3. Create a Virtual Environment

Windows

```bash
python -m venv venv
```

Linux/macOS

```bash
python3 -m venv venv
```

---

## 4. Activate the Virtual Environment

Windows

```bash
venv\Scripts\activate
```

Linux/macOS

```bash
source venv/bin/activate
```

---

## 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Configuration

Create a `.env` file inside the project directory.

Example:

```env
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

> **Note:** Never upload your `.env` file to GitHub. Ensure it is listed in `.gitignore`.

---

# ▶ Running the Application

Start the FastAPI development server:

```bash
uvicorn main:app --reload
```

Open your browser:

```
http://127.0.0.1:8000
```

---

# 🔄 Application Workflow

## Home Page

Displays project overview and navigation to all AI features.

↓

## Ask AI

User enters an academic question.

↓

Gemini AI processes the question.

↓

AI-generated response is displayed.

---

## Quiz Generator

User enters:

- Topic
- Difficulty Level

↓

Gemini AI generates:

- Multiple Choice Questions
- Options
- Answers

↓

Quiz is displayed.

---

## Summary Generator

User pastes study material.

↓

Gemini AI summarizes the content.

↓

Concise summary is displayed.

---

## Recommendation System

User enters a learning topic.

↓

Gemini AI recommends:

- Study Roadmap
- Important Concepts
- Learning Strategy

↓

Recommendations are displayed.

---

# 📸 Screenshots

Add screenshots of your application here after uploading them to GitHub.

Example:

```
screenshots/
    home.png
    ask.png
    quiz.png
    summary.png
    recommendation.png
```

You can then include them like this:

```markdown


<img width="1366" height="768" alt="Screenshot (428)" src="https://github.com/user-attachments/assets/52cc069a-ed4b-4946-8cb6-3d8f04bc98bd" />
<img width="1366" height="768" alt="Screenshot (429)" src="https://github.com/user-attachments/assets/23c5867e-9490-46a8-b070-bbdf7125e531" />



## Ask AI

<img width="1366" height="768" alt="Screenshot (430)" src="https://github.com/user-attachments/assets/62995885-0381-413b-b069-5dc6fa07272a" />


## Quiz

<img width="1366" height="768" alt="Screenshot (431)" src="https://github.com/user-attachments/assets/70381e6f-b5f4-4cc8-883a-b505c446db4b" />


## Summary

<img width="1366" height="768" alt="Screenshot (432)" src="https://github.com/user-attachments/assets/dc884e1a-8259-411d-85a6-e0d79e100d23" />


## Recommendations

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/37a1c752-862b-4c06-9bb3-2e3d2501d5eb" />

```

---

# 🚀 Future Enhancements

- User Authentication
- Quiz Score Evaluation
- Download Quiz as PDF
- Download Summary as PDF
- Learning History
- Progress Dashboard
- Voice Assistant
- Multi-language Support
- AI Chat History
- Database Integration

---

# 💡 Challenges Faced

During the development of EduGenie, several challenges were encountered:

- Integrating Google Gemini API
- Managing API quota limitations
- Building modular FastAPI routes
- Creating responsive UI for multiple pages
- Designing reusable frontend components
- Handling AI-generated responses effectively

These challenges helped improve understanding of AI integration, backend development, and full-stack application design.

---

# 🎯 Learning Outcomes

Through this project, the following skills were strengthened:

- FastAPI Development
- REST API Design
- Python Programming
- AI Integration using Gemini API
- HTML, CSS, and JavaScript
- Responsive Web Design
- Jinja2 Templates
- Environment Variable Management
- Modular Project Structure
- Git and GitHub Workflow

---

# 👩‍💻 Author

**Sangu Pallavi**

B.Tech Student

Aspiring Software Engineer

Interested in:

- Artificial Intelligence
- Full Stack Development
- Python Development
- Machine Learning
- Software Engineering

---

# 🙏 Acknowledgements

This project was developed using the following technologies and tools:

- Python
- FastAPI
- Google Gemini AI
- HTML5
- CSS3
- JavaScript
- Jinja2
- Uvicorn
- VS Code

---

# 📜 License

This project is developed for educational and learning purposes.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Your support is appreciated!
