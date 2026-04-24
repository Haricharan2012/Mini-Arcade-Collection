## 🎮 Mini-Arcade-Collection

A collection of **browser-based games** built using **C (Raylib)** and **Unity (C#)**, compiled to **WebAssembly**, and playable directly in modern web browsers.

This project brings back the charm of classic **flash-style arcade games** with modern web technologies—no installation required.

---

## 🚀 Project Overview

This project aims to create a **versatile, cross-platform browser gaming experience** where users can play multiple games anytime, anywhere.
A centralized web application was developed to host, manage, and provide seamless access to all games directly within the browser.

All games:

* Run directly in the browser 🌐
* Work across devices (PC, mobile, tablet, smart TVs) 📱💻📺
* Support **offline gameplay** ⚡
* Include **leaderboards stored in browser (IndexedDB)** 🗄️

---

## 🕹️ Games Included

| Game Name         | Built With | Description                            |
| ----------------- | ---------- | -------------------------------------- |
| **SpaceX Shoot**  | C + Raylib | A fast-paced space shooting game       |
| **Whack n Smack** | C + Raylib | Reflex-based arcade game               |
| **Anime Puzzle**  | C + Raylib | Puzzle-solving game with anime visuals |
| **Pong**          | Unity (C#) | Classic Pong recreated in Unity        |

---

## ⚙️ Tech Stack

### 🎯 Game Development

* **C + Raylib** (for 3 games)
* **Unity (C#)** (for Pong)

### 🌐 Web Conversion

* **Emscripten** → Converts C/Raylib games to WebAssembly
* **Unity WebGL Build** → Converts Unity game to browser-compatible format

### 💻 Frontend

* HTML5
* CSS3
* JavaScript
* WebAssembly (WASM)

### 🗄️ Storage

* **IndexedDB (Browser Database)**

  * Stores player names
  * Saves scores
  * Displays leaderboard

---

## ✨ Features

* 🎮 Multiple games in one place
* 🌍 Cross-platform compatibility
* 📶 Offline play support
* 🧠 Lightweight (no installation required)
* 🏆 Persistent leaderboard system
* ⚡ Fast performance using WebAssembly

---

## 📊 How It Works

1. User selects a game from the browser interface
2. Game loads using WebAssembly/WebGL
3. After gameplay:

   * User enters their name
   * Score is saved in **IndexedDB**
4. Leaderboard displays ranked scores

---

## 📌 Motivation

Traditional **Flash games** were once hugely popular but became obsolete after Flash was discontinued in 2020.

This project recreates that experience using **modern web technologies**, ensuring:

* Longevity
* Better performance
* Wider accessibility

---

## 🧩 Why WebAssembly?

WebAssembly allows:

* Near-native performance in the browser
* Reuse of C/C++ code
* Smooth graphics rendering (via WebGL)

---

## 🔧 Setup & Run

1. Clone the repository:

```bash
git clone https://github.com/Haricharan2012/Mini-Arcade-Collection.git
cd Mini-Arcade-Collection
```

2. Run using a local server:

```bash
# Python example
python -m http.server
```

3. Open in browser:

```
http://localhost:8000
```

---

## 📷 Screenshots (Optional)

*Add screenshots or GIFs here to showcase gameplay*

## SpaceXShoot
<img width="1670" height="995" alt="Space" src="https://github.com/user-attachments/assets/8527b4ec-ee89-4f4c-bab5-39e027b2d21e" />

---

## Anime puzzle
<img width="1763" height="995" alt="Ani_puzz" src="https://github.com/user-attachments/assets/af79b06e-12c0-439b-9677-b3184475d10b" />

---

## Whack_n_Smack
<img width="1587" height="1001" alt="WHACK1" src="https://github.com/user-attachments/assets/2a1dca06-af6c-4451-802e-fd2630916150" />

---

## Pong
<img width="1587" height="995" alt="Pong" src="https://github.com/user-attachments/assets/fa6114a7-2843-4909-913a-eee31eec2bb5" />

---

## 📹Video Demo

https://github.com/user-attachments/assets/d28edf70-a741-43d7-a847-e51e5ee17463

---

## 🔮 Future Improvements

* Multiplayer support 🌐
* Cloud-based leaderboard ☁️
* More games 🎯
* Improved UI/UX 🎨
* Mobile optimization 📱

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 💡 Acknowledgment

Inspired by classic **browser and flash games**, rebuilt using modern tools to keep the experience alive.

---
