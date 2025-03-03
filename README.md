🌟 The Globetrotter Challenge – A Full-Stack Travel Guessing Game 🌟

Welcome to The Globetrotter Challenge! This repository contains a full-stack web application built with Spring Boot, React, and MySQL. The app allows users to guess famous travel destinations based on cryptic clues, with engaging feedback, trivia, and the ability to challenge friends. It combines modern web technologies and AI-powered features to create an interactive, fun, and educational experience.

This project demonstrates how to create a dynamic web application with real-time gameplay, secure data management, and seamless user interaction, all while showcasing the power of Spring Boot for backend development, React for frontend development, and MySQL for data storage.

---

## 📖 Table of Contents

1. [Project Overview](#project-overview)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Screenshots](#screenshots)

---

🚀 Project Overview
Welcome to The Globetrotter Challenge—the ultimate travel guessing game! In this project, you’ll be building a full-stack web app where users are given cryptic clues about famous destinations around the world, and they must guess which destination is being described. Once they make their guess, fun facts, trivia, and surprises about the destination are revealed.

This project utilizes Spring Boot for the backend, React for the frontend, and MySQL for data storage, offering a seamless and engaging user experience.

Key Highlights:

🌍 AI-Powered Dataset: A dynamic dataset of over 100+ travel destinations, expanded with the help of AI tools like OpenAI API.
🧩 Interactive Gameplay: Presenting random clues and offering multiple answers for users to guess the destination.
🎉 Instant Feedback: Users receive immediate, playful feedback after each guess with animations and fun facts about the destination.
🌐 Challenge a Friend: Users can invite friends to play by sharing a unique invite link, with scores visible before starting the game.
💾 Database Integration: The dataset is securely stored in MySQL and accessed through a backend API, ensuring no direct access to questions from the browser.
---

## 🛠️ Tech Stack

- **Backend**: Spring Boot
- **Frontend**: React
- **Database**: MySQL
- **API**: RESTful Web Services
- **Styling**: CSS, Bootstrap (for frontend styling)

---

💡 Features
✨ Here are some exciting features of The Globetrotter Challenge:

# Users are presented with 1-2 cryptic clues about a random destination.
Multiple possible destination answers are provided, allowing the user to choose the correct one.
Instant Feedback:

🎉 Correct Answer: Fun animations (like confetti) and a fun fact about the destination are displayed.
😢 Incorrect Answer: A sad-face animation is shown, along with a fun fact to keep the learning experience enjoyable.
Play Again / Next:

# Users can click the ‘Play Again’ or ‘Next’ button to load a different random destination and continue the game.
Score Tracking:

# The app tracks the total score based on correct and incorrect answers, providing a score summary at the end of each round.
Challenge a Friend:

# Users can register with a unique username and challenge friends to play the game by sharing a dynamic image and invite link via WhatsApp.
The invited friend can view the invitee’s score before starting the game, adding a competitive element to the experience.
Secure Dataset Storage:

# All clues, answers, and fun facts are securely stored in the backend database (MySQL), ensuring users cannot access them directly from the browser.

# Responsive Design:

The game is optimized for both desktop and mobile devices, ensuring a seamless experience on all screen sizes.---

## 🧑‍💻 Installation

### Prerequisites

1. **Java 11 or above**
2. **Node.js** (v14 or above)
3. **MySQL Database**
4. **Maven** (for building the backend)
5. **IDE** (IntelliJ IDEA, VS Code, etc.)

### Backend Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-project-name.git

2. Navigate to the backend directory:

cd backend

3. Create a application.properties file inside src/main/resources and configure the 

MySQL database settings:

spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
spring.datasource.username=your_username
spring.datasource.password=your_password

4. Build and run the Spring Boot application:

mvn spring-boot:run

Frontend Installation

1. Navigate to the frontend directory:

cd frontend

2. Install the dependencies:

npm install

3. Start the React development server:

npm start

⚡ Usage

+ Visit the React application at https://intrigued-quizapp.vercel.app/.
+ Use the UI to register, log in, and interact with the app.
+ The Spring Boot server will be running on http://backend-production-2d2c.up.railway.app.



