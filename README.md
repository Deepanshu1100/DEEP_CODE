# Code Deep | Full-Stack Coding Practice Platform 🚀

**Code Deep** is a robust full-stack web application that allows users to write, compile, and execute code directly within the browser. It leverages a cloud-based execution engine to support multiple programming languages without local environment setup.

---

## 🌟 Key Features

* **Multi-Language Support:** Write and execute code in C++, Java, and JavaScript.
* **Remote Code Execution:** Integrated **Judge0 API** for secure, sandboxed, and fast cloud compilation.
* **Problem Management:** structured backend system to handle coding problems and test cases.
* **Responsive Interface:** Modern, clean UI built with **React.js** ensuring a smooth experience across devices.
* **Submission History:** **MongoDB** integration to track user submissions and results.

---

## 🛠️ Tech Stack

* **Frontend:** React.js, CSS3
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **API Integration:** Judge0 API (RapidAPI)

---

## 🏗️ System Architecture

The application follows a streamlined architecture to ensure secure code execution:

1.  **User Input:** The user writes code in the React Frontend and selects a language.
2.  **API Request:** The Node.js backend receives the code and forwards it to the Judge0 API.
3.  **Cloud Execution:** Judge0 compiles and runs the code in a secure sandboxed environment.
4.  **Output:** The result (output or error) is returned to the backend and displayed to the user.

---

## 📂 Project Structure

```text
DEEP_CODE/
├── client/           # Frontend (React.js application)
│   ├── src/
│   └── public/
├── server/           # Backend (Node.js & Express logic)
│   ├── models/       # MongoDB Schemas (User, Problem)
│   ├── routes/       # API Endpoints
│   └── controllers/  # Business Logic (Judge0 Integration)
└── README.md
