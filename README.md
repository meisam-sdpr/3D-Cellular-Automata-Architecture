# 3D-Cellular-Automata-Architecture

Generative 3D form-finding using Cellular Automata and Python in Grasshopper.

## Conway's Game of Life in 3D!

In this project, I built a computational model to translate Conway's "Game of Life" algorithm into a 3D spatial context. The dynamic, complex topology seen in the **video** is the visual output of the algorithm's evolution through stacking consecutive generations. 💡

https://github.com/user-attachments/assets/8265f5be-d25b-484e-b660-da0930e7de7e

## The Workflow:

First, I wrote a script using the Python 3 (Py3) component in Grasshopper. This code applies the rules of the "Game of Life" to a grid, generating a complex pattern of solid blocks (active cells) and voids (dead cells) for each generation.

Here are the controllable parameters for this logic:
* **Inputs:** Number of rows, Number of columns, Gen0 active cells, and Number of floors.
* **Outputs:** 3D Generative Form

Ultimately, each generated layer is stacked vertically. 🏢
By changing the Gen0 active cells (initial state) and tweaking the grid dimensions, completely different and unique structural forms take shape.

## 🛠 Tools Used:
* **Rhinoceros 3D / Grasshopper**
* **Python 3 / Py3 Component** (for coding the cellular automata rules and grid generation)
