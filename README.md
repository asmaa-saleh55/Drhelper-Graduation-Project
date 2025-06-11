## 🚀 Installation & Running Guide

To run the Dr. Helper web application locally, follow these steps:

### 🔧 Prerequisites

Ensure the following are installed on your machine:

* [Node.js](https://nodejs.org/) (v14 or later)
* [npm](https://www.npmjs.com/) (Node.js package manager)
* [Python 3](https://www.python.org/downloads/) (v3.6 or later)

---

### 1️⃣ Start the React Frontend

1. Open a terminal window.

2. Navigate to the root directory of the project.

3. Install project dependencies (only needed the first time):

  
Bash

   npm install
   
4. Start the React development server:

  
Bash

   npm run dev
   
   This will launch the frontend at [http://localhost:3000](http://localhost:3000) by default.

---

### 2️⃣ Run the Chatbot Backend (Python)

1. Open a new terminal window.

2. Navigate to the chatbot model directory:

  
Bash

   cd public/Model
   
3. Run the chatbot backend:

  
Bash

   python Projectrun.py
   
   This will start the chatbot service used by the web interface.

> 💡 Ensure all required Python libraries are installed. If you have a requirements.txt file in the project, you can install them with:
>
>
Bash

> pip install -r requirements.txt
> 
---

### ✅ You're Ready!

Once both the React frontend and the chatbot backend are running, visit [http://localhost:3000](http://localhost:3000) in your browser to use Dr. Helper.
nodejs.org
Node.js — Run JavaScript Everywhere

Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.

