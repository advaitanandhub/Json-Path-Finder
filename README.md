# 🔍 JSON Path Finder

A lightweight, browser-based tool to explore JSON structures and instantly find the dot-notation path of any key — no installation required.

## ✨ Features

- 📂 **Interactive tree view** — Click any key to reveal its full JSON path
- 📋 **One-click copy** — Copy the path to clipboard instantly
- 🎨 **Beautify / Minify** — Format or compact your JSON with a single click
- 🌙 **Dark mode** — Toggle between light and dark themes
- ⚡ **Zero dependencies** — Pure HTML, CSS, and JavaScript

## 🚀 Demo

Just open `jsonpathfinder.html` in any browser — no server or build step needed.

## 📸 Preview

> Paste any JSON on the left → Click a key → Get the path instantly on the right.

## 🛠️ How to Use

1. Paste or type your JSON in the **left panel**
2. Click **Beautify** to format it (optional)
3. Click any **key** in the tree on the right
4. The full dot-notation path appears at the top (e.g. `customer.location.city`)
5. Hit **Copy** to copy the path to your clipboard

## 📁 Project Structure

```
jsonpathfinder.html   ← Single file, everything included
README.md
```

## 🧑‍💻 Tech Stack

- HTML5
- CSS3 (CSS Variables for theming)
- Vanilla JavaScript (no frameworks)

## 🤝 Contributing

Feel free to open issues or submit PRs for new features — things like:
- Array index support in paths (e.g. `items[0].name`)
- Search/filter within the tree
- Export all paths as a list

## 📄 License

MIT — free to use, modify, and distribute.
