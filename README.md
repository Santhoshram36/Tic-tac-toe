# Tic-tac-toe

# Tic-Tac-Toe (Python CLI Game)  
A **Tic-Tac-Toe** game implemented in **Python** for two players, played in the **command-line interface (CLI)**.  

## How to Play  
- The game is played on a **3x3 board**.  
- Two players take turns, one using **X** and the other **O**.  
- Players enter the **row (1-3)** and **column (1-3)** where they want to place their mark.  
- The game ends when:  
  - A player **wins** by aligning three marks in a **row, column, or diagonal**.  
  - The board is **full**, resulting in a **tie**.  

## Game Rules  
1. The board is **empty** at the start.  
2. Players take turns to **input their move**.  
3. The game **validates the input**, ensuring:  
   - The move is **within bounds** (1-3 for row and column).  
   - The selected position is **not already occupied**.  
4. The game ends with:  
   - A **win** if a player aligns three symbols.  
   - A **tie** if all spaces are filled with no winner.

