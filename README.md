# 🎓 Student Progress Tracker (Landscape Line Graph)

An attractive, interactive web app for tracking student progress using vertical line graphs with circular name badges at the top, fractional quarter-step increments (`¼`, `½`, `¾`, `1`, `1 ¼`, `1 ½`, `1 ¾`, `2`, ... up to `21`), and a widescreen landscape layout.

---

## ✨ Features

- 📏 **Vertical Line Graph per Student**:
  - Each student has a vibrant, glowing vertical pole/stem.
  - As progress increases, the line rises dynamically from bottom to top.
- ⭕ **Top Circle Badge with Student Name**:
  - A stylized circular bubble sits directly at the top of the line.
  - Inside the circle: the student's name and avatar icon.
  - Floating badge directly above displays their current fractional score.
  - Click on any circle badge to rename, customize color, set direct value, or delete.
- ➕ / ➖ **Tactile Plus & Minus Stepper Buttons**:
  - Instant fractional adjustments in quarter-step intervals (`+¼` / `-¼`).
  - **Press & hold** any button for smooth continuous auto-scrolling adjustments.
  - Accompanied by synthesized audio tones that climb higher in pitch as students climb the ranks!
- 🔢 **Fractional Scale (0 to 21)**:
  - Supports: `¼` (1/4), `½` (1/2), `¾` (3/4), `1`, `1 ¼` (1 1/4), `1 ½` (1 1/2), `1 ¾` (1 3/4), `2`, up to **21**.
  - Left Y-axis displays fractional and whole ticks aligned with guidelines.
  - Configurable target scale: **1 to 21**, **1 to 20**, **1 to 15**, or **1 to 10**.
- 📱 **Native Landscape (Horizontal) Layout**:
  - Specially formatted for **horizontal / landscape orientation** so all students line up across the screen with plenty of vertical height for the graph bars.
  - Features an orientation guide prompt if viewed in portrait mode.
- 🎉 **Celebratory Milestone Confetti & Chimes**:
  - Triggers animated confetti burst and celebratory chime when a student reaches the top goal (20/21)!
- 💾 **Automatic Local Storage**:
  - All students, custom colors, and progress scores are saved automatically in the browser.
- ⚡ **Zero Dependencies / 100% Offline Capable**:
  - Completely self-contained in a single lightweight file (`index.html`). No npm install or backend required.

---

## 🚀 How to Run Locally

### Option A: Direct Open (Easiest)
Simply double-click `index.html` to open it in Chrome, Edge, Safari, or Firefox on your computer or tablet!

### Option B: Local Web Server
You can also run a quick local HTTP server:

```bash
# Using Python:
python -m http.server 8000
```
Then visit: `http://localhost:8000`

```bash
# Using Node / npx:
npx serve .
```

---

## 🌐 Simple Hosting Options (Free & Instant)

Because the app is a single, zero-dependency `index.html` file, hosting it online takes under 1 minute:

### 1. Netlify Drop (Zero code, takes 15 seconds)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop this folder (`progress`) right onto the web page.
3. Netlify will instantly give you a free public link (e.g., `https://your-app.netlify.app`).

### 2. GitHub Pages (Free forever)
1. Create a repository on GitHub (e.g. `student-progress`).
2. Upload `index.html`.
3. Go to **Settings** → **Pages** → under **Source** select `Deploy from a branch` (select `main` branch and `/root`).
4. Click **Save**. Your app will be live at `https://<your-username>.github.io/<repo-name>/`.

### 3. Vercel
1. Run `npx vercel` in this folder, or connect your GitHub repository to Vercel for instant free deployment.

---

## 📱 Mobile Tips

- **Rotate Device**: Hold your phone in **Horizontal (Landscape)** mode for the full widescreen classroom view.
- **Add to Home Screen**: On Safari (iOS) tap *Share → Add to Home Screen* or on Chrome (Android) tap *⋮ → Install App* for a full-screen app experience.
