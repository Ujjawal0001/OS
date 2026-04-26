# DeadlockX — Automated Deadlock Detection System v3.0

DeadlockX is a modern, web-based educational tool designed to simulate and detect deadlocks in operating systems. It features a stunning, premium glassmorphic user interface and interactive visualizations to help users understand complex deadlock detection algorithms.

## Features

- **Single-Instance Resource Allocation Graph (RAG) Mode:**
  - Interactive, draggable graph visualization of processes and resources.
  - Automatic cycle detection to identify deadlocks in single-instance resource systems.
  - Clear, step-by-step resolution strategies for detected deadlock cycles.

- **Multi-Instance Banker's Algorithm Mode:**
  - Dynamic resource allocation matrices (Allocated, Maximum Demand, Need, Available).
  - Safe state verification and safe sequence generation.
  - Step-by-step trace of the Banker's algorithm execution.

- **Modern Glassmorphic UI:**
  - Premium aesthetic featuring smooth gradients, dynamic backgrounds, and glass-like panels.
  - Micro-animations and hover effects for an engaging user experience.
  - Consistent and refined color palette for clear data representation.

- **Presets & Configurations:**
  - Pre-loaded scenarios (e.g., Safe, Deadlock, Complex, Banker's Classic, Unsafe) for quick testing.
  - Customizable number of processes and resources to build custom scenarios.

## Technologies Used

- **HTML5:** Semantic structure and layout.
- **CSS3:** Advanced styling, CSS variables, flexbox/grid layouts, animations, and glassmorphism effects.
- **Vanilla JavaScript:** Core logic for matrix manipulation, deadlock detection algorithms (DFS for cycles, Banker's safe state), and interactive HTML5 Canvas drawing.
- **Fonts:** 'Outfit', 'Orbitron', and 'Share Tech Mono' via Google Fonts.

## How to Run

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in any modern web browser (e.g., Chrome, Firefox, Edge, Safari).
3. No build tools or local servers are required—it runs completely on the client side!

## Usage Instructions

1. **Select Mode:** Choose between "Single-Instance (RAG)" and "Multi-Instance (Banker's Algorithm)" using the top toggle buttons.
2. **Configure System:** Use the "System Configuration" panel to set the number of processes and resources, or select a pre-defined preset.
3. **Adjust Matrices:** Modify the allocation and request/max matrices in the central panel.
4. **Run Detection:** Click the "Run Detection" button to execute the algorithm.
5. **View Results:** Read the analysis results and review the algorithm logs in the right panel. In RAG mode, observe the visually highlighted cycles on the interactive canvas.

## Author
Ujjawal
