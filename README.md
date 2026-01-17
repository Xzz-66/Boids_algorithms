# Boids_algorithms
Codes and documents for the boids algorithms with GenAI

This project implements a 2D **Boids** flocking simulation in Python (NumPy), including:
- the three classic flocking rules (**separation, alignment, cohesion**),
- two boundary modes (**wrap-around** and **reflect**),
- **matplotlib animation** (working in Jupyter via HTML / `to_jshtml()`),
- basic **correctness checks**,
- **Tier 1** spatial optimization using **SciPy KDTree / cKDTree** for neighbor search + benchmarking,
- **Tier 2** predator agent + boid predator-avoidance rule.

The main work is contained in the notebook:

- `Boids_simulation.ipynb`

---

## Requirements

Tested with Python 3 (Jupyter notebook). Main libraries used:
- `numpy`
- `matplotlib`
- `scipy` (for `scipy.spatial.KDTree` / `cKDTree`)
- `IPython` (for `HTML(...)` in notebooks)
