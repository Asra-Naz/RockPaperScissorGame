# RockPaperScissorGame

Rock, Paper, Scissors Game
This is a simple Java console-based implementation of the classic Rock, Paper, Scissors game. The user plays against the computer, which makes a random selection.

🎮 Game Description
The player selects Rock (0), Paper (1), or Scissors (2).

The computer makes a random selection.

The game then determines the winner based on standard rules:

Rock beats Scissors

Scissors beats Paper

Paper beats Rock

🚀 Getting Started
Prerequisites
Java JDK installed (version 8 or higher)

Terminal or Java IDE (like Eclipse or IntelliJ)

Compile the Program
bash
Copy
Edit
javac RockPaperScissorsgame.java
Run the Program
bash
Copy
Edit
java RockPaperScissorsgame
📥 Sample Input
yaml
Copy
Edit
Welcome to the Rock, Paper, Scissors Game!
Enter your choice:
0: Rock, 1: Paper, 2: Scissors
1
📤 Sample Output
yaml
Copy
Edit
You chose: Paper
Computer chose: Rock
You win!
🧠 How It Works
Input is taken using the Scanner class.

The computer choice is generated using Math.random().

Choices are compared using conditional statements.

The game prints the result: win, lose, or tie.

🔒 Input Validation
The program checks if the user's input is within the range [0, 2]. If not, it terminates and prompts the user to try again.

🛠️ Possible Enhancements
Add a loop to allow multiple rounds

Keep score over multiple rounds

Add input support for full words ("rock", "paper", "scissors")

Implement a GUI using Swing or JavaFX

📄 License
This game is open-source and available for learning, teaching, and personal use.
