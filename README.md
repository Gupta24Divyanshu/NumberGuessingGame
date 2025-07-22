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
![image](https://github.com/Gupta24Divyanshu/NumberGuessingGame/blob/main/NumberGuessingGame_backend/Images%20and%20Videos/Screenshot%20(141).png)
![image](https://github.com/Gupta24Divyanshu/NumberGuessingGame/blob/main/NumberGuessingGame_backend/Images%20and%20Videos/Screenshot%20(142).png)
![image](https://github.com/Gupta24Divyanshu/NumberGuessingGame/blob/main/NumberGuessingGame_backend/Images%20and%20Videos/Screenshot%20(143).png)
![image](https://github.com/Gupta24Divyanshu/NumberGuessingGame/blob/main/NumberGuessingGame_backend/Images%20and%20Videos/Screenshot%20(144).png)
![image](https://github.com/Gupta24Divyanshu/NumberGuessingGame/blob/main/NumberGuessingGame_backend/Images%20and%20Videos/Screenshot%20(145).png)
![image](https://github.com/Gupta24Divyanshu/NumberGuessingGame/blob/main/NumberGuessingGame_backend/Images%20and%20Videos/Screenshot%20(146).png)
![image](https://github.com/Gupta24Divyanshu/NumberGuessingGame/blob/main/NumberGuessingGame_backend/Images%20and%20Videos/Screenshot%20(147).png)

---

## 🖥️ System Architecture

The application follows a **client-server architecture**:

- **Frontend (Client)**: HTML5, CSS3, JavaScript  
- **Backend (Server)**: Java, Spring Boot, REST API
  
Frontend sends guess using fetch() → Backend validates and responds → Frontend displays result

---

## 🗂️ Project Structure

            NumberGuessingGame\
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

---
            
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

## 🔍 How the Game Works

1. **Start Game**: Random number (1-100) generated on backend.
2. **User Guess**: Frontend captures and sends guess via `fetch()`.
3. **Backend Logic**:

   * Checks if number is in range
   * Validates uniqueness
   * Compares guess
   * Returns feedback + remaining attempts
4. **Frontend UI** updates:

   * Displays result
   * Shows remaining guesses
   * Reveals correct number if attempts exhausted or guess is correct
5. **Reset Game**: Resets number and guess history.

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
