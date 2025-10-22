
✅ Permalist – To-Do List App

The Permalist App is a simple yet powerful to-do list web application built with Node.js, Express, and PostgreSQL.
It lets users add, manage, and delete daily tasks — keeping productivity organized and consistent every day.

🚀 Features

🗓️ Add New Tasks with a clean and intuitive UI

🗑️ Delete Tasks when completed

💾 Persistent Storage using PostgreSQL

🎨 EJS Templates for dynamic page rendering

⚙️ Express + Body-Parser for smooth form handling

🌐 RESTful Routes for structured backend logic

🧰 Tech Stack
Layer	Technology
Frontend	EJS, HTML5, CSS3
Backend	Node.js, Express.js
Database	PostgreSQL
Middleware	body-parser
📂 Project Structure
permalist-app/
│
├── views/              # EJS templates (home, list pages)
├── public/             # Static files (CSS, JS, images)
├── index.js            # Main Express server file
├── package.json        # Project metadata and dependencies
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/yourusername/permalist-app.git
cd permalist-app

2️⃣ Install dependencies
npm install

3️⃣ Create .env file

In the project root, create a .env file with the following:

PORT=3000
DATABASE_URL=postgresql://username:password@localhost:5432/permalist

4️⃣ Set up PostgreSQL

Run these SQL commands to create the database table:

CREATE TABLE tasks (
  id SERIAL PRIMARY KEY,
  task_name VARCHAR(255) NOT NULL
);

5️⃣ Start the app
npm start


Visit http://localhost:3000
 to view your app.

🧭 Routes Overview
Route	Method	Description
/	GET	Display all tasks
/	POST	Add a new task
/delete	POST	Delete a task
🧩 Future Enhancements

✅ Add user accounts with authentication

📅 Add due dates and task categories

🔄 Mark tasks as completed instead of deleting

📱 Make UI responsive using Bootstrap or Tailwind

☁️ Host the app on Render, Vercel, or Railway

👨‍💻 Author

[Dawar Abbas]
Full-Stack Developer | Focused on clean UI, reliable backends, and productivity tools
📧 meesumabbas891@gmail.com

🪪 License

This project is licensed under the MIT License — free for personal and commercial use.

