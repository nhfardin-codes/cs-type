<div align="center">

# ⌨️ CSType

**A sleek, strict, and tactile typing engine built for developers and mechanical keyboard enthusiasts.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Play_Now!-38bdf8?style=for-the-badge&logo=github)](https://nhfardin-codes.github.io/cs-type/)
[![Made with Vanilla JS](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]()
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)]()
[![Tone.js](https://img.shields.io/badge/Tone.js-Synthesized_Audio-ff4b4b?style=for-the-badge)]()

</div>

---

> **Why CSType?**  
> Most typing websites are visually cluttered and lack audio feedback. **CSType** fixes that by combining a distraction-free, dark-mode terminal aesthetic with mathematically synthesized mechanical keyboard sounds. Every keystroke gives you satisfying tactile feedback, and every mistake hits you with a heavy *thock*.

## ✨ Features

*   🎵 **Synthesized Mechanical Audio:** Powered by Tone.js, featuring sharp FM/Noise clicks for correct letters and heavy Membrane Synth "clacks" for errors.
*   🎯 **Strict Letter-by-Letter Tracking:** Smooth, responsive cursor that tracks your exact position, just like professional typing software.
*   🚫 **Spacebar Punishment System:** Try to skip a word before finishing it? The engine will highlight your mistakes in red, jump to the next word, and trigger an aggressive error sound. 
*   💾 **Local High Scores:** Automatically saves your highest WPM in your browser so you always have a target to beat.
*   💻 **CS & Dev Themed:** Practice typing real C syntax, Linux terminal commands, and computer science concepts instead of boring nursery rhymes.
*   🌙 **Sleek UI:** Built with Tailwind CSS and the beautiful `JetBrains Mono` developer font.

## 🚀 Live Demo

You don't need to download anything to play.  
👉 **[Click here to play CSType Live](https://nhfardin-codes.github.io/cs-type/)**

## 🎮 How to Play

1. Click anywhere on the screen (or press any key) to focus the engine and initialize the audio context.
2. The 60-second timer starts on your very first keystroke.
3. Type the highlighted text as fast and accurately as you can.
4. Use **Backspace** to correct mistakes. 
5. Hit **Escape** (Esc) at any time to instantly restart the test.

## 🛠️️ Tech Stack

CSType is built entirely on the frontend with zero dependencies to install:
*   **HTML5 / DOM API:** For the core structure and letter-by-letter rendering.
*   **Vanilla JavaScript:** For the strict typing validation logic, WPM calculation, and local storage.
*   **Tailwind CSS (via CDN):** For rapid, modern, dark-mode styling.
*   **Tone.js:** For browser-based audio synthesis (generating sound waves in real-time without relying on static `.mp3` files).

## 👨‍💻 Local Development

If you want to modify the code, add your own text pools, or tweak the synthesizer frequencies:

1. Clone the repository:
   ```bash
   git clone https://github.com/nhfardin-codes/cs-type.git
   ```
2. Open the directory:
   ```bash
   cd cs-type
   ```
3. Open `index.html` in your favorite web browser. That's it! No build steps required.

---
<div align="center">
  <i>Built by Nur Hasan Fardin.</i>
</div>