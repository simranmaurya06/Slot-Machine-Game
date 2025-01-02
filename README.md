**Slot Machine Game**

A console-based slot machine game built in Python, where players can deposit funds, place bets, and spin the reels for a chance to win. This project is perfect for learning Python basics like functions, loops, and conditionals.


# **Features**
- Deposit money to start the game.
- Bet on 1 to 3 lines, with flexible betting amounts.
- Randomized slot spins with a variety of symbols.
- Automatic calculation of winnings and updates to the balance.
- Simple and intuitive text-based interface.


# **How to Play**
1. *Start the game*: Rur desired amount.
2. *Set up your bet*:
   - Choose the number of lines to bet on (1–3).
   - Specify the amount to bet per line (within $1 to $100).
3. *Spin the slot machine*: The game will display the results and calculate your winnings.
4. *Continue or quit*: Check your balance and decide whether to keep playing or exit the game.


# **Game Rules**
- Bets per line must be between *$1 and $100*.
- You can bet on a maximum of *3 lines* per spin.
- Matching symbols on a line determine winnings:
  - *A*: 5x multiplier
  - *B*: 4x multiplier
  - *C*: 3x multiplier
  - *D*: 2x multiplier
- Your balance is updated after each spin.
  

# **Setup and Execution**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Slot-Machine.git
   ```
2. Navigate to the project directory:
   cd Slot-Machine
3. Run the game:
   python slot_machine.py


# **Example Gameplay**
What would you like to deposit? $100
Enter the number of lines to bet on (1-3): 2
What would you like to bet on each line? $10
You are betting $10 on 2 lines. Total bet is: $20

Slot Machine:
A | B | C
A | A | A
C | B | D

You won $50.
You won on lines: 2
Current balance is: $130


# **Technologies Used**
- Python 3.10+
- Random module for generating slot spins.


# **Future Enhancements**
- Add a graphical interface using `tkinter` or `PyQt`.
- Introduce more symbol types and dynamic reels.
- Implement a leaderboard to track high scores.


# **License**
This project is open-source and licensed under the [MIT License](https://opensource.org/licenses/MIT).
