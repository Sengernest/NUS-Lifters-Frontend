# NUS Lifters
A full-stack web forum application that allows users to register accounts, create fitness and gym-related topics, posts and comments as well as interact through likes. 

> **Tech Stack:** React + Vite • TypeScript • Material UI • Axios • Go • SQLite

**Frontend URL:** *https://nus-lifters-web-forum.netlify.app/forum*

**Backend GitHub Repo:** *https://github.com/Sengernest/NUS-Lifters-Backend.git*

---

## Features
- User registration and login
- JWT-based authentication
- Topic creation, editing, and deletion
- Post creation, editing, deletion, and liking
- Comment creation, editing, deletion, and liking
- Search and sorting for topics and posts
- Responsive UI using Material UI

## Tech Stack
**Frontend**
- React
- TypeScript
- Material UI
- Axios

**Backend**
- Go
- SQLite database

**Deployment**
- Frontend: Netlify
- Backend: Render

---

## Running locally

### Backend Setup
### 1. Clone the backend repository:  

```bash
git clone https://github.com/Sengernest/NUS-Lifters-Backend.git
```

### 2. Go into the directoy which the repo was cloned into

### 3. Before running the server, a JWT secret key must be set as an environment variable in the terminal:
   - **Windows (PowerShell)**  
     ```powershell
     $env:JWT_KEY="cvwo-secret-key"
     ```
   - **Windows (Command Prompt)**  
     ```cmd
     set JWT_KEY=cvwo-secret-key
     ```
   - **macOS / Linux**  
     ```bash
     export JWT_KEY="cvwo-secret-key"
     ```
4. Run the backend server
   
   ```bash
   go run main.go
   ```

### Frontend Setup
### 1. Clone the repository

```bash
git clone https://github.com/Sengernest/NUS-Lifters-Frontend.git
```

### 2. Go into the directory where the repo was cloned into 

### 3. Install dependencies

 ```bash
    npm install
  ```
    
### 4. Start the development server

```bash
npm run dev
```
---

## Deployed Application 
**Frontend (Netlify):**
https://nus-lifters-web-forum.netlify.app/forum

**Backend (Render):**
https://cvwo-nus-lifters-club-web-forum-backend.onrender.com
