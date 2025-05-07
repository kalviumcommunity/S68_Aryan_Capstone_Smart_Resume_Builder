# 🧠 Smart Resume Builder

A full-stack capstone project that helps users create professional, personalized resumes with the help of smart AI features like real-time suggestions, resume scoring, and dynamic templates. This project includes a frontend form, backend APIs, resume scoring logic, PDF export, and progress tracking via GitHub Projects.

---

## 🚀 Features

- ✅ Easy-to-use form to collect user resume data (Personal Info, Education, Experience, etc.)
- 🧠 AI-powered suggestions for improving resume quality (OpenAI API or mock data)
- 📊 Resume scoring based on completeness and formatting best practices
- 📄 Live resume preview
- 🖨️ Export to PDF
- ⚙️ Backend APIs to handle data submission and scoring
- 🧪 Input validation and bug fixes
- 🔁 GitHub Project board tracking for 10+ days
- 🎥 Demo video explaining development journey

---

## 🧱 Tech Stack

| Layer        | Technology                        |
|--------------|-----------------------------------|
| Frontend     | HTML/CSS + JavaScript **or** React.js |
| Backend      | Python Flask **or** Node.js + Express |
| Storage      | Local JSON (optional: MongoDB/Firebase) |
| AI/NLP       | OpenAI API (or static mock responses) |
| PDF Export   | jsPDF / html2pdf.js               |
| Deployment   | Vercel (Frontend), Render/Heroku (Backend) |

---

## 📂 Folder Structure
---

## 🗓️ GitHub Projects: Progress Tracking

This project was managed using **GitHub Projects** over a period of **10+ days**, with daily task tracking and status updates.

🗂️ Project Board includes:
- ✅ Task breakdown from planning to completion
- 🔄 Daily movement of tasks across To Do, In Progress, and Done
- 📝 Comments on each card showing date and work summary

📸 Proof:
- Screenshots are saved in `/docs/progress`
- Demo video walkthrough provided

---

## ✅ 10 Daily Tracked Tasks

| Day | Task                                               |
|-----|----------------------------------------------------|
| 1   | Project planning & folder structure setup          |
| 2   | Build basic frontend layout                        |
| 3   | Create resume form (HTML or React)                 |
| 4   | Setup backend server (Flask or Node.js)            |
| 5   | Connect frontend with backend API (POST resume)    |
| 6   | Live preview of resume + export to PDF             |
| 7   | Add AI suggestion API route (mock or OpenAI)       |
| 8   | Add resume scoring logic in backend                |
| 9   | Bug fixes, input validation                        |
| 10  | GitHub Project review + final demo recording       |

---

## 💻 How to Run Locally

### ⚙️ Backend (Flask)

```bash
cd server
pip install -r requirements.txt
python app.py