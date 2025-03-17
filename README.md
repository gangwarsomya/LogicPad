
# LogicPad: Collaborative Real-time Code Editor

LogicPad is a collaborative, real-time code editor that allows multiple users to seamlessly code together. Share a unique room ID and collaborate on projects simultaneously, with features like an AI-powered code generation and live preview.

![image](https://github.com/user-attachments/assets/1e13d80f-024a-4db7-bc5c-57916a0f51ed)


![image](https://github.com/user-attachments/assets/de780005-6b80-4348-b9be-ab0ff08a8032)


![image](https://github.com/user-attachments/assets/6248439a-7b80-4e42-b7e3-aa5f7d7bf588)


![image](https://github.com/user-attachments/assets/5273bf0c-059e-40c0-baf9-f45702c6e88a)



## Features

* **Real-time Collaboration:** Edit code across multiple files simultaneously with other users.
* **File Management:** Create, open, edit, save, delete, and organize files and folders within the editor.
* **Download Codebase:** Download the entire project as a zip file.
* **Unique Room IDs:** Generate unique room IDs for collaborative sessions.
* **Comprehensive Language Support:** Supports a wide variety of programming languages.
* **Syntax Highlighting:** Automatic syntax highlighting for various file types.
* **Code Execution:** Execute code directly within the editor.
* **Instant Updates:** Real-time synchronization of code changes across all files and folders.
* **User Presence:** See who's online and actively editing.
* **Notifications:** Real-time notifications for user join/leave events.
* **Real-time Chat:** Communicate with collaborators through a built-in chat.
* **Live Tooltips:** See which users are currently editing specific sections of code.
* **Auto Suggestions:**  AI-powered code suggestions based on the programming language.
* **Customizable Editor:** Change font size and font family.  (Mention themes if implemented).
* **AI-powered Copilot:** Generate code suggestions, insert, copy, or replace content seamlessly.
* **Live Preview:** View a live preview of your project. (If applicable, explain how to use it)



## Tech Stack

* **Frontend:** React, TypeScript, React Router, Tailwind CSS 
* **Backend:** Node.js, Express.js, Socket.io
* **Other:** Git, GitHub, Vercel



## Installation

### Method 1: Manual Installation

1. **Fork and Clone:** Fork and clone the repository from GitHub. (Provide the correct GitHub link.)

2. **Environment Variables:**  Create `.env` files in both the `client` and `server` directories with the necessary configuration. (Provide specific instructions and examples for the `.env` variables).


3. **Install Dependencies:**
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

4. **Start Servers:**
    ```bash
    cd client
    npm run dev
    cd ../server
    npm run dev
    ```

5. **Access Application:** Open `http://localhost:5173/`
