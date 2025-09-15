# Project Plan: FocusFlows

## Project Overview
FocusFlows is a simple task management application where users can create, update, and delete tasks.  
The project is structured with a frontend (React) and a backend (Node.js/Express or Python) and is designed for easy deployment.

---

## Objectives
- Build a functional task management app.
- Keep frontend and backend modular.
- Maintain clear project documentation in GitHub.
- Deploy frontend and backend separately while keeping repo organized.

---

## Repo Structure
FocusFlows/
├── README.md
├── project-plan/
│ └── project-plan.md # This file
├── docs/ # Diagrams, mockups, notes
├── frontend/ # React app
├── backend/ # Node.js/Express or Python API
└── .gitignore

---

## Features
- **Task CRUD**: Create, Read, Update, Delete tasks.
- **User-friendly UI**: Clean and responsive.
- **API integration**: Frontend communicates with backend for data persistence.
- **Deployment-ready**: Frontend and backend can be deployed separately.

---

## Backend
- **Language**: Node.js (Express) or Python (FastAPI/Flask)  
- **Database**: SQLite (file-based, simple)  
- **API Endpoints**:
  - `GET /tasks` – fetch all tasks
  - `POST /tasks` – add a task
  - `PUT /tasks/:id` – update a task
  - `DELETE /tasks/:id` – delete a task

---

## Frontend
- **Framework**: React
- **Components**:
  - `TaskList` – displays all tasks
  - `TaskItem` – individual task with edit/delete
  - `TaskForm` – add or edit task
- **API calls**: Axios or fetch
- **State management**: `useState` & `useEffect`

---

## Deployment
- **Frontend**: Vercel / Netlify  
- **Backend**: Render / Railway  
- Ensure frontend points to live backend URL.

---

## Documentation & Notes
- All project planning files are stored in `project-plan/`.
- Diagrams, UI mockups, or additional notes go in the `docs/` folder.
- Keep commits frequent and descriptive.