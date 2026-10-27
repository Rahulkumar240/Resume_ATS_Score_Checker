# Resume Analyzer 📄🔍

An automated **Resume Analyzer built on the MERN stack** designed to help recruiters streamline the hiring pipeline. Instead of manually screening hundreds of applications, this tool parses candidate profiles, evaluates qualifications, and matches applicants with their **best-suited job roles** based on their core competencies. 

Built using the **AGILE methodology**, the project follows clean, modular, and highly scalable architecture principles.

---

## 🚀 Key Features

*   **Single Resume Analysis:** Processes one comprehensive resume at a time for deep, contextual parsing.
*   **Role Alignment:** Automatically determines and suggests the best-suited career roles that match the candidate's skill set.
*   **Recruiter Dashboard:** Eliminates manual scanning effort by extracting key metrics instantly.
*   **Structured Processing:** Dedicated backend pipelines for seamless file handling, text extraction, and analytics parsing.

---

## 🏗️ Repository Architecture

The project maintains a strict separation of concerns between client interface and server logic:

```text
├── Frontend/             # React application (UI/UX components, state management)
└── backend/              # Node.js & Express server application
    ├── node_modules/     # Server-side dependencies
    ├── routes/           # REST API endpoints mapping controller actions
    ├── uploads/          # Temporary local storage for uploaded resumes
    ├── utils/            # Helper classes, text parsers, and processing logic
    ├── .gitignore        # Version control exclusions
    ├── package.json      # Backend dependency manifests
    └── server.js         # Application entry point
```

---

## 🛠️ Tech Stack

*   **Frontend:** React.js, HTML5, CSS3, JavaScript (ES6+)
*   **Backend:** Node.js, Express.js
*   **Database:** MongoDB (MERN standard compliance)
*   **Processing:** File parsing utilities for document scanning

---

## ⚡ Getting Started

### Prerequisites
*   [Node.js](https://nodejs.org/) (v14+ recommended)
*   [MongoDB](https://www.mongodb.com/) (Local or Atlas instance)

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Rahulkumar240/AiResumeanalyzer.git
   cd AiResumeanalyzer
   ```

2. **Configure the Backend:**
   ```bash
   cd backend
   npm install
   # Create a .env file and configure your PORT and MONGODB_URI
   npm start / node server.js
   ```

3. **Configure the Frontend:**
   ```bash
   cd ../Frontend
   npm install
   npm start
   ```

---

## 📈 Development Methodology

This project was built following the **AGILE Framework**:
*   Iterative feature releases (Incremental delivery of processing tools).
*   Modular code splitting for component scalability.
*   Continuous integration optimization across backend router architectures.

---

## 👤 Author

*   **Rahul Kumar** - [Rahulkumar240](https://github.com/Rahulkumar240)
