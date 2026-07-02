🔐 Auth App

A production-level full-stack authentication application built with a Java backend and a separate frontend. The project demonstrates secure authentication and authorization using industry-standard practices, making it a solid foundation for scalable web applications.

✨ Features
🔑 User Registration
🔐 Secure User Login
🛡️ JWT-based Authentication
🔒 Password Encryption
🚪 Protected Routes
📦 Separate Frontend and Backend
🐳 Docker Support
⚡ Production-ready Project Structure
📂 Project Structure
Auth-app/
│
├── auth-backend/          # Java Backend
├── auth-app-frontend/     # Frontend Application
├── .vscode/
└── README.md
🛠️ Tech Stack
Backend
Java
Spring Boot
Spring Security
JWT Authentication
Maven
Frontend
React.js
JavaScript
HTML5
CSS3
Database
MySQL
DevOps
Docker
🚀 Getting Started
1. Clone the Repository
git clone https://github.com/Ayush-kumar-01/Auth-app.git
cd Auth-app
2. Start the Backend
cd auth-backend

Run the application:

./mvnw spring-boot:run

or

mvn spring-boot:run
3. Start the Frontend

Open a new terminal:

cd auth-app-frontend
npm install
npm start
⚙️ Environment Variables

Configure your backend environment variables before running the application.

Example:

SPRING_DATASOURCE_URL=your_database_url
SPRING_DATASOURCE_USERNAME=your_username
SPRING_DATASOURCE_PASSWORD=your_password

JWT_SECRET=your_secret_key
JWT_EXPIRATION=86400000
🔐 Authentication Flow
User registers a new account.
Password is securely encrypted before storage.
User logs in with valid credentials.
Server generates a JWT token.
Client includes the token in subsequent requests.
Protected endpoints validate the token before granting access.
📌 Project Highlights
Secure authentication using Spring Security.
JWT-based stateless authorization.
Encrypted password storage.
Modular frontend and backend architecture.
Easily deployable with Docker.
🐳 Docker

Build the Docker image:

docker build -t auth-app .

Run the container:

docker run -p 8080:8080 auth-app
📈 Future Enhancements
Email Verification
Forgot Password
Refresh Tokens
Google OAuth Login
GitHub OAuth Login
Role-Based Access Control (RBAC)
Two-Factor Authentication (2FA)
User Profile Management
🤝 Contributing

Contributions are always welcome!

Fork the repository.
Create a new feature branch.
git checkout -b feature-name
Commit your changes.
git commit -m "Add new feature"
Push your branch.
git push origin feature-name
Open a Pull Request.
👨‍💻 Author

Ayush Kumar

GitHub: https://github.com/Ayush-kumar-01

⭐ Support

If you found this project useful, consider giving it a ⭐ Star on GitHub. It helps others discover the project and motivates future improvements.
