# SpaceTwin Classroom: Google Classroom Integration 🎓

A full classroom-management web app that connects **SpaceTwin**, an immersive virtual workspace platform, to **Google Classroom** and the wider Google Workspace. Teachers and students can manage courses, assignments, quizzes, grades and files without leaving SpaceTwin.

It integrates **five Google APIs**: Classroom, Drive, Forms, Sheets and Gmail.

<!-- Add screenshots here, e.g. ![Dashboard](./screenshots/dashboard.png) -->

---

## Features

**🔐 Sign-in and roles**
- Google sign-in with OAuth 2.0, plus automatic token refresh and retry
- Role-based interface: teachers and students see different tools for each course

**📚 Courses and people**
- List, create and delete courses
- View the class roster and add students

**📝 Assignments and submissions**
- Create, edit and delete coursework
- Students submit answers and file attachments
- Teachers view submissions with status filters, grade them, and **bulk-grade** several at once

**❓ Quizzes (Google Forms)**
- Build quizzes in the app with multiple question types
- View and export responses, then **sync quiz grades back to Classroom**

**📊 Gradebook (Google Sheets)**
- Auto-generated gradebook spreadsheet for each course, plus an analytics sheet
- Letter grades, **grade curves and weighted grades**
- Export to CSV

**📁 File organization (Google Drive)**
- Creates a tidy `SpaceTwin Classroom / Course / Assignment` folder structure automatically
- Upload attachments, pick files from Drive, and migrate existing files into the structure

**📧 Notifications (Gmail)**
- Email grade notifications, assignment reminders and progress reports, individually or in bulk
- Configurable notification settings

---

## Tech Stack

| Area | Tools |
|------|-------|
| Languages | JavaScript (ES6+, async/await), HTML5, CSS3 |
| Google APIs | Classroom API, Drive API, Forms API, Sheets API, Gmail API |
| Auth | Google Identity Services (OAuth 2.0), Google API Client (gapi) |

About 7,500 lines of JavaScript, split into focused modules: `auth`, `courses`, `coursework`, `submissions`, `forms`, `gradebook`, `drive-utils`, `notifications` and more.

---

## Code
> 🔒 **About the code:** this project was built during my work at SpaceTwin, and the source code belongs to the company, so it isn't published here. This page describes what I built. I'm happy to walk through it in an interview.

---

## Author

**Sariya Al Jaber**, Frontend Developer<br>
📧 sariajabr@gmail.com · 🐙 [@eng-sariya1](https://github.com/eng-sariya1)

