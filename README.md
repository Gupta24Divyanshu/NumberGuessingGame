# 🔢 Number Guessing Game using Spring Boot



> 🚀 Codveda Internship Project – Level 1 Task 1

---

## 🔧 Features

🎲 Random number is generated between 1 and 100.

⌛ User has only 5 unique guesses to find the number.

📢 Immediate feedback: "Too high", "Too low", "Correct".

⚠️ Repeated guesses are not allowed.

🔄 Reset button starts a new game with a fresh number.

🛑 After 5 attempts, the correct answer is revealed.

---

## 🖼️ Screenshots

---

## 🖥️ System Architecture

The application follows a **client-server architecture**:

- **Frontend (Client)**: HTML5, CSS3, JavaScript  
- **Backend (Server)**: Java, Spring Boot, REST API
  
Frontend sends guess using fetch() → Backend validates and responds → Frontend displays result

---

## 🗂️ Project Structure
G:\
└── Codveda\
    └── level_1\
        └── Task_2\
            ├── NumberGuessingGame\
            │   ├── frontend\
            │   │   ├── index.html
            │   │   ├── style.css
            │   │   └── script.js
            │   └── backend\
            │       ├── src\
            │       │   └── main\
            │       │       └── java\
            │       │           └── com\
            │       │               └── example\
            │       │                   └── game\
            │       │                       ├── GameApplication.java
            │       │                       └── GuessingGameController.java
            │       ├── pom.xml
            │       └── application.properties

----
            
## 🧰 Technology Stack

| Area       | Tech Stack                             |
|------------|----------------------------------------|
| Frontend   | HTML5, CSS3, JavaScript                |
| Backend    | Java 21, Spring Boot 3.5.3, Maven      |
| Tools      | VS Code, Git, GitHub, npm, Live Server |

---



▶️ Steps to Run Application

✅ Start Backend (Spring Boot)
cd G:\Codveda\level_1\Task_2\NumberGuessingGame\backend
mvn spring-boot:run

Default Port: 8080 To change port:

# application.properties
server.port=8081

✅ Start Frontend (Live Server)
cd G:\Codveda\level_1\Task_2\NumberGuessingGame\frontend
npm init -y                   # Run once
npm install live-server --save-dev
npx live-server

Open in browser at: http://localhost:5500/

---

## 🔍 How It Works

User starts the game with the Start Game button.

A number is generated in the backend using Random.

User submits a guess from the frontend.

Backend validates and checks:

Is it within range?

Has it been guessed before?

Is it correct?

Response is shown instantly with number of attempts left.

After 5 attempts or a correct guess, user can reset the game.

---

## 💡 Future Improvements

🎯 Add difficulty levels (Easy, Medium, Hard)
🧠 Add guess history on screen
💾 Track high scores with localStorage
🔁 Add timer for challenge mode
🎨 Use animations and sound effects
🌍 Convert to multilingual UI

---

## 🙋‍♂️ Author

| Name            | GitHub                                        | LinkedIn                                                    | Email                                                             |
| --------------- | --------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------------- |
| Divyanshu Gupta | [GitHub](https://github.com/Gupta24Divyanshu) | [LinkedIn](https://linkedin.com/in/divyanshu-gupta-dev670/) | [divyanshugupta670@gmail.com](mailto:divyanshugupta670@gmail.com) |

---
