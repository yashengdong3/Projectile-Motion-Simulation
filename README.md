# Physics Motion Simulation & Numerical Computing

This repository contains several Python projects developed while learning scientific computing and introductory physics. The projects focus on numerical methods, physics simulation, and data visualization using Python.

---

## Overview

The purpose of this repository is to practice applying Python to solve engineering and physics problems. The projects include projectile motion simulation, orbital motion visualization, numerical integration, and recursive algorithms.

---

## Projects

### Projectile Motion Simulation

- Simulate projectile trajectories under different launch angles (15°, 30°, 45°, 60°, 75°).
- Compare the influence of launch angle on the trajectory and landing distance.
- Visualize launch and landing points using Matplotlib.

Governing equation:

$$
y=x\tan(\theta)-\frac{gx^2}{2v^2\cos^2(\theta)}
$$

---

### Kinematics of Elliptical Motion

- Simulate motion along an elliptical trajectory.
- Visualize velocity and acceleration vectors.
- Practice parametric equations and vector representation.

Parametric equations:

$$
x=\cos(\omega t),\qquad
y=\sin(\omega t)
$$

---

### Numerical Integration

- Approximate definite integrals using numerical methods.
- Implement the Midpoint Rule and Trapezoidal Rule.
- Compare numerical results with analytical solutions.

Example function:

$$
f(x)=x\sin^2(x)
$$

---

### Recursive Algorithm Practice

- Implement the Fibonacci sequence using recursion.
- Understand recursive function design and stopping conditions.

---

## Skills

- Python
- NumPy
- Matplotlib
- Numerical Computing
- Physics Simulation
- Scientific Visualization

---

## Preview

### Projectile Motion

Comparison of projectile trajectories under different launch angles.

![Projectile Motion](projectile_motion.png)

---

### Kinematics of Elliptical Motion

Visualization of particle motion on an elliptical trajectory.

![Kinematics Ellipse](kinematics_ellipse.png)

---

## Future Improvements

- Add user-adjustable simulation parameters.
- Improve visualization with animations.
- Organize the projects into independent Python modules.
