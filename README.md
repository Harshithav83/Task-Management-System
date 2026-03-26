# 📋 Task Management System (Python - Console Based)

## 🚀 Project Overview

The **Task Management System** is a console-based application developed using Python that allows users to efficiently manage their daily tasks.
The project follows the **MVC (Model-View-Controller)** architecture to ensure clean code organization, scalability, and maintainability.

---

## 🎯 Features

* ✅ Add new tasks
* 📄 View all tasks
* ✏️ Update existing tasks
* ❌ Delete tasks
* 👤 Manage users
* 🗂️ Categorize tasks
* 💾 Data stored using JSON files

---

## 🧠 Architecture Used

This project follows the **MVC (Model-View-Controller)** pattern:

* **Model** → Defines the data structure (Task, User, Category)
* **View** → Handles user interaction via console
* **Controller** → Contains business logic and manages operations

---

## 📂 Project Structure

```
task_management_system/
│
├── main.py
│
├── controllers/
│   ├── task_controller.py
│   └── user_controller.py
│
├── models/
│   ├── task.py
│   ├── user.py
│   └── category.py
│
├── views/
│   └── console_view.py
│
├── utils/
│   ├── file_handler.py
│   └── validators.py
│
├── data/
│   ├── tasks.json
│   ├── users.json
│   └── categories.json
```

---

## ⚙️ Technologies Used

* Python 🐍
* JSON (for data storage)
* Object-Oriented Programming (OOP)

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```
git clone <your-repo-link>
```

### Step 2: Navigate to Project Folder

```
cd task_management_system
```

### Step 3: Run the Application

```
python main.py
```

---

## 🔁 Workflow Example

1. User selects an option from the menu
2. View collects input from user
3. Controller processes the request
4. Model structures the data
5. Data is stored/retrieved from JSON files

---

## 💡 Key Concepts Demonstrated

* MVC Architecture
* OOP (Classes and Objects)
* File Handling in Python
* Modular Programming
* Separation of Concerns

---

## 🚀 Future Enhancements

* 🔐 User Authentication (Login/Signup)
* 🌐 Convert to Web App using Flask
* 📅 Add due dates and reminders
* 🔍 Search and filter tasks
* ⭐ Task priority levels

---

## 👩‍💻 Author

**Harshitha V**

* AIML Graduate
* Passionate about Python, AI & Software Development

---

## ⭐ Acknowledgment

This project was built as part of learning and improving problem-solving and software development skills.

---

## 📌 Note

This is a beginner-to-intermediate level project designed to demonstrate structured programming and clean architecture.
