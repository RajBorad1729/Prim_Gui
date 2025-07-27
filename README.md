# Prim's Algorithm MST Visualizer (Java Swing)

## Overview

This project is a **Java Swing GUI application** that visually demonstrates Prim's Algorithm for finding the Minimum Spanning Tree (MST) of a grid-based graph. Users can interactively select nodes on a grid, and the application will compute and display the MST, including edge weights and the total weight.

## Features

- **Interactive Grid:** Select nodes to include in the graph.
- **Visual MST Display:** See the MST drawn with colored nodes and edges.
- **Edge Weights:** All edge weights are calculated based on node positions.
- **Adjacency Matrix:** View the adjacency matrix in the console.
- **Modern Java Swing UI:** Clean, resizable interface.

## Technologies Used

- **Java 8+**
- **Java Swing** for GUI
- **Object-Oriented Design:** Custom classes for Node, AdjacencyMatrix, Prim's Algorithm, and visualization.

## How to Run

1. **Clone or Download the Repository**

2. **Compile the Source Code**

   Open a terminal and navigate to the `src` directory:
   ```sh
   cd e:\Project\MST_Prim_GUI\src
   javac com/mst/prim/*.java
   ```

3. **Run the Application**

   ```sh
   java com.mst.prim.Main
   ```

4. **Usage**

   - A window will open with a grid of buttons.
   - Click on grid buttons to select nodes.
   - Click **"Show Minimum Spanning Tree"** to compute and visualize the MST.
   - The MST will be displayed in a new window, and the adjacency matrix will be printed in the console.

## File Structure

```
src/
  com/
    mst/
      prim/
        Main.java                # Entry point
        MainWindow.java          # Main GUI window
        MinimumSpanningTree.java # MST visualization component
        Node.java                # Node representation
        AdjacencyMatrix.java     # Matrix for edge weights
        PrimsAlgorithm.java      # Prim's algorithm logic
        Calculate.java           # Utility for distance calculation
```

## Screenshots

<img width="1136" height="641" alt="{443F17F5-BC21-4FC6-BA65-78C811E2BFD1}" src="https://github.com/user-attachments/assets/dc978403-235f-449d-947c-a654fa62c7bb" />

<img width="1134" height="621" alt="{75D4F26B-A403-4FC7-975A-34D7B882A428}" src="https://github.com/user-attachments/assets/da2be038-166b-48f0-8ca1-67c7fcf6f53d" />





---

**Enjoy visualizing Prim's Algorithm!**
