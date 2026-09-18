# PIN POP 🎯

A polished, lightweight, responsive browser puzzle game — **100 levels**, satisfying chain reactions, and smooth gameplay on desktop, tablet, and mobile.

**▶️ Play now:** [https://maliyan04.github.io/pin-pop/](https://maliyan04.github.io/pin-pop/)

---

## 📖 About

**PIN POP** is a casual puzzle / hyper-casual game. You're given a board full of colorful pins and a limited number of taps. Tap a pin to pop it — and it triggers a **chain reaction** that clears every connected pin of the same color. Pick the right pin to clear the most pins per tap, and finish the board before your taps run out.

> **Think carefully. Tap smart. Make the biggest POP!**

---

## ✨ Features

- 🎮 **100 handcrafted levels** — procedurally generated and always solvable
- ⛓️ **Chain reaction mechanic** — pop connected pins of the same color
- 📱 **Fully responsive** — optimized for mobile, tablet, laptop & desktop
- 🎨 **Clean, modern UI** — rounded cards, soft shadows, colorful pins
- 🔊 **Lightweight sound effects** & optional background music (synthesized, no large assets)
- 📳 **Haptic feedback** on supported devices (Vibration API)
- 🏆 **Local progress saving** via `localStorage` — levels & settings persist
- 📴 **Offline-ready** — PWA with Service Worker caching
- ♿ **Accessibility** — respects `prefers-reduced-motion`, keyboard-friendly, large touch targets
- ⚡ **Zero dependencies** — pure HTML, CSS & JavaScript, no frameworks

---

## 🎯 How to Play

1. **Look** at the pin arrangement.
2. **Tap** a pin to pop it and its connected same-colored neighbors.
3. **Trigger chain reactions** to clear large clusters efficiently.
4. **Clear the board** using the available taps.
5. **Complete the level** to unlock the next challenge.

### Goal
Clear the required pins using **as few taps as possible**. Beat the par to earn **3 stars** ⭐⭐⭐.

### Tips
- The **⚡ badge** in the HUD shows the largest group currently on the board — a great hint for your next move.
- Use the **💡 Hint** button (3 per level) to highlight the biggest cluster.
- Plan ahead — sometimes popping a smaller group first creates a bigger one after gravity settles.

---

## 🕹️ Controls

| Platform | Action |
|---|---|
| **Desktop** | Mouse click on pins · `Esc` to pause |
| **Mobile / Tablet** | Touch tap on pins |
| **All** | Buttons: Pause · Restart · Hint |

---

## ⚙️ Settings

Accessible from the Main Menu and the Pause menu:

- **Music** – On / Off
- **Music Volume** – Slider
- **Sound Effects** – On / Off
- **Haptic Feedback** – On / Off *(auto-disabled on unsupported devices)*
- **Restart Current Level**
- **Reset Progress** *(with confirmation)*

All settings are saved automatically.

---

## 🖥️ Tech Stack

- **HTML5** – semantic, accessible markup
- **CSS3** – Flexbox, Grid, `clamp()`, CSS variables, safe-area insets
- **Vanilla JavaScript (ES5-safe)** – no frameworks, no build step
- **Web Audio API** – synthesized SFX & music (zero audio files)
- **Vibration API** – optional haptic feedback
- **Service Worker + Web App Manifest** – PWA / offline support
- **localStorage** – progress & settings persistence (with in-memory fallback)

---

## 📂 Project Structure
