# CalcThreads Frontend - React + TypeScript (Vite)

This repository contains the frontend codebase for the client application, built using **React**, **TypeScript**, and **Vite**.  
The goal of this project is to initialize the client environment so developers can begin building UI components efficiently.

---

## 🚀 Tech Stack

- **React 19.2.0**
- **TypeScript**
- **Vite**
- **Node.js (LTS recommended: v18 or v20)**
- **npm / pnpm / yarn** (choose based on project standard)

---

## 📌 Requirements to Run the Project

Before running this project locally, ensure you have:

- **Node.js v18+**
- **npm v9+** or an alternative package manager
- A code editor such as **VS Code**

---

## 📦 How to Install & Run Locally

### 1️⃣ Clone Repository

```bash
git clone https://github.com/bisawebdev/calcthreads-peer-trial-frontend-team-a.git
cd calcthreads-peer-trial-frontend-team-a
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Start Development Server

```bash
npm run dev
```

### 4️⃣ Open in Browser

Vite will serve the project at:

```
http://localhost:5173/
```

---

## 📁 Project Structure

```
src/
 ├─ components/        # Reusable UI components
 ├─ state/             # (Optional) State management / stores
 ├─ App.tsx            # Main app component
 ├─ main.tsx           # Entry point
 └─ index.css          # Global styling
```

---

## 🧪 Acceptance Criteria & Verification

### **User Story**

_As a developer, I want to initialize the React/TypeScript client project so that I have a front-end environment ready for building the user interface components._

### **Acceptance Criteria**

- The client project is initialized using Vite with TypeScript support.
- The `App.tsx` component renders successfully in the browser.
- The project structure includes folders for components and state management.
- No TypeScript or compilation errors occur during development.

---

## 📝 Technical Notes (For Future Development)

- Components should follow **atomic structure** or team coding guidelines.
- Use **TypeScript strictly** (`strict: true`) for better type safety.
- Keep state management inside `src/state/`.  
  Suggested tools: Zustand, Redux Toolkit, Jotai, or Context API.
- Avoid pushing build artifacts (`dist/`) — ensure `.gitignore` is correct.
- Use **Conventional Commits**:
  - `feat:` new feature
  - `fix:` bug fix
  - `chore:` config / minor updates
  - `refactor:` code improvement
  - `docs:` documentation updates

---

## 🤝 Contribution Guidelines

- Create a new branch for every task:
  ```
  git checkout -b feat/<task-name>
  ```
- Commit using conventional commits.
- Open a Pull Request with:
  - User Story
  - Acceptance Criteria
  - Screenshot result
  - Description of changes

---
