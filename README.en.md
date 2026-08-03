<div align="center">

[![Русский](https://img.shields.io/badge/Русский-2b3137?style=for-the-badge&logoColor=white)](README.md)
[![Тоҷикӣ](https://img.shields.io/badge/Тоҷикӣ-2b3137?style=for-the-badge&logoColor=white)](README.tg.md)
[![English](https://img.shields.io/badge/English-6C4CF1?style=for-the-badge&logoColor=white)](README.en.md)

<br>

# Moodle.tj

### Learning platform for Tajikistan

Courses and lessons, quizzes and assignments, a built-in code compiler,
auto-graded programming tasks, an AI tutor, forums and student-retention
analytics — in one system.

<br>

[![Open moodle.tj](https://img.shields.io/badge/Live%20site-moodle.tj-6C4CF1?style=for-the-badge&logo=googlechrome&logoColor=white)](https://moodle.tj/)

<br>

[![Status](https://img.shields.io/badge/Status-In%20production-34A853?style=flat-square)](https://moodle.tj/)
![Source code](https://img.shields.io/badge/Source%20code-not%20available-lightgrey?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.14-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram%20Bot-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Languages](https://img.shields.io/badge/Interface-RU%20%7C%20TJ-6C4CF1?style=flat-square)

**[Live site](https://moodle.tj/) · [Screenshots](#screenshots) · [Features](#features) · [Tech stack](#tech-stack) · [Hire me](#hire-me)**

</div>

---

## Live in production

> The platform is deployed and serving real students:
> **[moodle.tj](https://moodle.tj/)**
>
> This is not a mockup or a tutorial project — courses are running,
> students solve tasks and receive notifications.

| Item | Value |
|---|---|
| Address | [moodle.tj](https://moodle.tj/) |
| Type | LMS — learning management system |
| Interface | Russian and Tajik |
| Roles | Student, teacher, administrator |
| Access | Free and premium courses |

---

## This is a showcase, not the source code

> This repository contains **no source code** — only a description and
> screenshots of the running platform.
>
> **Moodle.tj is a closed commercial project.** The code lives in a private
> repository, is not open-source and may not be downloaded, copied or reused.
>
> This page exists to present completed work. If you need a platform like
> this, it can be **commissioned**.

---

## Screenshots

<table>
<tr>
<td width="50%" valign="top">

### Home page

Landing screen with live platform statistics: number of courses,
students and rating. Dark theme, language switcher
and global search in the header.

<img src="docs/screenshots/01-home.png" alt="Home page">

</td>
<td width="50%" valign="top">

### Course catalogue

Search by title, filters by category and difficulty level.
Each card shows the category, author, duration, student count
and price.

<img src="docs/screenshots/02-courses.png" alt="Course catalogue">

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Course page

Instructor, duration, number of students and lessons.
A personal progress bar, the full syllabus with expandable lessons
and tabs for syllabus, description and forum.

<img src="docs/screenshots/03-course-detail.png" alt="Course page">

</td>
<td width="50%" valign="top">

### Lesson

Lesson content with rich formatting and syntax highlighting.
On the right — the course outline with progress; lessons available
only with a premium subscription are marked with a lock.

<img src="docs/screenshots/04-lesson.png" alt="Lesson">

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Built-in compiler

The lesson and the code editor share one screen — nothing to install.
Personal files are stored in the account and the program output
appears right there.

<img src="docs/screenshots/05-compiler.png" alt="Built-in compiler">

</td>
<td width="50%" valign="top">

### Programming task

Statement, input and output format, worked examples.
"Run" executes against your own input, "Check" runs the solution
against the full test suite.

<img src="docs/screenshots/06-coding-task.png" alt="Programming task">

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Automatic grading

The submission is executed against every test case on the server.
The next lesson unlocks only after a successful submission —
copying someone else's answer will not work.

<img src="docs/screenshots/07-ai-judge.png" alt="Automatic code grading">

</td>
<td width="50%" valign="top">

### Analytics and churn risk

Who is studying, who is about to drop out and how reminders perform.
Activity by weekday, average progress, students grouped by risk level
and CSV export.

<img src="docs/screenshots/08-analytics.png" alt="Analytics">

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Reminder campaigns

Automatic emails to students who stopped studying.
Four ready-made email designs, frequency capping
and quiet hours so nobody gets spammed.

<img src="docs/screenshots/09-campaigns.png" alt="Reminder campaigns">

</td>
<td width="50%" valign="top">

### Email preview

Every template can be opened and reviewed in full before sending —
with the student's progress, a return-to-course button
and notification settings links.

<img src="docs/screenshots/10-email-preview.png" alt="Email preview">

</td>
</tr>
</table>

---

## Features

### Learning

| Area | What it does |
|---|---|
| Courses | Categories, difficulty levels, free and premium |
| Lessons | Text, rich formatting, syntax highlighting, attached materials |
| Progress | Completion marks, course percentage, resume where you left off |
| Quizzes | Multiple-choice questions, attempts, automatic scoring |
| Assignments | Student uploads, teacher review and grading |
| Certification | Course completion tracking |

### Programming

| Area | What it does |
|---|---|
| Online compiler | Code editor inside the lesson, nothing to install |
| Personal files | Code is stored in the account and available from any device |
| Auto-graded tasks | Statement, tests, passing threshold, points |
| Test-based grading | Solutions run against every test case on the server |
| Lesson gating | The next lesson unlocks only after the task is solved |
| Submission history | Every attempt with its code and result |

### Artificial intelligence

| Area | What it does |
|---|---|
| Lesson AI tutor | Explains the material and answers questions about the lesson |
| Conversation history | The dialogue is saved and restored when you return |
| Author chat | A separate AI channel to reach the course instructor |
| Model choice | Several models supported, including local ones |

### Community

| Area | What it does |
|---|---|
| Course forum | Discussions, replies, voting on helpful posts |
| Comments | Discussion under every lesson with likes |
| News | Platform feed with comments and voting |
| Reviews | Platform ratings from students |
| Notifications | In-app alerts about course events |
| Telegram | Account linking, sign-in and notifications through a bot |

### For teachers and administrators

| Area | What it does |
|---|---|
| Teacher dashboard | Create and edit courses, lessons and quizzes |
| Enrolment requests | Approve enrolment and premium access |
| Grading | Score assignments with written feedback |
| Analytics | Activity, progress, churn risk, CSV export |
| Campaigns | Automatic emails to inactive students with frequency control |
| Moderation | Manage comments, reviews and contact messages |

### Platform

| Area | What it does |
|---|---|
| Two languages | Full interface translation into Russian and Tajik |
| Dark theme | Switchable appearance |
| Global search | Across courses, lessons and news |
| Safe links | Identifiers in URLs are encrypted |
| SEO | Sitemap for search engines |
| Responsive | Works correctly on phones and tablets |

---

## Tech stack

| Layer | Stack |
|---|---|
| Backend | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) |
| Database | ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| Frontend | ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| Code editor | ![Ace](https://img.shields.io/badge/Ace%20Editor-1E1E1E?style=flat-square&logo=visualstudiocode&logoColor=white) |
| Code execution | Wandbox, Paiza.io — server-side compilation and execution |
| Artificial intelligence | ![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) |
| Messaging | ![Telegram](https://img.shields.io/badge/Telegram%20Bot%20API-26A5E4?style=flat-square&logo=telegram&logoColor=white) |
| Localisation | Django i18n — Russian and Tajik |

---

## Project scale

| Metric | Value |
|---|---|
| Data models | 36 |
| URL routes | 127 |
| Main modules | Courses, quizzes, assignments, forum, news, compiler, AI, analytics |
| Interface languages | 2 |

Key entities: `Course`, `Lesson`, `Material`, `Quiz`, `Question`, `Assignment`,
`Submission`, `Enrollment`, `LessonProgress`, `QuizAttempt`, `ForumDiscussion`,
`News`, `CompilerFile`, `CodingTask`, `CodingTestCase`, `CodingSubmission`,
`LessonAIChatHistory`, `Notification`.

---

## What the platform solves

- **Learning to code without setting up an environment.** The student opens
  a lesson and writes code straight in the browser — editor and compiler
  are built in.
- **Honest assessment.** Tasks are graded automatically against tests,
  and the next lesson unlocks only after a pass.
- **Help when the teacher is offline.** The AI tutor explains the lesson
  material around the clock.
- **Fighting drop-off.** Analytics shows who is about to quit, and reminder
  campaigns bring students back.
- **Native language.** A full Tajik interface, not machine translation.

---

## Hire me

Need a learning platform, a corporate training portal or a course system
for your school, university or company?
**I build these systems to order.**

What I can do:

- a learning platform for your needs — courses, quizzes, certificates;
- automatic grading of programming assignments against test suites;
- a built-in AI tutor and chatbot;
- integration with Telegram, payments and your own services;
- analytics and a student-retention system;
- multilingual interface and custom design;
- deployment to your server and domain, staff training, ongoing support.

**Get in touch:**

| | |
|---|---|
| Email | **imomzoda0044@gmail.com** |
| GitHub | [@imomzoda-dev](https://github.com/imomzoda-dev) |
| Website | [moodle.tj](https://moodle.tj/) |

Write to me — we will discuss the scope, timeline and price.
The first consultation is free.

---

## Licence

© 2026 Imomzoda Mehriddin. All rights reserved.

Proprietary software. Copying, distribution, modification and commercial use
are prohibited without prior written permission from the copyright holder.
The screenshots and the text of this page are copyrighted as well.

<div align="center">

### See the platform in action

[![moodle.tj](https://img.shields.io/badge/Open-moodle.tj-6C4CF1?style=for-the-badge&logo=googlechrome&logoColor=white)](https://moodle.tj/)

</div>
