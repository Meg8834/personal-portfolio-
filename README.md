🚀 Personal Portfolio – Full Stack Web Application
📌 Project Overview

This project is a full-stack personal portfolio website developed to showcase my skills, projects, and profile as an AI Engineer & Full-Stack Developer.
It features a responsive frontend, a Python-based backend API, and a functional contact form with database storage.

🛠️ Tech Stack
🔹 Frontend

HTML5

CSS3

JavaScript (Vanilla JS)

Responsive UI design

Smooth animations and transitions

🔹 Backend

Python

Flask (REST API)

Flask-CORS (for frontend–backend communication)

🔹 Database

MySQL / SQLite

Used to store contact form submissions

🔹 Tools & Utilities

Git & GitHub

Visual Studio Code

Python Virtual Environment (venv)

JSON (API data exchange format)

🔄 Application Workflow

User fills out the Contact Form on the frontend

JavaScript sends form data using Fetch API in JSON format

Flask backend receives data through the /contact API

Data is validated and stored in the database

Backend returns a JSON response

Frontend displays success or error message

🌐 API Details
Contact API

Endpoint: /contact

Method: POST

Data Format: JSON

Sample Request

{
  "name": "John Doe",
  "email": "john@example.com",
  "subject": "Project Discussion",
  "message": "Let's collaborate"
}


Sample Response

{
  "success": true,
  "message": "Message saved successfully"
}

▶️ How to Run the Project
1️⃣ Backend Setup
cd backend
python app.py


Backend runs at:
http://127.0.0.1:5000

2️⃣ Frontend Setup

Open directly in browser OR

Use Live Server:

frontend/index.html

✨ Key Features

Fully responsive portfolio design

Clean and modern UI

Contact form with backend API integration

Database storage for user messages

Clear separation of frontend and backend

Maintainable and scalable structure

🎯 Learning Outcomes

Full-stack development workflow

REST API development using Flask

JSON-based frontend ↔ backend communication

Database integration

GitHub project structuring and version control

📌 Future Enhancements

Gmail SMTP email notifications

Admin dashboard to view messages

Deployment to cloud (Render / Railway / AWS)

👤 Author

Megaraj M
AI Engineer & Full-Stack Developer

🔗 GitHub: https://github.com/Meg8834

🔗 LinkedIn: https://www.linkedin.com/in/megaraj-m-7b4b79341/

🏁 Conclusion

This project demonstrates a real-world full-stack web application with API integration, database handling, and a responsive frontend.
It is suitable for academic submission, interviews, and professional portfolio showcasing.