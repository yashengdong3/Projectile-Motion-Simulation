# Physics Motion Simulation & Numerical Computing

A Python-based simulation and numerical computing tool designed to model, solve, and visualize classical physics kinematics and mathematical algorithms.

---

## 📌 Overview

This repository focuses on scientific computing, physics modeling, and algorithm implementation using Python. It simulates real-world physical behaviors, provides numerical approximations for calculus, and delivers clean, academic-grade visualizations to analyze complex dynamic systems.

---

## ✨ Features

* **Projectile Motion Simulation**
  * Compare trajectories across different launch angles ($15^\circ$, $30^\circ$, $45^\circ$, $60^\circ$, $75^\circ$).
  * Automatic marking of precise launch and landing points.
  * *Governing Equation:* $$y = x\tan(\theta) - \frac{g x^2}/{2 v^2 \cos^2(\theta)}$$

* **Kinematics Analysis on Orbits (Orbital Mechanics)**
  * Simulate particle physics on an elliptical orbit (e.g., Earth-Sun gravitational system).
  * Real-time vector visualization of Velocity ($\mathbf{v}$) and Acceleration ($\mathbf{a}$) using calculus derivations.
  * *Parametric Equations:* $$x = cos(\omega t), \quad y = sin(\omega t)$$

* **Numerical Analysis & Algorithms**
  * **Numerical Integration:** Implemented Riemann Sum (incorporating both **Midpoint Rule** and **Trapezoidal Rule**) to approximate definite integrals for non-linear functions ($f(x) = x\sin^2(x)$).
  * **Recursive Algorithms:** Developed a recursive tree structure for **Fibonacci Sequence** generation and optimized its base-case boundary conditions through rigorous debugging.

* **Scientific Visualization**
  * High-quality, publication-ready plots (300+ DPI) generated using Matplotlib with precise grids, legends, and vector annotations.

---

## 🛠️ Skills & Tech Stack

* **Language:** Python
* **Libraries:** NumPy, Matplotlib
* **Core Concepts:** Physics Modeling, Kinematics, Numerical Simulation, Calculus Approximations, Vector Derivations, Algorithm Debugging

---

## 🖼️ Preview

## Projectile Motion

Comparison of projectile trajectories at different launch angles.

![Projectile Motion](projectile_motion.png)

---

## Kinematics Ellipse

Visualization of kinematics ellipse generated using parametric equations.

![Kinematics Ellipse](kinematics_ellipse.png)
