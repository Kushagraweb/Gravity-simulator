# Gravity Simulator

This is an interactive 2D gravity simulator built with Python and Pygame. The simulation showcases gravitational forces between particles, with options for real-time interaction and visualization.

---

## Features

1. **Gravity Simulation**:
   - Simulates gravitational attraction between particles based on their mass and distance.
   - Particles influence each other dynamically in real-time.

2. **Collision Detection**:
   - Particles merge when they collide, conserving mass and radius.

3. **Interactive Controls**:
   - Right-click to add particles with velocity set by mouse direction.
   - Middle-click to remove particles by selecting them.
   - Adjustable particle properties like position, mass, radius, and velocity through the sidebar.

4. **Vector Field Visualization**:
   - Displays a vector field representing gravitational forces at grid points.
   - Color-coded arrows indicate the particle exerting the strongest force at each point.

5. **Pause/Resume**:
   - Pause and resume the simulation with the spacebar.

6. **Particle Trails**:
   - Visualize particle movement with trailing effects.

7. **Screen Wrapping**:
   - Particles wrap around the screen edges, maintaining simulation continuity.

---

## Installation

### Prerequisites
- Python 3.x
- Pygame library

### Steps
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd gravity-simulator
   ```

3. Install the required dependencies:
   ```bash
   pip install pygame
   ```

4. Run the simulation:
   ```bash
   python main.py
   ```

---

## Controls

### General Controls
- **Arrow Keys**: Select input fields in the sidebar.
- **Enter**: Confirm changes to the selected input.
- **Backspace**: Clear the current input field.
- **Spacebar**: Pause/Resume the simulation.
- **Mouse Scroll**: Adjust particle radius.

### Mouse Actions
- **Left Click**: Drag particles or interact with sliders.
- **Right Click**: Add a new particle at the cursor's position.
- **Middle Click**: Remove particles by clicking on them.

---

## Sidebar Options

1. **Adjust Particle Properties**:
   - Modify position (X, Y), mass, radius, and initial velocity.

2. **Gravitational Constant (G)**:
   - Use the slider to adjust the gravitational strength.

3. **Vector Field Density**:
   - Modify the spacing of the vector field grid.

4. **Vector Field Toggle**:
   - Checkbox to enable or disable the vector field visualization.

---

## Future Improvements

- **Performance Optimization**:
  - Implement spatial partitioning (e.g., quadtrees) for faster collision detection and force calculations.

- **Enhanced Visuals**:
  - Add smooth animations for particle merging.
  - Provide more customization options for particle trails and colors.

- **Advanced Features**:
  - Add preset systems (e.g., solar system, galaxies).
  - Allow users to reset the simulation.

---

## License
This project is licensed under the MIT License. See `LICENSE` for details.

---

## Acknowledgments
- Built using [Pygame](https://www.pygame.org/).
- Inspired by physics simulations and gravitational systems.

