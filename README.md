# GraphConnect

![GitHub stars](https://img.shields.io/github/stars/skp8500/Graphconnect?style=for-the-badge)
![GitHub license](https://img.shields.io/github/license/skp8500/Graphconnect?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/skp8500/Graphconnect?style=for-the-badge)

GraphConnect is an interactive shortest-path visualizer built with vanilla JavaScript, HTML, and CSS. It lets you build custom graphs, switch between Dijkstra and BFS, and watch the path update in real time as you drag nodes, edit edges, and explore different graph layouts.

## Preview

![GraphConnect Preview](assets/graphconnect-preview.svg)

## Features

- Interactive graph canvas with draggable nodes
- Add, connect, disconnect, and delete nodes and edges
- Real-time shortest-path calculation between `S` and `E`
- Supports both Dijkstra for weighted paths and BFS for unweighted traversal
- Edge weight editor with automatic distance-based weights or manual overrides
- Step-by-step algorithm visualization panel
- Path animation for clearer traversal playback
- Zoom, pan, and optional grid snapping for easier graph editing
- Keyboard shortcuts for faster interaction
- Fully client-side and dependency-free

## Installation

1. Clone the repository:

```bash
git clone https://github.com/skp8500/Graphconnect.git
```

2. Move into the project folder:

```bash
cd Graphconnect
```

3. Open `index.html` in your browser.

If you prefer a local server, you can also run the project with any static server extension or tool.

## Usage

1. Open the app in your browser.
2. Use `Drag` mode to move nodes and inspect the live shortest path.
3. Switch to `Node` mode to place new nodes on the canvas.
4. Switch to `Edge` mode and click two nodes to create or remove a connection.
5. Click an edge label to set a manual weight or restore automatic distance-based weighting.
6. Toggle between `Dijkstra` and `BFS` to compare algorithm behavior.
7. Use `Animate` to replay the selected path or `Steps` to inspect the algorithm state step by step.

## Configuration

This project does not require environment variables, API keys, or secrets.

You can customize the experience directly in the source files:

- `app.js` for graph logic, algorithms, interaction behavior, and shortcuts
- `style.css` for theme, spacing, layout, and visual styling
- `index.html` for structure, controls, and page metadata

### Keyboard Shortcuts

| Key | Action |
| --- | --- |
| `1` | Drag mode |
| `2` | Add node mode |
| `3` | Add edge mode |
| `4` | Delete mode |
| `d` | Dijkstra |
| `b` | BFS |
| `g` | Toggle grid |
| `a` | Animate path |
| `s` | Toggle step mode |
| `r` | Reset graph |
| `←` / `→` | Navigate algorithm steps |

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- SVG for edge rendering and graph visualization

## Project Structure

```text
Graphconnect/
├── assets/
│   └── graphconnect-preview.svg
├── app.js
├── index.html
├── LICENSE
├── README.md
└── style.css
```

## Contributing

Pull requests are welcome. If you want to propose a major enhancement, open an issue first so the discussion can happen before implementation starts.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


