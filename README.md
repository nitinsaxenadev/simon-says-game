# 🎮 Simon Says Game

An interactive browser-based memory game built using vanilla JavaScript and DOM APIs. Implements dynamic sequence generation, asynchronous event timing, and real-time state management without external dependencies.

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
</p>

---

## 📖 About

Simon Says is a memory game where the computer plays a sequence of flashing colored tiles, and the player has to repeat it back in the same order. Each round the sequence grows by one — one wrong move and the game is over. This project recreates that classic in the browser using plain JavaScript, with no external dependencies.


---
<img width="1892" height="911" alt="Game play" src="https://github.com/user-attachments/assets/d7b27e0b-1e7c-4bba-940f-a69070b95855" />


## ✨ Features

- 🎲 Randomly generated, ever-growing color sequences
- ⚡ Visual feedback for both the computer's sequence and your input
- 🏁 Game-over detection with your final score displayed
- 🪶 Zero dependencies — pure HTML, CSS, and JavaScript

---

## 🗂️ Project Structure

```
simon-says-game/
├──README.md
├──Sreenshots.zip
│  └── gameplay.png      # Screenshot used in this README
├──Js/
│   └── app.js           # Game logic
├──index.html            # Main HTML file
└──  css/
      └── style.css      # Styling for the game board and buttons


```

---

## ▶️ How to Play

1. Press any key to start the game.
2. Watch the sequence of colors flash on the board.
3. Click the tiles in the same order.
4. Each round adds a new color to the sequence — get as far as you can.
5. One wrong move ends the game and shows your final score.

---

## 💻 Getting Started

No build tools, installs, or dependencies required.

### Clone the repository

```bash
git clone https://github.com/nitinsaxenadev/simon-says-game.git
cd simon-says-game
```

### Run it

Simplest option — just open `index.html` directly in your browser.

Or serve it locally:

```bash
# Using Python 3
python -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 (Flexbox) | Layout and styling |
| JavaScript (ES6) | Game logic and DOM manipulation |

---

## 🌱 Roadmap / Possible Improvements

- [ ] High score tracking with `localStorage`
- [ ] Sound effects for each color and game over
- [ ] Adjustable difficulty / playback speed
- [ ] On-screen restart button
- [ ] Fully responsive layout for small mobile screens
- [ ] Keyboard controls (map keys 1–4 to tiles)

Contributions and suggestions are welcome — feel free to open an issue or a pull request.

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

---
## 📄 License

This project is open-source software licensed under the [MIT License](LICENSE). You are free to use, modify, distribute, and contribute to this project.


## 🙋 Author

Built by **Nitin Saxena**
- GitHub: [@nitinsaxenadev](https://github.com/nitinsaxenadev)

If you like this project, consider giving it a ⭐ on GitHub!
