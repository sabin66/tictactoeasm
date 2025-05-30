# Tic-Tac-Toe in Assembly (emu8086)

A simple implementation of the classic **Tic-Tac-Toe** game using x86 Assembly language for the **emu8086** emulator.

## Features

- 2-player mode (Player X and Player O)
- Turn-based gameplay logic
- Win detection (horizontal, vertical, diagonal)
- Draw detection after 9 moves
- Visual 3x3 game board (text-based)

## Technologies

- Language: x86 Assembly
- Emulator: [emu8086](http://www.emu8086.com/)

## How to Run

1. Open the project in the **emu8086** IDE.
2. Compile and run the program.
3. Follow on-screen prompts to make your moves (players take turns).
4. Game ends automatically after a win or a draw.

## Notes

- Internal variables like `win_flag` and `moves_counter` manage the game state.
- Board is represented as a 3x3 grid, displayed using ASCII characters.
- Uses `jmp fim` to end execution in a controlled infinite loop (can be replaced with `int 21h` or `int 20h` for proper DOS exit).

## ![image](https://github.com/user-attachments/assets/2cf85842-2194-4c1b-a925-df31186bd8b2)
## ![image](https://github.com/user-attachments/assets/3873a743-9cdd-4cfe-9a0b-2b2af1e40894)



