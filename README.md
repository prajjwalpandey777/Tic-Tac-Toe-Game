# 🎮 Tic Tac Toe Game

A stylish and interactive **Tic Tac Toe Game** built using **HTML, CSS, and JavaScript** with a modern **Neon UI Theme**.
This game allows two players to play turn-by-turn with automatic winner detection and game reset functionality.

---

## 🚀 Features

* ✅ Two-player gameplay (X vs O)
* ✅ Automatic winner detection
* ✅ Reset Game button
* ✅ New Game option after winning
* ✅ Neon cyberpunk-inspired UI
* ✅ Responsive design using `vmin`
* ✅ Smooth glowing effects using CSS

---

## 🛠️ Technologies Used

* **HTML5** – Structure of the game 
* **CSS3** – Styling and neon effects 
* **JavaScript (ES6)** – Game logic and interactions 

---

## 📂 Project Structure

```bash
tic-tac-toe/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 🎯 How to Play

1. Click on any empty box to make a move.
2. Players alternate turns between **O** and **X**.
3. The game automatically detects the winner.
4. Click:

   * **Reset Game** → Restart the current match
   * **New Game** → Start a completely new game after winning

---

## 🎨 UI Theme

This project uses a futuristic neon theme:

* 🔹 Neon Cyan (`#00FFE5`)
* 🔸 Neon Pink (`#FF0050`)
* ⚫ Dark Background (`#30343F`)

The glowing effects are created using:

* `box-shadow`
* `text-shadow`

---

## 🧠 Game Logic

The JavaScript logic includes:

* Turn management
* Winning pattern checks
* Button disabling after moves
* Winner display message
* Game reset functionality

Winning patterns are stored in an array:

```javascript
const winPatterns = [
 [0,1,2],
 [3,4,5],
 [6,7,8],
 [0,3,6],
 [1,4,7],
 [2,5,8],
 [0,4,8],
 [2,4,6]
];
```



---

## 📸 Preview

✨ Neon glowing Tic Tac Toe board with interactive gameplay.

---

## 🔮 Future Improvements

* 🤖 Add AI mode
* 🌐 Multiplayer support
* 🔊 Sound effects
* 🎵 Background music
* 📱 Better mobile optimization
* 🏆 Score tracking system

---

## 👨‍💻 Author

Created with ❤️ by **Prajjwal Pandey**
