# CodeBite: Gamified Web Dev Arena 🚀

CodeBite is a standalone, client-side EdTech web application built for Gen Z students learning **HTML5**, **CSS3**, **JavaScript**, and **jQuery**.

Inspired by Duolingo's gamification mechanics, CodeBite breaks down web development concepts into interactive, bite-sized lessons with live feedback and instant sandbox practice.

---

## 🌟 Key Features

- **The "3-Beat Card" Educational Pattern**:
  1. **Beat 1 (Concept Bite)**: Syntax blueprint + ELI5 (Explain Like I'm 5) summary + live mini-example preview.
  2. **Beat 2 (Micro Challenge)**: Interactive fill-in-the-blank code chips & bug-hunt quizzes.
  3. **Beat 3 (Live Sandbox Test)**: Real-time code editor with live `<iframe>` rendering, automated test case validation, and celebratory confetti!

- **Duolingo-Style Gamification Engine**:
  - **Skill Level Selection**: *Entry*, *Pro*, and *Expert* levels.
  - **Hearts / Lives System**: 5-heart pool with an interactive **Warm-Up Heart Refill Drill** trivia modal when low on lives.
  - **XP & Streaks**: Earn +10 XP per lesson, +20 XP for sandbox builds, and track daily calendar streaks.
  - **Visual Skill Roadmap**: Winding progression path across 4 core tracks (HTML5, CSS3, JavaScript, jQuery).

- **Built-in Live Web Sandbox**:
  - Multi-tab split editor (**HTML**, **CSS**, **JS/jQuery**) with auto-rendering live preview.
  - Includes pre-loaded starter kits (*jQuery BG Switcher*, *Responsive Flexbox Card*, *Character Counter*).

- **Zero Backend / 100% Client-Side**:
  - All state, progress, streaks, and settings persist exclusively via browser `localStorage`.
  - Supports **Export JSON** backup and **Reset Progress** options.

---

## 🚀 How to Run Locally

Since CodeBite is a 100% single-page client-side app, you don't need any complex build tools or node servers!

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/codebite.git
   cd codebite
   ```
2. **Open in browser**:
   Simply double-click `index.html` or open it in your favorite browser:
   ```bash
   open index.html  # On macOS
   ```

---

## 🌐 Deploy to GitHub Pages (Free Hosting)

1. Push this repository to GitHub.
2. Go to your repository settings on GitHub: **Settings** -> **Pages**.
3. Under **Build and deployment** -> **Branch**, select `main` (or `master`) branch and folder `/ (root)`.
4. Click **Save**. Your app will be live at `https://YOUR_USERNAME.github.io/codebite/`!
