# Contributing to Tokyo Racing

## 🤝 How to Contribute

We welcome contributions! Here's how to help:

### 1. Fork & Clone

```bash
git clone https://github.com/YOUR-USERNAME/tokyo-racer.git
cd tokyo-racer
```

### 2. Create Branch

```bash
git checkout -b feature/your-feature-name
```

### 3. Make Changes

- Edit `game.html` for game code
- Update `README.md` for documentation
- Keep code clean and commented

### 4. Test

```bash
python -m http.server 8000
# Test at http://localhost:8000/game.html
```

### 5. Commit

```bash
git add .
git commit -m "feat: Add your feature description"
```

### 6. Push & Create PR

```bash
git push origin feature/your-feature-name
```

Create Pull Request on GitHub.

---

## 📋 Contribution Guidelines

- ✅ Write clean, commented code
- ✅ Test before submitting
- ✅ Update documentation
- ✅ Follow existing code style
- ❌ No minified code
- ❌ No breaking changes

---

## 🐛 Reporting Bugs

1. Check existing issues first
2. Create new issue with title: `[BUG] Short description`
3. Include:
   - Browser/OS
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots/video if applicable

---

## 💡 Feature Requests

1. Create issue with title: `[FEATURE] Short description`
2. Explain the feature
3. Why it's needed
4. Mockups/screenshots if applicable

---

## 🎨 Code Style

```javascript
// Use camelCase for variables
let playerPosition = { x: 0, y: 0 };

// Use descriptive names
function updateVehiclePhysics() { }

// Comment complex logic
// Calculate tire grip using Pacejka model
const grip = calculateTireGrip(slip);

// Use meaningful variable names
const maxAcceleration = 2;
const airResistance = 0.98;
```

---

## 🚀 Development Areas

### Priority (Help Needed!)
- [ ] Multiplayer implementation
- [ ] Audio system
- [ ] Traffic AI
- [ ] Vehicle customization
- [ ] Leaderboards

### Medium Priority
- [ ] Weather effects
- [ ] More vehicles
- [ ] Map expansion
- [ ] Achievements

### Low Priority
- [ ] Graphics improvements
- [ ] UI tweaks
- [ ] Documentation

---

## 📚 Resources

- Three.js Documentation: https://threejs.org/docs/
- JavaScript Guide: https://developer.mozilla.org/en-US/docs/Web/JavaScript/
- Git Guide: https://git-scm.com/book/

---

## 💰 Support

If you'd like to support development:
- Star the repository ⭐
- Share the game 🎮
- Report bugs 🐛
- Suggest features 💡
- Contribute code 👨‍💻

---

## ❓ Questions?

Create a new GitHub Discussion or open an issue.

**Thank you for contributing! 🙏**
