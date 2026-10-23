# 🎯 Real-Time Java Quiz Game

A console-based quiz application built using Java that tests your knowledge of Java programming through 10 multiple-choice questions. Each question has an **8-second time limit**, making the quiz interactive and time-sensitive.

## ✨ Features

- 📝 10 multiple-choice questions on Java fundamentals and OOP concepts
- ⏱️ 8-second time limit for each question
- ✅ Automatic answer validation
- 📊 Real-time score tracking
- 👤 Player name input
- 💡 Displays the correct answer when a response is incorrect or time runs out
- 🏆 Personalized feedback based on the final score
- ⚠️ Handles invalid answers and non-numeric input

## 🛠️ Technologies Used

- **Java** — core programming language
- **Scanner** — reads user input
- **Arrays** — stores questions, options, and correct answers
- **ExecutorService and Future** — manage timed input
- **TimeUnit and TimeoutException** — implement the question time limit
- **Exception Handling** — handles input and execution errors

## 📋 Requirements

- Java Development Kit (JDK) installed
- A terminal or command prompt
- Any Java-compatible code editor (optional)

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

Replace `<your-repository-url>` with the URL of this GitHub repository.

### 2. Navigate to the project folder

```bash
cd Real-Time-Java-Quiz-Game
```

### 3. Compile the Java program

```bash
javac RealTimeQuizGame.java
```

### 4. Run the program

```bash
java RealTimeQuizGame
```

## 🎮 How to Play

1. Start the program.
2. Enter your name.
3. Read each multiple-choice question.
4. Enter an option from `1` to `4` within 8 seconds.
5. View the correct answer when applicable.
6. Check your final score and performance feedback.

## 📊 Scoring System

| Score | Feedback |
|---|---|
| 8–10 | Excellent! |
| 5–7 | Good job! |
| 0–4 | Keep practicing! |

Each correct answer earns one point. The maximum score is **10**.

## 📚 Concepts Practiced

- Java fundamentals
- Arrays and loops
- Conditional statements
- Methods and static members
- Exception handling
- Multithreading and concurrency utilities
- Time-limited input handling

## 🔮 Future Improvements

- Randomize questions and answer options
- Add difficulty levels
- Include more programming topics
- Save player scores and create a leaderboard
- Add a graphical user interface (GUI)
- Improve timeout handling and input validation

## 👨‍💻 Author

Created as a Java programming project to practice core concepts and concurrency utilities.

## 📄 License

No license has been added to this repository. All rights are reserved by default unless a license is added.

---

⭐ If you find this project useful, consider giving the repository a star!
