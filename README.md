# Go Game: A Beginner's Guide

Go is an ancient board game that originated in China over 2,500 years ago. It is a strategy game that emphasizes territory control, patience, and deep thinking.

## Basic Rules of Go

### The Board and Stones
Go is played on a **19x19 grid**, with black and white stones.  
*Players take turns placing one stone at a time on the intersections of the board.*  
***Controlling more territory than your opponent is the key to winning.***

### Game Flow
1. Set up the board and stones
2. Decide who plays black and white (black moves first)
3. Players alternate turns, placing stones
4. The game ends when both players pass

### Important Terms
- **Liberty**: An empty point next to a stone  
- *Capture*: Surrounding an opponent's stones and removing them  
- ***Ko***: A repeating capture scenario that requires a specific rule to avoid infinite loops

---

## Recommended Resources
Learn more about Go strategies and rules at [Go on Wikipedia](https://en.wikipedia.org/wiki/Go_(game)).

---

## Example Pseudocode
place_stone(player, x, y)` places a stone at the specified intersection  

```python
def place_stone(board, player, x, y):
    if board[x][y] == 0:
        board[x][y] = player
        print(f"{player} placed a stone at ({x},{y})")
    else:
        print("This spot is already occupied!")
```


| Stone Color | Description                              |
|------------ |------------------------------------------|
| Black       | Moves first, controls key positions      |
| White       | Moves second, more defensive             |
