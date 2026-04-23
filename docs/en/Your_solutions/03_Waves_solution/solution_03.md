This problem demonstrates how two waves traveling in opposite directions combine to form a **standing wave**.

### 1. Apply the Principle of Superposition
The resulting wave $y(x, t)$ is the sum of the two individual waves:
$$y(x, t) = y_1(x, t) + y_2(x, t)$$
$$y(x, t) = A \sin(kx - \omega t) + A \sin(kx + \omega t)$$

To simplify this, we use the trigonometric identity for the sum of sines:
$$\sin(\alpha) + \sin(\beta) = 2 \sin\left(\frac{\alpha + \beta}{2}\right) \cos\left(\frac{\alpha - \beta}{2}\right)$$

Let $\alpha = kx + \omega t$ and $\beta = kx - \omega t$:
* $\frac{\alpha + \beta}{2} = \frac{2kx}{2} = kx$
* $\frac{\alpha - \beta}{2} = \frac{2\omega t}{2} = \omega t$

**The Resulting Standing Wave Equation:**
$$y(x, t) = [2A \sin(kx)] \cos(\omega t)$$


---

### 2. Characteristics of the Standing Wave
* **Amplitude:** The term $(2A \sin(kx))$ represents the position-dependent amplitude.
* **Oscillation:** The term $\cos(\omega t)$ means every point on the wave oscillates in simple harmonic motion at the same frequency.

---

### 3. Identify the Positions of the Nodes
**Nodes** are points where the displacement is always zero. This occurs when the spatial part of the equation is zero:
$$\sin(kx) = 0$$

The sine function is zero when its argument is an integer multiple of $\pi$:
$$kx = n\pi, \quad \text{where } n = 0, \pm 1, \pm 2, \dots$$

Since $k = \frac{2\pi}{\lambda}$, we substitute that in:
$$\left(\frac{2\pi}{\lambda}\right)x = n\pi$$
$$x = n \frac{\lambda}{2}$$

**Positions of the Nodes:**
Nodes occur at $x = 0, \frac{\lambda}{2}, \lambda, \frac{3\lambda}{2}, \dots$ (every half-wavelength).

---

### Summary Table

| Feature | Equation / Value |
| :--- | :--- |
| **Standing Wave Equation** | $y(x, t) = 2A \sin(kx) \cos(\omega t)$ |
| **Node Condition** | $\sin(kx) = 0$ |
| **Node Positions ($x$)** | $n \frac{\lambda}{2}$ |
| **Antinode Positions ($x$)** | $(n + \frac{1}{2}) \frac{\lambda}{2}$ |
