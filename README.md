# dijkstra-pathfinding-visualizer
A Python + Pygame visualizer for Dijkstra’s shortest path algorithm with interactive grid, obstacles, and real-time pathfinding animation.
📌 Dijkstra Pathfinding Visualizer (Python + Pygame)

An interactive Pathfinding Algorithm Visualizer built using Python and Pygame that demonstrates Dijkstra’s Algorithm step-by-step on a grid. Users can place start/end points, create obstacles, and visualize the shortest path.

🚀 Features

Interactive grid-based environment

Place Start and End nodes

Add and remove Walls/Barriers

Visualize Dijkstra Algorithm execution

Highlights:

Open nodes

Closed nodes

Final shortest path

🛠 Technologies Used

Python

Pygame

PriorityQueue (Dijkstra Implementation)

📥 Installation Guide
✅ Step 1: Install Python

Download and install Python from:
https://www.python.org/downloads/

⚠ Recommended Version: Python 3.11 or 3.12
(Pygame may not work properly with Python 3.14)

✅ Step 2: Install Pygame

Open PowerShell / CMD and run:

pip install pygame


If the above does not work, try:

python -m pip install pygame


Or if using Python 3.12 specifically:

py -3.12 -m pip install pygame

▶ How to Run the Program
✅ Step 1: Clone the Repository
git clone https://github.com/your-username/dijkstra-pathfinding-visualizer.git

✅ Step 2: Open the Project Folder
cd dijkstra-pathfinding-visualizer

✅ Step 3: Run the Program
python dijkstra_visualizer.py


Or if Python version selection is needed:

py -3.12 dijkstra_visualizer.py

🎮 Controls / How to Use
🖱 Mouse Controls
Action	Function
Left Click (1st)	Set Start Node (Orange)
Left Click (2nd)	Set End Node (Purple)
Left Click (after that)	Place Walls/Barriers (Black)
Right Click	Remove Node / Reset Cell
⌨ Keyboard Controls
Key	Function
SPACE	Run Dijkstra Algorithm
C	Clear the Grid
🎨 Color Legend
Color	Meaning
Orange	Start Node
Purple	End Node
Black	Wall/Barrier
Green	Open Nodes (In Queue)
Red	Closed Nodes (Visited)
Blue	Final Shortest Path
📌 Algorithm Used

This project uses Dijkstra’s Algorithm, which guarantees the shortest path in a weighted/unweighted graph.
In this grid-based system, each move has equal weight (cost = 1).


Add speed control slider

Add weighted nodes
