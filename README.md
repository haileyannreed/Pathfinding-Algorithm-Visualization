# Pathfinding Algorithm Visualization

## 📌 Project Overview
This project visualizes and analyzes five fundamental search algorithms:  
**Breadth-First Search (BFS), Depth-First Search (DFS), Uniform Cost Search (UCS), Greedy Best-First Search (GBFS), and A* Search.**  
The implementation focuses on their traversal paths using a graph representation of **Romania**, showcasing the strengths and weaknesses of each algorithm.

## 🎯 Objectives
- Implement and compare five search algorithms on a given graph.
- Develop a **visualization tool** to illustrate their traversal paths.
- Analyze the differences in performance based on traversal paths, efficiency, and cost.
- Utilize **Python graphical libraries** like `Matplotlib`, `NetworkX`, and `Pillow` to create clear and engaging visual representations.

## ✨ Features
✅ **Graph Representation**: The Romania road map is modeled as a weighted graph.  
✅ **Algorithmic Visualization**: Each search algorithm traverses the graph with an animated step-by-step visual output.  
✅ **Comparison Analysis**: Distance traveled, number of steps, and traversal paths are recorded for each algorithm.  
✅ **Interactive Jupyter Notebook**: Markdown cells explain the implementation, while Python code executes the visualizations.  

## 🛠️ Implementation
The project is structured into the following key steps:

### 1️⃣ Graph Construction
- The Romania map is represented as an adjacency list.
- A heuristic function is defined for informed searches.

### 2️⃣ Search Algorithms
- **BFS**: Explores neighbors layer by layer.
- **DFS**: Explores deeply before backtracking.
- **UCS**: Prioritizes paths with the lowest cost.
- **GBFS**: Selects the most promising node based on heuristics.
- **A\***: Balances path cost and heuristic estimates.

### 3️⃣ Visualization
- **Graph plotted over a Romania map image**.
- **Traversal paths are displayed dynamically** using `NetworkX` and `Matplotlib`.

### 4️⃣ Performance Comparison
| Algorithm | Uses Heuristics? | Guarantees Optimal Path? | Speed |
|-----------|----------------|------------------------|-------|
| BFS       | ❌ No          | ✅ Yes (Unweighted)   | ⚡ Fast |
| DFS       | ❌ No          | ❌ No                 | ⚡ Fast |
| UCS       | ❌ No          | ✅ Yes                | 🐢 Slow |
| GBFS      | ✅ Yes         | ❌ No                 | ⚡ Fast |
| A*        | ✅ Yes         | ✅ Yes                | 🔥 Optimized |

## 💻 Technologies Used
- **Python** (for algorithm implementation)
- **Matplotlib** (for graph visualization)
- **NetworkX** (for graph representation and pathfinding)
- **Pillow** (for image processing)
- **Jupyter Notebook** (for documentation and execution)

## 🚀 Running the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/haileyannreed/Pathfinding-Algorithm-Visualization.git
   cd Pathfinding-Algorithm-Visualization
