# 🔗 CodeDekho – AI-Powered Real-Time Code Collaborator

**CodeDekho** is a full-stack web application that enables multiple users to collaborate on code in real time, run code in various programming languages, and get AI-driven reviews and optimization suggestions.

---

## 🚀 Features

- 🧑‍💻 **Real-Time Collaboration**  
  Multiple users can join a shared code room and collaborate live via WebSockets.

- 💡 **AI Code Review**  
  Integrated **Gemini API** to analyze and suggest best practices, optimizations, and improvements.

- ⚙️ **Multi-Language Code Execution**  
  Supports real-time code execution in **C++, Python, Java, and JavaScript** using the **Piston API**.

- 📡 **Room Management with Socket.IO**  
  Users can join/leave rooms and sync code edits with real-time accuracy.

- 🌐 **Modern Tech Stack**  
  Built with a clean and responsive UI, and a scalable backend for seamless experience.

---

## 🛠️ Tech Stack

| Layer         | Technologies                                                                               |
| ------------- | ------------------------------------------------------------------------------------------ |
| **Frontend**  | React.js, JavaScript, CSS, Socket.IO                                                       |
| **Backend**   | Node.js, Express.js, Socket.IO                                                             |
| **APIs Used** | [Piston API](https://github.com/engineer-man/piston), [Gemini API](https://ai.google.dev/) |
| **Others**    | Vite, Nodemon, Axios                                                                       |

---

## 📷 Screenshots

**Joining Code Rooms**  
![Join Room](https://github.com/user-attachments/assets/df839f51-0205-403d-8ec6-9e10200aa5ae)

**Collaborative Editor**  
![Editor](https://github.com/user-attachments/assets/d4534045-d5f2-4b4c-a57d-660a496a8325)

**AI Review Response**  
![AI Review](https://github.com/user-attachments/assets/643f83c5-b6a0-402c-8c8c-5a5f86febb07)

---

## 🧪 How It Works

1. User joins a room via a unique **Room ID**.
2. The code editor is synced across users using **Socket.IO**.
3. Code can be written and executed instantly via the **Piston API**.
4. An **AI Review** can be triggered using the **Gemini API** to receive feedback on code quality, structure, and optimizations.

---

## 🔧 Getting Started (Local Setup)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/code-dekho.git
```

### 2. Install Dependencies

**Frontend:**

```bash
cd frontend
npm install
```

**Backend:**

```bash
cd ../backend
npm install
```

### 3. Run the Servers

**Start Backend:**

```bash
npm run dev
```

**Start Frontend:**

```bash
cd ../frontend
npm run dev
```

Open your browser and visit:  
`http://localhost:5173`

---

## 📦 Folder Structure

```
.
├── frontend
│   └── src/
│       ├── main.jsx
│       └── App.jsx
├── backend
│   └── index.js
├── README.md
```

---

## 📈 Future Improvements

- Enhance AI reviews to support **multiple suggestions with scoring**.
- Add **user authentication** and **room persistence**.
- Implement better **concurrency control** for large groups.
- Integrate **audio chat feature** for real-time verbal collaboration in a room.

---
