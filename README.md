# Locomotion Optimization with CEM and ARS on MuJoCo MJX

Optimization for Robot Motion Planning and Control — Assignment 4.

Gradient-free control of MuJoCo MJX systems using the **Cross Entropy Method (CEM)** and
**Augmented Random Search V2-t (ARS)**, applied to CartPole, Walker2D, and the 3D Humanoid.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/t6niskoppel/Optimization-for-Robot-Motion-Planning-and-Control-assignment4/blob/main/ars_cem_locomotion_final.ipynb)

All work lives in a single notebook —
[`ars_cem_locomotion_final.ipynb`](ars_cem_locomotion_final.ipynb) — with the optimizer
code, all six deliverables, figures, gait videos, and write-up inline. Needs a GPU runtime;
the first cell installs `mujoco`, `mujoco-mjx`, and `mediapy`.

## Layout

| Path | Contents |
|------|----------|
| [`ars_cem_locomotion_final.ipynb`](ars_cem_locomotion_final.ipynb) | The full project. |
| [`graphs/`](graphs/) | Figures — learning curves, CEM-vs-ARS, efficiency, sim2sim gap. |
| [`videos/`](videos/) | Rendered Walker2D and Humanoid gaits. |
| [`data/`](data/) | Saved policies / learning curves (`.npz`). |
