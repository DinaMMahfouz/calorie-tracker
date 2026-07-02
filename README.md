# 🍽️ Calorie Tracker

A calorie tracking app that estimates nutrition from food photos using AI image recognition, with manual meal logging as a fallback.

Built as part of my [AI Agents Learning Journey](../../) — this project lives under `claude/calorie-tracker/` to document hands-on work built with Claude.

---

## ✨ Features

- 📸 **Photo-based estimation** — upload or capture a food photo and get an AI-estimated calorie count
- ✍️ **Manual logging** — add meals directly by name/portion when a photo isn't available or the estimate needs correcting
- 📊 **Daily tracking** — view logged meals and running calorie totals

---

## 🛠️ Tech Stack

- **Frontend/App:** JavaScript (Node.js)
- **Testing/Automation:** Playwright MCP (`.playwright-mcp/`) for browser-based test automation
- **Built with:** [Claude Code](https://claude.com/claude-code)

> Note: tech stack listed above is a placeholder — swap in your actual frameworks/libraries (e.g. React, Express, a specific vision API) once confirmed.

---

## 🚀 Getting Started

```bash
# clone the repo
git clone https://github.com/DinaMMahfouz/AI-Agents-Learning-Journey.git
cd AI-Agents-Learning-Journey/claude/calorie-tracker

# install dependencies
npm install

# run the app
npm start
```

> Update these commands to match your actual install/run scripts once finalized.

---

## 📸 Preview

Example food photos used for testing calorie estimation are included in this folder.

---

## 🧪 Testing

This project uses Playwright MCP for automated browser testing — see `.playwright-mcp/` for test configuration and traces.

---

## 📄 License

MIT
