# 🍽️ Calorie Tracker

An AI-assisted calorie tracker that estimates nutrition from food photos using image recognition, with manual meal logging as a fallback.

Built as part of my [AI Agents Learning Journey](../../) — this project lives under `claude/calorie-tracker/` to document hands-on work built with Claude Code.

---

## ✨ Features

- 📸 **Photo-based estimation** — upload or capture a food photo and get an AI-estimated calorie count
- ✍️ **Manual logging** — add meals by name/portion when a photo isn't available or an estimate needs correcting
- 📊 **Daily tracking** — view logged meals and running calorie totals

---

## 🛠️ Tech Stack

<!-- CONFIRM THESE — replace with the actual libraries/APIs you used, then delete this comment. -->

- **App / Frontend:** JavaScript (Node.js) — _replace with your actual framework, e.g. React / Express_
- **Vision / AI:** _replace with the actual model or API used for image estimation_
- **Testing:** Playwright (via `.playwright-mcp/`) for browser-based test automation
- **Built with:** [Claude Code](https://claude.com/claude-code)

---

## 🚀 Getting Started

<!-- CONFIRM these commands match your actual scripts in package.json, then delete this comment. -->

```bash
# clone the parent repo
git clone https://github.com/DinaMMahfouz/AI-Agents-Learning-Journey.git
cd AI-Agents-Learning-Journey/claude/calorie-tracker

# install dependencies
npm install

# run the app
npm start
```

---

## 📸 Demo

<!-- HIGH PRIORITY: add a screenshot or a short GIF of the app estimating calories from a photo.
     Put the image in this folder and reference it here, e.g.:
     ![Calorie Tracker demo](./demo.gif)
-->

_A short demo GIF will go here._

Example food photos used to test calorie estimation are included in this folder.

---

## 🧪 Testing

This project uses Playwright for automated browser testing — see `.playwright-mcp/` for test configuration and traces.

---

## 📄 License

MIT
