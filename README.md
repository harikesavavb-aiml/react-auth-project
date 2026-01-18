🔐 React Email Authentication System

A real-world email-based authentication system built using React, Redux Toolkit, and JWT, demonstrating how modern frontend applications handle secure login, protected routes, and session persistence.

This project focuses on authentication logic, not just UI.

✨ Key Features

📧 Email & password based login

🔑 JWT-based authentication

🧠 Centralized auth state using Redux Toolkit

🔒 Protected routes using React Router

💾 Session persistence using localStorage

🚪 Secure logout & auto-login handling

🛠️ Tech Stack

Frontend: React JS

State Management: Redux Toolkit

Routing: React Router DOM

Authentication: JWT

Fake API: Reqres Authentication API

Storage: Browser localStorage

🔑 Demo Login Credentials (Email-Based)

⚠️ These are public test credentials provided by the fake authentication API.

Email: eve.holt@reqres.in
Password: cityslicka

🔄 Authentication Workflow

User enters email and password on the login page

Credentials are sent to the authentication API

On successful validation, a JWT token is returned

Token is stored securely in localStorage

Redux state updates authentication status

User is redirected to protected pages

Logout clears token and resets state

🚧 Protected Routes

The following routes are accessible only after authentication:

/dashboard

/profile

/attendance

/tasks

Unauthorized users are automatically redirected to the login page.

🔁 Session Persistence

Authentication state is restored on page refresh

User remains logged in as long as the JWT token exists

Logout completely clears the session

This behavior closely mimics production-level authentication systems.

📁 Project Structure (Simplified)
src/
 ├─ app/              # Redux store configuration
 ├─ features/auth/    # Authentication slice
 ├─ pages/            # Login, Dashboard, Profile
 ├─ components/       # ProtectedRoute
 ├─ services/         # API & Axios configuration
 └─ App.js

🚀 How to Run the Project
npm install
npm start


The application runs on:

http://localhost:3000

📌 Learning Outcomes

Implemented email-based authentication flow

Gained hands-on experience with JWT handling

Learned Redux-based auth state management

Secured frontend routes effectively

👤 Author

Harikesava V B
B.E. Computer Science and Engineering (AIML)
Frontend / Full Stack Enthusiast

📜 Note

This project uses a fake authentication API for learning purposes.
No real user data is involved.
