# ![PlanPilot Banner](./screenshots/banner.png)

# 🚀 PlanPilot – Agile Project Management SaaS

PlanPilot is a modern project management platform built for agile teams and organizations to efficiently plan projects, manage sprints, track issues, and streamline workflows through an intuitive Kanban-based system.

Designed with scalability and collaboration in mind, PlanPilot provides organization-level workspaces, sprint lifecycle management, drag-and-drop issue tracking, and secure authentication to help teams deliver projects faster.

---

## ✨ Key Highlights

* 🏢 Multi-Organization Architecture
* 📁 Project & Sprint Management
* 📋 Drag-and-Drop Kanban Board
* 📌 Issue Tracking & Prioritization
* 🔐 Clerk Authentication & Authorization
* 🔥 Firebase Firestore Integration
* 👥 Role-Based Access Control
* 🎨 Modern Responsive UI
* ⚡ Built with React & Vite

---

# 📸 Screenshots

## Landing Page

The homepage introduces the platform and provides quick access to project creation and organization management.

![Landing Page](./screenshots/landing-page.png)

---

## Create Project

Create projects with unique project keys and descriptions inside your organization workspace.

![Create Project](./screenshots/create-project.png)

---

## Organization Dashboard

Manage multiple projects across organizations with a clean and organized interface.

![Organizations Dashboard](./screenshots/organizations-dashboard.png)

---

## Sprint Board

Track sprint progress through an intuitive Kanban workflow.

![Sprint Board](./screenshots/sprint-board.png)

---

## Issue Management

Create, prioritize, assign, and move issues across workflow stages.

![Issue Management](./screenshots/issue-management.png)

---

# 🏗️ System Architecture

```text
User
 │
 ▼
Clerk Authentication
 │
 ▼
Organizations
 │
 ▼
Projects
 │
 ▼
Sprints
 │
 ▼
Issues
 │
 ▼
Kanban Workflow
```

---

# ✨ Features

## 🏢 Organization Management

* Create and manage organizations
* Organization-specific project workspaces
* Switch between organizations
* Admin-controlled access

---

## 📁 Project Management

* Create new projects
* Unique project key system
* Project descriptions and metadata
* Organization-based project ownership
* Project deletion controls

---

## 🏃 Sprint Management

* Create sprint cycles
* Sprint date validation
* Sprint lifecycle management

### Sprint Workflow

```text
Planned
   ↓
Active
   ↓
Completed
```

* Start and end sprint controls
* Sprint progress monitoring

---

## 📌 Issue Tracking

* Create project issues
* Assign issues to users
* Edit and update issues
* Delete issues with permissions
* Issue descriptions and metadata

### Supported Priorities

```text
Low
Medium
High
```

---

## 📋 Kanban Workflow

Drag-and-drop issue tracking inspired by modern Agile tools.

### Workflow Stages

```text
Todo
   ↓
In Progress
   ↓
In Review
   ↓
Done
```

Features:

* Drag-and-drop functionality
* Status tracking
* Visual workflow management
* Sprint-based issue organization

---

## 🔐 Authentication & Authorization

Powered by Clerk Authentication.

Features include:

* Secure Sign Up / Sign In
* User profile management
* Protected routes
* Organization-based access control
* Role-based permissions
* Admin-only actions

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* React Router DOM
* Tailwind CSS
* React Hook Form
* Zod

### Authentication

* Clerk Authentication
* Clerk Organizations

### Database

* Firebase Firestore

### UI Libraries

* Radix UI
* Lucide React
* Sonner
* Vaul

### Productivity Tools

* Hello Pangea Drag & Drop
* Date-fns
* React MD Editor

---

# 📂 Project Structure

```text
src
│
├── components
│   ├── sprint-board.jsx
│   ├── sprint-manager.jsx
│   ├── create-issue.jsx
│   ├── create-sprint.jsx
│   ├── issue-card.jsx
│   ├── issue-details-dialog.jsx
│   └── ui/
│
├── pages
│   ├── HomePage.jsx
│   ├── Organization.jsx
│   ├── Project.jsx
│   ├── Create.jsx
│   ├── Sign-In.jsx
│   └── Sign-Up.jsx
│
├── services
│   ├── issueService.js
│   ├── sprintService.js
│   ├── projectService.js
│   ├── organisation.js
│   └── userService.js
│
├── hooks
│   └── use-fetch.js
│
├── firebase.js
├── App.jsx
└── main.jsx
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/your-username/planpilot.git
cd planpilot
```

---

## Install Dependencies

```bash
npm install
```

---

## Setup Environment Variables

Create a `.env` file:

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

---

## Run Development Server

```bash
npm run dev
```

---

## Build For Production

```bash
npm run build
```

---

# 🔒 Security & Permissions

PlanPilot implements:

* Clerk Authentication
* Protected Routes
* Organization-Level Isolation
* Role-Based Access Control
* Admin Authorization Checks
* Firestore Validation Rules

---

# 📈 Future Enhancements

* Team invitations
* Issue comments
* File attachments
* Activity logs
* Analytics dashboard
* Burndown charts
* Team velocity metrics
* Custom workflows
* Real-time collaboration
* Notifications system

---

# 👩‍💻 Author

## Ishika Bansal

Full Stack Developer passionate about building scalable SaaS applications and modern web experiences.

### Connect With Me

* GitHub: https://github.com/Ishika-45
* LinkedIn: https://linkedin.com/in/ishika-bansal-3443a4250
* Portfolio: https://talentcanvas.netlify.app

---

# ⭐ Why This Project Matters

PlanPilot demonstrates real-world software engineering concepts including:

* Multi-Tenant SaaS Architecture
* Agile Project Management
* Sprint Planning
* Kanban Workflow Systems
* Authentication & Authorization
* Role-Based Access Control
* Firebase Firestore Integration
* Modern React Development
* Scalable Frontend Architecture

Built to simulate how professional project management platforms like Jira and Trello organize projects, teams, and workflows.
