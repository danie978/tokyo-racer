# Tokyo Racing - Installation Guide

## 🌐 Play Online (Easiest)

### Step 1: Visit the Game
```
https://danie978.github.io/tokyo-racer/game.html
```

### Step 2: Start Playing
- Click "START RACE" for a timed race
- Click "FREE ROAM" to explore
- Use arrow keys or WASD to drive

✅ **No installation needed!**

---

## 💻 Run Locally

### Requirements
- Git
- Python 3.6+ OR Node.js 14+

### Method 1: Python (Recommended)

```bash
# Clone repository
git clone https://github.com/danie978/tokyo-racer.git
cd tokyo-racer

# Start server
python -m http.server 8000

# Open browser
http://localhost:8000/game.html
```

### Method 2: Node.js

```bash
# Clone repository
git clone https://github.com/danie978/tokyo-racer.git
cd tokyo-racer

# Install dependencies
npm install

# Start server
npm start

# Open browser
http://localhost:8000/game.html
```

### Method 3: Live Server (VS Code)

1. Install "Live Server" extension in VS Code
2. Clone the repository
3. Right-click `game.html`
4. Select "Open with Live Server"
5. Browser opens automatically

---

## 📱 Mobile Installation

### iPhone

1. Open Safari
2. Navigate to: `https://danie978.github.io/tokyo-racer/game.html`
3. Tap Share button
4. Select "Add to Home Screen"
5. App appears on home screen

### Android

1. Open Chrome
2. Navigate to: `https://danie978.github.io/tokyo-racer/game.html`
3. Tap menu (three dots)
4. Select "Install app" or "Add to Home Screen"
5. App appears on home screen

---

## 🔧 Development Setup

### Clone & Setup

```bash
# Clone the repository
git clone https://github.com/danie978/tokyo-racer.git
cd tokyo-racer

# Install dependencies (optional)
npm install

# Start development server
python -m http.server 8000
# or
npm start
```

### File Structure

```
tokyo-racer/
├── game.html          # Main game file
├── index.html         # Landing page
├── README.md          # Project info
├── CHANGELOG.md       # Version history
├── RELEASE.md         # Release notes
├── INSTALLATION.md    # This file
├── manifest.json      # PWA manifest
├── package.json       # Dependencies
└── .gitignore         # Git ignore
```

### Editing the Game

All game code is in `game.html`:

```html
<!-- Game canvas -->
<canvas id="canvas"></canvas>

<!-- JavaScript (scroll to bottom) -->
<script>
  // Game code here
</script>
```

---

## 🚀 Deployment

### GitHub Pages (Automatic)

1. Push to GitHub:
```bash
git add .
git commit -m "Update game"
git push origin main
```

2. Enable GitHub Pages:
   - Go to Settings > Pages
   - Source: main branch
   - Click Save

3. Access at: `https://danie978.github.io/tokyo-racer/game.html`

### Custom Domain

1. Buy domain (e.g., `tokyoracing.com`)
2. Add CNAME file with domain
3. Update DNS settings
4. Enable HTTPS

### Vercel (Easy)

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Netlify (Easy)

1. Connect GitHub repository
2. Build command: (leave empty)
3. Publish directory: (root)
4. Deploy

---

## ⚙️ Configuration

### Game Settings

Edit in `game.html` under `gameState`:

```javascript
let gameState = {
    // Adjust these values:
    speed: 0,
    maxSpeed: 300,        // Max km/h
    acceleration: 2,      // Speed increase per frame
    friction: 0.98,       // Air resistance
};
```

### Graphics Settings

Edit Three.js configuration:

```javascript
// Render quality
renderer.setPixelRatio(window.devicePixelRatio);

// Shadow quality
directionalLight.shadow.mapSize.width = 2048;
directionalLight.shadow.mapSize.height = 2048;

// Fog distance
scene.fog = new THREE.Fog(0x1a1a2e, 2000, 5000);
```

---

## 🔌 Troubleshooting

### Game Won't Load

1. Check browser console (F12)
2. Ensure WebGL is enabled
3. Try different browser
4. Clear cache and reload

### Low FPS

1. Close other tabs
2. Lower graphics settings
3. Try different browser
4. Update GPU drivers

### Mobile Issues

1. Use landscape orientation
2. Clear browser cache
3. Try different browser
4. Ensure enough storage

### Network Error

1. Check internet connection
2. Disable VPN
3. Clear DNS cache
4. Try again later

---

## 📞 Support

**Issues or Questions?**

1. Check GitHub Issues: https://github.com/danie978/tokyo-racer/issues
2. Read FAQ: (coming soon)
3. Contact developer: (coming soon)

---

## 🎮 Let's Play!

Now you're ready to start racing!

🏎️ **Happy Racing!**
