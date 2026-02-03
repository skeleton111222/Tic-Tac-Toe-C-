# Tic Tac Toe Console Game (C#)

## Project Description
This project is a simple **Tic Tac Toe** game developed as a **console application in C#**.  
It allows two players to play against each other by taking turns placing their marks (`X` and `O`) on a 3×3 grid.  
The game automatically checks for win and draw conditions and displays the result.

This project is ideal for beginners learning **C#**, **arrays**, **loops**, and **conditional logic**.

---

## Technologies Used
- **Programming Language:** C#
- **Framework:** .NET Console Application
- **Environment:** Visual Studio / VS Code / .NET CLI

---

## Files Included
- `Tic-Tac-Toe-c-sharp.cs` – Contains the complete game logic and UI
- `README.md` – Project documentation
- `.gitignore` - Ignore other files
---

## Features
- Two-player gameplay (Player X vs Player O)
- Console-based board display
- Input validation for moves
- Automatic win detection
- Draw detection
- Clear and user-friendly console interface

---

## How to Compile / Run

1. Clone the repo or download
```
git clone https://github.com/skeleton111222/Tic-Tac-Toe-C-Sharp
```

2. Use CLI or Open it in code editor

### Using .NET CLI
- .NET SDK installed (version 6.0 or later recommended)  
  Check installation:
```
  dotnet --version
```
- Navigate into the project directory
```
cd Tic-Tac-Toe-C-Sharp
```
- Restore dependencies
```
dotnet restore
```
- Build the project
```
dotnet build
```
- Run the application
```
dotnet run
```

Or 

### Using Visual Studio (code editor)
1. Open Visual Studio
2. Open the project folder
3. Press **Ctrl + F5** to run the program

---

## File Structure

```
Tic-Tac-Toe-C-Sharp/
│
├── .gitignore (to ignore other files)
├── README.md (project's info, this file)
└── Tic-Tac-Toe-c-sharp.cs(code file)
```

---

## Sample Output:
```
...................
:     |     |     :
:  X  |  O  |  3  :
:_____|_____|_____:
:     |     |     :
:  4  |  X  |  6  :
:_____|_____|_____:
:     |     |     :
:  O  |  8  |  X  :
:     |     |     :
...................

Player X wins!
```

---

## Notes

- Players must enter a number between 1 and 9
- Invalid or already-used positions are rejected
- The game runs until a win or draw is detected
- Console screen clears after each move for better readability

---

## Future Enhancements

- Add an option to restart the game
- Implement single-player mode with AI
- Add score tracking
- Improve UI using colors
- Convert to a GUI or web-based version

---

## Conclusion

This Tic Tac Toe console application demonstrates core programming concepts such as arrays, loops, conditionals, and user input handling in C#.
It serves as a strong foundation for beginners and can be expanded into more advanced versions with additional features.
