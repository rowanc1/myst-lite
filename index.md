---
title: Interactive figures using JupyterLite
---

In 1963, [Edward Lorenz](wiki:Edward_Norton_Lorenz), with the help of [](wiki:Ellen_Fetter) who was responsible for the numerical simulations and figures, and [Margaret Hamilton](<wiki:Margaret_Hamilton_(software_engineer)>) who helped in the initial, numerical computations leading up to the findings of the Lorenz model, developed a simplified mathematical model for [](wiki:atmospheric_convection). The model is a system of three ordinary differential equations now known as the Lorenz equations:

\begin{align}
\label{eq:lorenz}
\frac{\mathrm{d}x}{\mathrm{d}t} &= \sigma (y - x), \\[6pt]
\frac{\mathrm{d}y}{\mathrm{d}t} &= x (\rho - z) - y, \\[6pt]
\frac{\mathrm{d}z}{\mathrm{d}t} &= x y - \beta z.
\end{align}

The Lorenz equations can arise in simplified models for lasers, dynamos, thermosyphons, brushless DC motors, electric circuits, chemical reactions and forward osmosis. A visualization of [](#eq:lorenz) can be seen using `ipywidgets` running in `JupyterLite`.

:::{figure} #lorenz
The Lorenz Attractor using `ipywidgets`.
:::
