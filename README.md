# Os-project

# Efficient Page Replacement Algorithm Simulator

## Overview
The **Efficient Page Replacement Algorithm Simulator** is a software tool designed to simulate and analyze various page replacement algorithms used in operating systems. This project helps in understanding how different algorithms manage page faults and optimize memory usage.

## Features
- Simulation of multiple page replacement algorithms:
  - FIFO (First-In-First-Out)
  - LRU (Least Recently Used)
  - Optimal Page Replacement
  - LFU (Least Frequently Used)
- User-defined input for:
  - Number of frames
  - Reference string
- Real-time performance metrics:
  - Number of page faults
  - Page hit ratio
  - Execution time analysis
- Graphical and textual representation of results
- Step-by-step execution mode for better visualization
- Option to save simulation results as a text file or CSV
- Support for variable frame sizes for comparative analysis
- Ability to analyze performance under different workloads
- Logging feature to track multiple simulation runs

## Requirements
- Programming Language: C++ / Python
- Libraries (if applicable):
  - `matplotlib` (for Python visualization)
  - `curses` (for terminal-based UI)
- Compatible with Windows, Linux, and macOS

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/page-replacement-simulator.git
   ```
2. Navigate to the project directory:
   ```sh
   cd page-replacement-simulator
   ```
3. Compile and run (for C++):
   ```sh
   g++ simulator.cpp -o simulator
   ./simulator
   ```
   OR
   Run the Python version:
   ```sh
   python simulator.py
   ```

## Usage
1. Enter the number of frames available in memory.
2. Provide the reference string for page requests.
3. Choose the algorithm to simulate.
4. View the results including the number of page faults and efficiency metrics.

## Example
```
Enter number of frames: 3
Enter reference string: 7 0 1 2 0 3 4 2 3 0 3 2
Choose Algorithm:
1. FIFO
2. LRU
3. Optimal
4. LFU
Enter choice: 2

Results:
Total Page Faults: 6
Page Hit Ratio: 50%
```

## Future Enhancements
- GUI-based simulator
- Support for additional page replacement algorithms
- Integration with real-time process memory management simulation
