# MindGraph 🧠

An interactive, browser-based mind mapping tool for building and exploring concept graphs — no installation, no backend, no account required.

![MindGraph demo](./assets/demo.gif)
> *Coming soon — add a GIF of the tool in action*

---

## ✨ Features

- **Visual graph builder** — create nodes and connections interactively
- **Node groups** — organize concepts into Ceiling, Floor, and Related categories, each with distinct visual shapes
- **Force-directed layout** — nodes automatically arrange themselves using physics simulation
- **Guided connection flow** — step through node pairs and define relationships with intermediate concepts
- **Drag & drop** — reposition nodes freely on the canvas
- **Delete nodes** — select any node and press `Delete` to remove it

### 🚧 Roadmap
- [ ] Export graph as image (PNG)
- [ ] Export/import graph as JSON
- [ ] Save and load sessions (localStorage)
- [ ] Edit node labels after creation
- [ ] Directed edges (arrows)

---

## 🚀 Getting Started

No installation needed. Just open `index.html` in your browser.

```bash
git clone https://github.com/LuisaCampanhaH/MindGraph.git
cd MindGraph
open index.html
```

Or try the **[live demo →](https://luisacampanhah.github.io/MindGraph)** *(GitHub Pages)*

---

## 🎮 How to Use

**Phase 1 — Define your groups**

| Field | Description |
|---|---|
| Ceiling | Top-level concepts (rendered as upward triangles) |
| Floor | Ground-level concepts (rendered as downward triangles) |
| Related | Supporting concepts (rendered as hexagons/diamonds) |

**Phase 2 — Build connections**

The tool steps through every pair of nodes and asks you to define a connecting concept. Type the intermediate idea and press `Enter` to confirm, or `→ Skip` to move on.

**Controls**

| Action | How |
|---|---|
| Move node | Click and drag |
| Select node | Click |
| Delete node | Select + `Delete` key |
| Confirm pair | `Enter` |
| Skip pair | `Escape` or Skip button |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla JavaScript (ES6+) |
| Rendering | HTML5 Canvas API |
| Layout | Custom force-directed simulation |
| Styling | CSS3 |

No frameworks. No dependencies. Runs entirely in the browser.

---

## 📁 Project Structure

```
MindGraph/
├── index.html      # App entry point
├── style.css       # Styles
├── script.js       # Core logic (graph engine + UI)
└── assets/
    └── demo.gif    # Demo screenshot (coming soon)
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

MIT License — feel free to use, modify, and distribute.

---

*Built by [Luisa Campanha](https://github.com/LuisaCampanhaH)*
