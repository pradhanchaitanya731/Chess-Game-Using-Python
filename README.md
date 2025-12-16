# Chess-Game-Using-Python
This project is a simple Chess game built with Python and Tkinter. It supports legal move generation, check/checkmate/stalemate detection, pawn promotion, move history, and highlights.

---
📖 Overview

This project is a simple Chess game built with Python and Tkinter.
It supports legal move generation, check/checkmate/stalemate detection, pawn promotion, move history, and highlights.
The implementation focuses on clarity and readability, without relying on external dependencies — only Python’s standard library.

<img width="965" height="875" alt="Screenshot 2025-08-25 152740" src="https://github.com/user-attachments/assets/d7be0f82-97eb-4074-a4fa-2737f25fb351" />


🚀 Features

✅ Graphical User Interface with Tkinter.

✅ Legal move generation for all pieces.

✅ Check, checkmate, and stalemate detection.

✅ Pawn promotion to Queen, Rook, Bishop, or Knight.

✅ Move history displayed in algebraic-like notation.

✅ Board highlights:

Selected square

Possible legal moves

King in check

✅ Restart button to reset the game.

⚡ Lightweight: no external dependencies.

⚙️ Rules Implemented

Standard chess piece moves.

Turn-based play between White and Black.

Pawn double-step, captures, and promotion.

No castling (to keep the logic short & clean).

No en passant (simplified pawn rules).

📂 Project Structure

chess_tk.py → Main game script containing all logic (board, moves, UI).

Uses dataclasses for moves and deep-copy for board states.

Board represented as a simple 8x8 2D list.

🎮 How to Play

Run the script:

python chess_tk.py


Click a piece to highlight it and see possible moves.

Click a destination square to move the piece.

For pawn promotion, a popup will let you choose the piece.

Track move history in the side panel.

🖼️ GUI Preview

Board with alternating light/dark squares.

Unicode chess symbols for pieces (♔, ♕, ♖, ♗, ♘, ♙).

Move history sidebar.

🔮 Future Improvements

♜ Add castling.

♟ Add en passant.

🤖 Add AI opponent (minimax/stockfish integration).

🌐 Online multiplayer with sockets/Flask.

✨ This project is perfect for beginners learning Tkinter and chess logic, or as a base to build a more advanced chess engine.
