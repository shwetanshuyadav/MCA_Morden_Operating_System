# MCA Operating System Lab

This repository contains implementations of various Operating System concepts and algorithms as part of the MCA Operating System Lab course. The programs are written in Python and provided as Jupyter Notebooks for easy execution and visualization.

## List of Algorithms Implemented

### Introduction
- **exp_1.ipynb**: Retrieve and display basic Operating System information using Python's `platform` module.

### Process Management
- **exp_4.ipynb**: Monitor and display top processes based on CPU usage using `psutil`.

### File Systems
- **exp_2.ipynb**: Display disk partition information and usage statistics.
- **exp_5.ipynb**: Monitor and display network statistics in real-time.

### Page Replacement
- **exp_9.ipynb**: Implement FIFO and LRU Page Replacement algorithms.
- **exp_10.ipynb**: Implement Predictive LRU Page Replacement algorithm.
- **exp_14.ipynb**: Implement LRU Cache mechanism.

### Disk Scheduling
- **exp_13.ipynb**: Implement FCFS (First Come First Served) and SSTF (Shortest Seek Time First) Disk Scheduling algorithms.

### Deadlocks
- **exp_16.ipynb**: Implement Banker's Algorithm for deadlock avoidance.

## How to Compile and Run Programs

All programs are provided as Jupyter Notebook files (.ipynb). To run them:

1. Ensure you have Python installed (version 3.x recommended).
2. Install required libraries: `pip install psutil` (for system monitoring).
3. Open the notebook in Jupyter Notebook or JupyterLab.
4. Run the cells in order.

For notebooks involving real-time monitoring (e.g., exp_5.ipynb), the code may run in a loop; use Ctrl+C in the terminal to stop if running outside Jupyter.

## Folder Structure

- `Introduction/`: Basic OS information
- `Process_Management/`: Process-related operations
- `File_Systems/`: File and disk management
- `Page_Replacement/`: Memory page replacement algorithms
- `Disk_Scheduling/`: Disk scheduling algorithms
- `Deadlocks/`: Deadlock prevention and avoidance
- `Scheduling/`: CPU scheduling algorithms (to be added)
- `Memory_Management/`: Memory allocation algorithms (to be added)

## Requirements

- Python 3.x
- Jupyter Notebook
- psutil library: `pip install psutil`

## Contributing

Feel free to contribute by adding more OS algorithms or improving existing implementations.