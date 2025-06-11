## 🚀 Installation & Running Guide

To run the Dr. Helper website locally, follow the steps below:

### 🔧 Prerequisites

Ensure the following are installed on your system:

* [Node.js](https://nodejs.org/) (v14 or later)
* [npm](https://www.npmjs.com/)
* [Python 3](https://www.python.org/downloads/) (v3.6 or later)
* [Django](https://www.djangoproject.com/) (v3.0 or later)
* Python packages listed in requirements.txt (if available)

---

### To run Dr. Helper, follow these 3 steps:

---

### 1️⃣ Start the React Frontend

1. Open a terminal window.

2. Navigate to the root directory of the project.

3. Install dependencies (only needed the first time):

  
Bash

   npm install
   
4. Start the React development server:

  
Bash

   npm run dev
   
   The frontend will be available at: [http://localhost:3000](http://localhost:3000)

---

### 2️⃣ Run the Chatbot Model (Python)

1. Open a new terminal window.

2. Navigate to the chatbot model directory:

  
Bash

   cd public/Model
   
3. Start the chatbot engine:

  
Bash

   python Projectrun.py
   
   This initializes the chatbot functionality used by the application.

---

### 3️⃣ Start the Backend Server (Django)

1. In another terminal window, navigate to the Django backend directory (if it's separate).
2. Run the Django server with:

  
Bash

   python manage.py runserver
   
   This starts the backend API to handle requests from the frontend.

---

### ✅ You're Ready!

With the frontend, chatbot model, and Django backend all running, open your browser and go to:

👉 [http://localhost:3000](http://localhost:3000) to start using Dr. Helper.
nodejs.org
Node.js — Run JavaScript Everywhere

Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.

