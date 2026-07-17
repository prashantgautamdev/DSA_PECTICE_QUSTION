# 🐍 PyGrind — Python DSA & Core Practice Console

**4,116 free, ad-free practice questions for Python developers** — Data Structures & Algorithms *and* Python language fundamentals, all in a single static HTML file. No sign-up, no backend, no tracking. Clone it, open it, start grinding.

[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML%2FCSS%2FJS-e34c26)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](#license)
[![No dependencies](https://img.shields.io/badge/dependencies-zero-4cae7d)](#)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-4b9cd3)](#contributing)

> **Live demo:** deploy in under a minute with GitHub Pages — see [Deploy](#-deploy-your-own-copy-in-60-seconds) below.

---

## What is PyGrind?

PyGrind is a single-page, offline-friendly **interview and learning prep tool** for anyone studying **Python programming** and **Data Structures & Algorithms (DSA)** for coding interviews, college exams, or personal upskilling. It bundles two full question banks into one lightweight console:

| Mode | Questions | Topics | Covers |
|---|---|---|---|
| 🧩 **DSA (Python)** | 2,052 | 20 | Arrays, Strings, Linked Lists, Trees, Graphs, Dynamic Programming, Heaps, Tries, Backtracking, Bit Manipulation, System-style Design (LRU Cache, etc.), Matrix problems |
| 🐍 **Python Core** | 2,064 | 22 | Syntax, Data Types, OOP, Exceptions, File Handling, Generators & Iterators, Decorators, Regex, Multithreading & the GIL, Standard Library, Testing, Memory & Performance |

Every question ships with:
- A clear **problem statement**
- A **hint / explanation** you reveal on demand (so you can genuinely try first)
- A **runnable Python starter snippet** with one-click copy
- A **difficulty tag** (Easy / Medium / Hard)

## Why PyGrind?

- **100% free, 100% ad-free.** No paywalls, no login walls, no "unlock more questions" upsells.
- **Zero backend.** It's one `.html` file — open it locally, host it on GitHub Pages, or drop it on any static host.
- **Built for Python specifically.** Every DSA solution and every core-language example is idiomatic Python 3 — not pseudocode, not Java-ported syntax.
- **Searchable & filterable.** Filter by topic or difficulty, search by keyword, or hit "Random rep" for spaced-practice-style drilling.
- **Session progress tracking.** Mark problems as solved and watch your progress bar fill up (resets per session — no accounts, no data collection).
- **Works offline.** Once loaded, no network calls are made — perfect for practicing on a flight or with spotty wifi.

## Screenshots

> *(Add your own screenshots here after deploying — drag them into this section on GitHub, e.g. `docs/screenshot-dsa.png` and `docs/screenshot-python.png`)*

## 🚀 Deploy Your Own Copy in 60 Seconds

### Option 1 — GitHub Pages (recommended, free hosting)

1. **Fork or clone this repo.**
   ```bash
   git clone https://github.com/prashantgautamev/pygrind.git
   cd pygrind
   ```
2. Push it to your own GitHub repository (if you haven't already):
   ```bash
   git remote set-url origin https://github.com/prashantgautamdev/DSA_PECTICE_QUSTION.git
   git push -u origin main
   ```
3. On GitHub: go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`, choose the `main` branch and `/ (root)` folder, then **Save**.
5. Wait ~1 minute. Your site goes live at:
   ```
   https://github.com/prashantgautamdev/DSA_PECTICE_QUSTION
   ```

That's it — `index.html` is already named correctly for GitHub Pages to serve it automatically.

### Option 2 — Run it locally

No build step, no `npm install`. Just open the file:

```bash
git clone https://github.com/prashantgautadev/pygrind.git
cd pygrind
open index.html        # macOS
start index.html        # Windows
xdg-open index.html     # Linux
```

Or double-click `index.html` in your file explorer.

### Option 3 — Any static host

Drag-and-drop `index.html` onto **Netlify**, **Vercel**, **Cloudflare Pages**, or **surge.sh** — all of them support a single static HTML file with zero configuration.

## 🗂️ Repository Structure

```
pygrind/
├── index.html      # the entire app — UI, styling, and question banks, all in one file
├── README.md        # this file
└── LICENSE           # MIT license
```

There's intentionally no build tooling, no `package.json`, and no external runtime dependencies — the only network requests are for Google Fonts (optional; the page still works if blocked).

## 🧠 How the Question Bank Is Built

Each mode is composed of a set of **hand-written, distinct base problems** (114 for DSA, 129 for Python Core — 243 total), covering the concepts that actually come up in interviews and real projects. Each base problem is expanded into multiple **numbered variants** (different array sizes, targets, parameters) so you get realistic repeated practice reps on the same underlying pattern — similar to flashcard drilling. The variant number is always shown in the UI (e.g. `variant 4/18`), so nothing is hidden or padded silently.

## 🛠️ Tech Stack

- Plain **HTML + CSS + vanilla JavaScript** — no React, no build step, no bundler
- **IBM Plex Sans / IBM Plex Mono** for typography
- Question data is embedded directly in the page as JSON, so the whole thing works from `file://` with no server

## 🤝 Contributing

Contributions are welcome! Ways to help:

- **Add more base problems** to either question bank (`DSA` or `Python Core`) — see the generator scripts if you're regenerating data, or edit the embedded JSON directly for small fixes.
- **Report bugs** or incorrect explanations via [Issues](../../issues).
- **Improve accessibility** (keyboard navigation, screen-reader labels).
- **Add topics** not yet covered (e.g. NumPy/Pandas basics, async/await, type-checking with mypy).

To contribute:
1. Fork the repo
2. Create a branch: `git checkout -b feature/my-improvement`
3. Commit your changes: `git commit -m "Add my improvement"`
4. Push and open a Pull Request

## ❓ FAQ

**Is this affiliated with LeetCode, HackerRank, or any other platform?**
No — PyGrind is an independent, open-source practice tool built from scratch.

**Does it track my progress across sessions?**
Not yet — progress resets on page reload by design (no accounts, no backend, no localStorage). This keeps the tool 100% private and dependency-free. Persistent progress could be added as a future enhancement (see [Contributing](#-contributing)).

**Can I use this for campus placements / coding interview prep in India or anywhere else?**
Yes — that's exactly what it's for. It works completely offline once loaded, so it's great for prep on limited or no internet.

**Is it mobile-friendly?**
Yes, the layout is responsive and works on phones and tablets.

## 📄 License

This project is licensed under the [MIT License](LICENSE) — free to use, modify, and distribute.

---

<p align="center">Made for anyone grinding Python DSA and core concepts before an interview. ⭐ Star this repo if it helped you!</p>
