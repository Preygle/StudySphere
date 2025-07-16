# 🌐 Student Productivity Web Portal

This is a full-stack educational productivity web application designed to centralize student tools, assignments, notes, and support through a smart chatbot interface. It includes services like cloud storage, assignment aggregation, personal to-do lists, curated online resources, and a built-in GPT-4-based chatbot for help.

---

## 🚀 How to Start the Project

### 🖥️ Start the Web Server
```bash

node server.js
```

### 💬 Start the Chatbot Server
```bash
python chat_server.py
```

---

## 🔐 Authentication

- Users can **Sign Up** or **Log In** using their credentials.
- All user data is stored in a connected **MongoDB** database.

---

## 🧭 Navigation & Pages

Once logged in, users are directed to the **Home Page**, which includes a navigation bar with:

- **Home** – Redirects to the top of the homepage.
- **Services** – Scrolls to the services section.
- **Feedback** – Scrolls to the feedback form.
- **About Us** – Opens the "About Us" page.
- **Contact Us** – Opens the contact details page.
- **User Profile** – Displays the username and daily activity streak.

---

## ⚙️ Features & Services

### 1️⃣ Organized Notes and Lectures

- Integrated with a **Google Cloud Storage (GCS) Bucket**.
- Users can:
  - Create folders
  - Upload files
  - Access and download uploaded content

### 2️⃣ Assignments & To-do List

- Assignment data is **scraped** from a dummy site hosted on **Vercel** named `consolidated-assignment`. [LINK!](https://github.com/Preygle/consolodated-assignment)
- It aggregates assignments from:
  - LMS
  - Microsoft Teams
  - VPropel
- Displayed fields:
  - Title
  - Description
  - Due Date
  - Source Platform
- Includes a **user-custom to-do list**:
  - Add task (Title, Description, Due Date)
  - View pending tasks

### 3️⃣ Online Courses and Roadmap

- Curated links for learning:
  - DSA in Java
  - Linux
  - MySQL
  - Other programming essentials

### 4️⃣ Online Tools and Resources

Direct links to tools like:
- Jupyter
- FreeCAD
- Overleaf
- Notion
- Desmos
- Tinkercad
- Replit
- Grammarly
- Postman

---

## 🤖 GPT-4 Chatbot Integration

- Powered by OpenAI's GPT-4 via OpenRouter API.
- Chatbot runs from `chat_server.py`.
- Backend ports: **5000** (Web ↔️ Chat) and **5001** (API ↔️ GPT-4).
- Use it for quick help, explanations, guidance, etc.

---

## 📫 Feedback and About Us

- Found at the bottom of the home page.
- Users can leave feedback and get information about the creators and purpose of the project.

---

## 📂 Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express, Python (Flask for chatbot)
- **Database**: MongoDB
- **Cloud**: Google Cloud Platform (GCS)
- **APIs**: OpenRouter (GPT-4), custom scraping API
- **Hosting**: Vercel (for dummy assignment scraping site)

---

## ✨ Project Status

This project is in active development. Suggestions, improvements, or contributions are welcome.

---

## 📧 Contact

Feel free to reach out through the **Contact Us** page on the site or drop feedback through the form.
