# 💖 Birthday Animation & Interactive Celebration Web App

> A premium, interactive, and romantic web application designed to deliver an unforgettable digital birthday celebration experience with rich visuals, elegant glassmorphism, 3D flippable photo cards, and web audio soundscapes.

🌐 **Live Demo & Deployment**: [https://birthday-v2-0.netlify.app/](https://birthday-v2-0.netlify.app/)

---

## ✨ Key Features & Highlights

- **🌸 Classy Romantic Pink & Rose Gold Theme**: Designed with deep velvet plum-black backgrounds, soft blush pink gradients, champagne gold accents, and dynamic glassmorphism panels.
- **✨ Interactive Heart Trail Cursor**: Floating glowing pink hearts (`💖`) and rose-gold sparkles drift gracefully following mouse movements and touch gestures in real-time.
- **🎂 Interactive Blowable Candle & Cake**: Recipients can close their eyes, make a secret wish, and tap the candle flame to blow it out—triggering a massive burst of confetti and synthesized wind audio.
- **🎁 Unwrap Surprise Love Letter**: Interactive 3D gift box opening animation revealing a full-page luxury wax-sealed message card and photo frame.
- **🎈 Floating Wish Balloons with Love Emoji Bursts**: Clickable floating balloons that explode into a burst of 16 animated love emojis (`💖`, `🥰`, `💕`, `💘`, `💓`, `💗`, `💌`, `❤️`, `🌹`, `✨`, `🌸`, `💋`) and reveal personalized love wishes.
- **📸 3D Flippable Polaroid Memory Gallery**: Interactive slideshow featuring 3D flip card memory polaroids that flip over to reveal handwritten romantic back-notes for every chapter.
- **🎵 Offline Web Audio Synthesizer**: Built-in sound effects (pop sounds, candle blow wind FX, magic chimes, and ambient soundscapes) created 100% offline via the Web Audio API without requiring external audio files.

---

## 🛠️ Technology Stack

- **Core**: HTML5, Modern JavaScript (ES6+)
- **Styling**: Vanilla CSS3 (Custom Glassmorphism, 3D CSS Transforms, Keyframe Animations, CSS Variables)
- **Graphics**: HTML5 Canvas Particle Engine (Confetti, Stars, Sparkles, and Floating Heart Trails)
- **Audio**: Web Audio API (OscillatorNode, GainNode, AudioContext synthesis)

---

## 📁 Project Structure

```text
Birthday-animation/
├── index.html         # Main HTML5 structure with slide-by-slide sections
├── style.css          # Romantic design system, glassmorphism, & 3D CSS animations
├── script.js         # Particle engine, sound synthesizer, & interactive slide controller
├── gift_photo.png     # Secret gift box revealed photo
├── pic1.jpg           # Memory Gallery Chapter I Photo
├── pic2.jpg           # Memory Gallery Chapter II Photo
├── pic3.jpg           # Memory Gallery Chapter III Photo
└── README.md          # Project documentation
```

---

## 🚀 How to Run Locally

1. **Clone or Download** the repository to your local directory.
2. Open `index.html` in any modern web browser (Google Chrome, Mozilla Firefox, Safari, Microsoft Edge).
3. Alternatively, serve via a local web server (e.g., VS Code Live Server or `npx serve`).

---

## 💌 Personalization & Customization

### 1. Custom Recipient Name via URL
You can pass the recipient's name directly in the web browser URL using the `name` parameter:
```text
index.html?name=Sophia
```
This dynamically updates the greeting title across the entire celebration to:  
*“Happy Birthday, Sophia! ✨”*

### 2. Customizing Photos & Messages
- Replace `gift_photo.png`, `pic1.jpg`, `pic2.jpg`, and `pic3.jpg` with your own personal photographs.
- Modify the romantic message cards and back-notes inside `index.html` or `script.js` to add your custom love notes and dates.

---

## 📄 License

Created with ❤️ for special celebrations. Free to use, personalize, and share.
