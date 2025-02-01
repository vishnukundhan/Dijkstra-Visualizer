# Dijkstra-Visualizer
# Dijkstra's Algorithm Visualization on 2D Grid

This project provides an interactive visualization of Dijkstra's shortest path algorithm on a 2D grid. The visualization helps users understand how the algorithm explores nodes and finds the optimal path between source and destination points while avoiding obstacles.

## Features

**Grid Interface**
- Interactive 2D grid where users can:
  - Place source point (green)
  - Place destination point (red)
  - Add wall blocks (black) to create obstacles
- Clear visualization of the path-finding process

**Algorithm Visualization**
- Real-time visualization of Dijkstra's algorithm exploration
- Color-coded elements:
  - Light blue: Unexplored cells
  - Dark blue: Visited cells
  - Green: Final shortest path
  - Black: Wall obstacles
  - Red: Destination point
  - Green: Source point

## How It Works

The visualization demonstrates Dijkstra's algorithm's core functionality:
1. Starts from the source node and explores neighboring cells
2. Gradually expands, updating distances to each reachable cell
3. Avoids wall obstacles during exploration
4. Highlights the shortest path in green once the destination is reached

## Implementation Details

**Core Components**
- 2D grid representation using matrix data structure
- Priority queue for efficient node exploration
- Distance tracking for each cell
- Parent pointer mapping for path reconstruction

**Visualization Features**
- Step-by-step animation of node exploration
- Clear indication of visited nodes
- Highlighted final path
- Interactive wall placement

## Usage

1. Launch the visualization
2. Place the source point (green) on the grid
3. Place the destination point (red)
4. Add walls (black) to create obstacles
5. Click "Visualize Dijkstra's Algorithm" to start the animation
6. Watch as the algorithm explores the grid and finds the shortest path

## Technical Requirements

- Any modern web browser
- JavaScript enabled
- HTML5 Canvas support

## Future Enhancements

- Additional pathfinding algorithms (A*, BFS, DFS)
- Adjustable animation speed
- Multiple path visualization
- Custom grid sizes
- Save/load grid configurations

## Contributing

Contributions are welcome! Please feel free to submit pull requests or create issues for bugs and feature requests.

Citations:
[1] https://pplx-res.cloudinary.com/image/upload/v1738412620/user_uploads/xYHtxVjRvTFZdXO/Screenshot-2025-02-01-175311.jpg
[2] https://pplx-res.cloudinary.com/image/upload/v1738412620/user_uploads/remFcDoCCKJQikQ/Screenshot-2025-02-01-175246.jpg
[3] https://pplx-res.cloudinary.com/image/upload/v1738412620/user_uploads/ZXLSlVePfancFBg/Screenshot-2025-02-01-175302.jpg
