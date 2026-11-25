# AI Pathfinding Simulator

Interactive grid maze that compares five search algorithms: BFS, DFS, UCS, Greedy best-first and A*.

- Pick a scenario and an algorithm, then press Next step or Play.
- Edit the maze: walls, start, goal, and cell costs (5 or 9).
- Compare all runs the five algorithms and shows expanded nodes, moves and path cost.

Rules: moves are up/down/left/right. Normal cells cost 1, purple cells cost 5 or 9. BFS and DFS ignore weights when choosing the next cell. Greedy uses h only, A* uses g+h (Manhattan distance).

Open `index.html` in any browser, or use the GitHub Pages link.
