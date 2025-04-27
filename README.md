# RockPaperScissorsGame
This is a simple Java program that lets the user play Rock, Paper, Scissors against the computer by making a selection and determining the winner.

## 📋 Features

- User selects Rock (0), Paper (1), or Scissors (2).
- Computer randomly chooses its move.
- Input validation ensures only valid choices are accepted.
- Displays the result: win, lose, or tie.

## 🛠️ How It Works

1. The user is prompted to enter a choice:  
   - `0` for Rock  
   - `1` for Paper  
   - `2` for Scissors
2. The computer randomly selects a choice (0–2).
3. The program compares the two choices and displays:
   - Tie
   - User wins
   - Computer wins

## 💻 Usage

1. Compile the program:

```bash
javac RockPaperScissorsGame.java
```

2. Run the program:

```bash
java RockPaperScissorsGame
```

3. Follow the prompt to make your choice!

## 📦 Example

```
Welcome to the Rock, Paper, Scissors Game!
Enter your choice
0: Rock, 1: Paper, 2: Scissors
0
Computer chose: 2
You win! - Congratulations!
```

## 🧹 Requirements

- Java JDK 8 or later

## 📚 Future Improvements

- Allow multiple rounds until the user chooses to quit.
- Keep track of the score (wins, losses, ties).
- Add user-friendly names for computer choices instead of just numbers.
- Create a graphical user interface (GUI) version.
