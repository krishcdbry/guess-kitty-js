# 🐱 Guess Kitty

<div align="center">

![Guess Kitty Banner](https://img.shields.io/badge/Guess-Kitty-purple?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTEyIDJjMi4yMSAwIDQgMS43OSA0IDRzLTEuNzkgNC00IDQtNC0xLjc5LTQtNCAxLjc5LTQgNC00bTAgMTJjLTQuNDEgMC04IDEuNzktOCA0djJoMTZ2LTJjMC0yLjIxLTMuNTktNC04LTR6Ii8+PC9zdmc+)

**An addictive, modern puzzle game where you find the hidden kitty!**

[![Live Demo](https://img.shields.io/badge/Live-Demo-success?style=for-the-badge)](https://guess-kitty-js.vercel.app)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![React](https://img.shields.io/badge/React-JS-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)

</div>

---

## ✨ Features

🎨 **Stunning Modern UI** - Beautiful gradient backgrounds, smooth animations, and glassmorphism effects
🎮 **Addictive Gameplay** - Simple yet challenging - find the hidden kitty in a 5x5 grid
📊 **Score Tracking** - LocalStorage-powered score history with statistics (Total, Average, Best, Worst)
📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
🌈 **Smooth Animations** - Delightful hover effects, transitions, and victory animations
⚡ **Lightning Fast** - No build process, instant loading

---

## 🎮 How to Play

1. **Start the Game** - Click the start button on the landing screen
2. **Click the Blocks** - Choose a block to unlock it
3. **Find the Kitty** - Keep clicking until you find the hidden kitty (😊)
4. **Score Points** - The fewer attempts, the higher your score!
   - Formula: `Score = (25 - attempts) × 100`
   - Maximum score: **2,500 points** (find on first try!)
5. **Track Progress** - View your score history and statistics on the right panel

---

## 🚀 Live Demo

Check out the live version: **[guess-kitty-js.vercel.app](https://guess-kitty-js.vercel.app)** _(Update this URL after deployment)_

---

## 💻 Technologies Used

- **React.js** - Component-based UI architecture
- **Vanilla JavaScript (ES6+)** - Modern JavaScript features
- **CSS3** - Advanced styling with gradients, animations, and flexbox
- **LocalStorage API** - Persistent score tracking
- **Font Awesome** - Beautiful icon library
- **Google Fonts (Poppins)** - Modern, clean typography
- **Vercel** - Blazing fast deployment platform

---

## 🛠️ Local Development

### Quick Start

```bash
# Clone the repository
git clone https://github.com/krishcdbry/guess-kitty-js.git

# Navigate to the project
cd guess-kitty-js

# Open in browser
# Simply open index.html in your browser
# OR use a local server:
python3 -m http.server 8000
# OR
npx serve .
```

Visit `http://localhost:8000` in your browser!

### No Build Process Required! 🎉

This project uses browser-based Babel transpilation, so there's no need for npm, webpack, or any build tools. Just open `index.html` and start playing!

---

## 📁 Project Structure

```
guess-kitty-js/
├── index.html              # Main HTML file with React components
├── assets/
│   ├── style.css          # Modern CSS with gradients and animations
│   └── img/               # Game screenshots
├── build/                 # React libraries
├── vendor/                # Font Awesome and dependencies
├── vercel.json           # Vercel deployment configuration
└── README.md             # You are here!
```

---

## 🎨 Design Highlights

### Color Palette
- **Primary Gradient**: Purple/Blue (`#667eea` → `#764ba2`)
- **Success Gradient**: Mint Green (`#11998e` → `#38ef7d`)
- **Error Gradient**: Red/Coral (`#eb3349` → `#f45c43`)

### Key Features
- Animated gradient background
- Glassmorphism (frosted glass) effects
- Smooth 3D hover animations on blocks
- Victory celebration with scaling animations
- Responsive grid layout
- Custom scrollbars
- Backdrop blur effects

---

## 📊 Score Calculation

Your score is calculated based on how quickly you find the kitty:

| Attempts | Score | Difficulty |
|----------|-------|-----------|
| 1-5      | 2000-2500 | 🏆 Amazing! |
| 6-10     | 1500-1900 | 🎯 Great! |
| 11-15    | 1000-1400 | 👍 Good |
| 16-20    | 500-900   | 😊 Not bad |
| 21-25    | 0-400     | 💪 Keep trying! |

---

## 🚀 Deployment

### Deploy to Vercel

```bash
# Install Vercel CLI (if not already installed)
npm i -g vercel

# Deploy
vercel

# Deploy to production
vercel --prod
```

Or simply:
1. Push your code to GitHub
2. Import the repository in [Vercel Dashboard](https://vercel.com)
3. Click "Deploy"!

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is [MIT](LICENSE) licensed.

---

## 👨‍💻 Author

**Krishcdbry**

- GitHub: [@krishcdbry](https://github.com/krishcdbry)
- Portfolio: [krishcdbry.com](https://krishcdbry.com) _(Update with your actual portfolio URL)_

---

## 🙏 Acknowledgments

- Original concept and implementation by Krishcdbry
- Modernized UI with gradient design, animations, and glassmorphism
- Font Awesome for beautiful icons
- Google Fonts for Poppins typeface
- Vercel for hosting

---

## 📸 Screenshots

### Stage 1 - Landing Page
![Guess Kitty JS](https://raw.githubusercontent.com/krishcdbry/guess-kitty-js/master/assets/img/guess-kitty-one.png)

### Stage N/2 - Mid Game
![Guess Kitty JS](https://raw.githubusercontent.com/krishcdbry/guess-kitty-js/master/assets/img/guess-kitty-two.png)

### Stage N - Game Complete
![Guess Kitty JS](https://raw.githubusercontent.com/krishcdbry/guess-kitty-js/master/assets/img/guess-kitty-three.png)

---

<div align="center">

**⭐ Star this repo if you like it! ⭐**

Made with 💜 and lots of ☕

</div>
