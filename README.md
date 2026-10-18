# ✊✋✌️ Rock-Paper-Scissors Game (C++)

A robust, console-based **Rock-Paper-Scissors** game built using **C++**. This project is designed following clean modular programming principles, leveraging `struct` data encapsulation, enumerations (`enum`), and structured game-loop logic to deliver an interactive gaming experience with automated score tracking.

---

## 🌟 Key Features

* **🎮 Interactive Multi-Round Gameplay:** Play a configurable number of rounds (defaulted to 3 rounds per match) against a computer opponent.
* **🤖 Smart Random AI:** The computer makes randomized choices (`Stone`, `Paper`, or `Scissors`) utilizing C++ random number generators (`<cstdlib>` and `<ctime>`).
* **📊 Comprehensive Score Tracking:** Tracks player wins, computer wins, and draw rounds dynamically across the match.
* **🏆 Intelligent Winner Determination:** Automatically evaluates round-by-round results and determines the ultimate match winner.
* **🔄 Replayability:** Built-in loop allowing users to restart and play multiple consecutive matches seamlessly with automatic screen clearing.

---

## 📁 Project Structure

```text
Rock-Paper-Scissors-CPP/
│
├── main.cpp         # Core game logic, round processing, score tracking, and execution loop
└── README.md        # Comprehensive project documentation
🛠️ Concepts & Technologies Applied
Language: C++

Data Structures (struct):

stRoundInfo: Stores individual round details (Round number, choices, winner, and winner name).

stGameResults: Manages overall session statistics (Total rounds, win counts, draws, and final match winner).

Enumerations (enum): Type-safe state management for choices (enGameChoice) and winners (enWinner).

Modular Functions: Separating concerns into specialized functions (WhoWonTheRound, WhoWonTheGame, PrintRoundResults, etc.).

Control Flow: Robust do-while loops for game re-playability and input validation to restrict user choices between 1 and 3.

⚙️ How to Compile and Run
1. Requirements
Any standard C++ compiler supporting C++11 or higher (e.g., GCC, Clang, MSVC).

2. Compilation
Ensure main.cpp is downloaded in your working directory. Open your terminal or command prompt and run:

Bash
g++ main.cpp -o rps_game
3. Execution
On Windows:

DOS
rps_game.exe
On Linux / macOS:

Bash
./rps_game

🎮 How to Play
Run the executable. The game will automatically clear the screen and start a 3-round match.

When prompted, enter your choice by typing the corresponding number:

1 for Stone

2 for Paper

3 for Scissors

View the round results showing your choice, the computer's choice, and the round winner.

At the end of the match, view the final summary of wins and losses, and choose whether to play again (Y/N).

👤 Author
Ibrahim Al-Tarifi

Software Engineering Student & C++ Developer

Focused on Algorithms, Data Structures, and Clean Code Architecture.
