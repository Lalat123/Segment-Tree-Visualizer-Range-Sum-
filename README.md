# 🌳 Segment Tree Visualizer (Range Sum)

An interactive, responsive web-based tool designed to visualize the internal mechanics, construction, and operations of a **Segment Tree** built for Range Sum Queries. 

Aimed at competitive programmers and students, this tool bridges the gap between abstract data structures and visual intuition.

🔗 **[Launch Live Demo](https://segment-tree-visualizer-1--lalat-kesharike.replit.app/)**

---

## ✨ Key Features

* **Dynamic Tree Construction:** Input custom integer arrays (e.g., `1 3 5 7 9 11`) to watch the binary tree structure render dynamically.
* **SVG-Driven UI:** Clean, vector-based rendering of tree nodes, text labels, and parent-child edge connections that scales beautifully.
* **Interactive Range Sum Queries:** Highlight a range `[L, R]` to visualize exactly which segment nodes are combined to fetch the sum in $O(\log N)$ time.
* **Real-Time Point Updates:** Modify a value at any index and watch the data propagation travel upward from the leaf node to the root.
* **Algorithmic Insight:** Each node displays its corresponding array boundaries `[start, end]` alongside its current aggregated sum.

---

## 🛠️ Tech Stack

To ensure maximum performance, minimal overhead, and zero dependency issues, this project is built entirely using native web technologies:

* **Frontend Structure:** HTML5 (Semantic Layout)
* **Styling & Theme:** CSS3 (Flexbox/Grid layout, smooth transitions)
* **Core Engine:** Vanilla JavaScript (ES6+ Object-Oriented Logic)
* **Graphics Rendering:** Scalable Vector Graphics (SVG) for precise line-and-circle mathematical layouts

---

## 📐 Complexity Breakdown

The application demonstrates operations running at optimal theoretical algorithmic complexities:

| Operation | Time Complexity | Space Complexity | Description |
| :--- | :--- | :--- | :--- |
| **Build Tree** | $O(N)$ | $O(N)$ | Allocates linear memory up to $4 \times N$ nodes. |
| **Range Query** | $O(\log N)$ | $O(\log N)$ | Traverses only relevant overlapping segments. |
| **Point Update** | $O(\log N)$ | $O(1)$ | Mutates a leaf and updates its ancestors. |

---

## 🚀 Getting Started & Local Setup

Since this project has **zero external dependencies**, you can set it up locally in seconds without managing `npm` packages.

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/segment-tree-visualizer.git](https://github.com/your-username/segment-tree-visualizer.git)
cd segment-tree-visualizer
