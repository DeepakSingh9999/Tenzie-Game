# 🎲 Tenzies Game (React)

A fun and simple dice game built with **React**. The goal is to roll until all dice show the same number. You can hold dice between rolls to lock their values and strategically reach victory!

---

## 🚀 Live Demo

👉 *(Add your deployed link here — e.g., Vercel, Netlify, GitHub Pages)*

---

## 🕹️ How to Play

1. Click **Roll** to roll all dice.
2. Click on individual dice to **hold** their value.
3. Held dice will not change on the next roll.
4. Keep rolling until **all dice show the same number**.
5. 🎉 You win when every die matches!

---

## 🛠️ Built With

* ⚛️ [React](https://react.dev/)
* 🎨 CSS3
* 🧠 JavaScript (ES6+)
* 🎲 `nanoid` (for unique IDs)

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/tenzies-game.git
```

Navigate into the project directory:

```bash
cd tenzies-game
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

---

## 🏗️ Project Structure

```
tenzies-game/
│
├── src/
│   ├── components/
│   │   └── Die.js
│   ├── App.js
│   ├── index.js
│   └── styles.css
│
├── public/
└── package.json
```

---

## ✨ Features

* 🎲 Random dice generation
* 📌 Hold/unhold dice functionality
* 🏆 Win detection logic
* 🔁 New game reset option
* ⚡ Fast and responsive UI
* 🧩 Clean component-based architecture

---

## 🧠 Game Logic Overview

* Dice are stored in state as an array of objects:

  ```js
  {
    id: "unique-id",
    value: 1-6,
    isHeld: false
  }
  ```
* When rolling:

  * Dice that are **not held** get new random values.
* Win condition:

  * All dice are held.
  * All dice have the same value.

---

## 📸 Screenshot

*(Add a screenshot here if available)*

---

## 📚 What I Learned

* Managing state with `useState`
* Using `useEffect` for win detection
* Handling array state updates in React
* Component reusability
* Conditional rendering

---

## 🚀 Future Improvements

* ⏱️ Add timer
* 🔢 Track number of rolls
* 🏅 High score leaderboard
* 🎵 Sound effects
* 🌙 Dark mode

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgements

Inspired by the Tenzies game concept and built as part of my React learning journey.

