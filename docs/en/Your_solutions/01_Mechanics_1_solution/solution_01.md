This problem involves **Projectile Motion**. We will break the initial velocity into components and use calculus (integration) to derive the motion equations.


### **1. Initial Values and Components**
* Initial Velocity ($v_0$): **100 m/s**
* Launch Angle ($\theta$): **37°**
* Gravity ($g$): $\approx 9.8 \text{ m/s}^2$ (or $10 \text{ m/s}^2$ for simpler calculation). Let's use **9.8 m/s²**.

**Velocity Components:**
* Horizontal: $v_{0x} = v_0 \cos(37^\circ) = 100 \cdot 0.8 = \mathbf{80 \text{ m/s}}$
* Vertical: $v_{0y} = v_0 \sin(37^\circ) = 100 \cdot 0.6 = \mathbf{60 \text{ m/s}}$

---

### **2. Deriving Differential Equations of Motion**

We start from acceleration ($a$) and integrate with respect to time ($t$).

#### **Horizontal Direction ($x$):**
There is no air resistance, so acceleration is zero.
1.  **Acceleration:** $a_x = \frac{d^2x}{dt^2} = 0$
2.  **Velocity:** Integrate $a_x$: $v_x(t) = \int 0 \, dt = v_{0x} = \mathbf{80}$
3.  **Position:** Integrate $v_x$: $x(t) = \int 80 \, dt = \mathbf{80t}$

#### **Vertical Direction ($y$):**
Gravity acts downwards.
1.  **Acceleration:** $a_y = \frac{d^2y}{dt^2} = -g = \mathbf{-9.8}$
2.  **Velocity:** Integrate $a_y$: $v_y(t) = \int -g \, dt = v_{0y} - gt = \mathbf{60 - 9.8t}$
3.  **Position:** Integrate $v_y$: $y(t) = \int (60 - 9.8t) \, dt = \mathbf{60t - 4.9t^2}$

---

### **3. Determine the Time of Flight ($T$ )**
The projectile hits the ground when $y(t) = 0$.
$$60t - 4.9t^2 = 0$$
$$t(60 - 4.9t) = 0$$
Since $t = 0$ is the start, we solve for the other root:
$$4.9t = 60 \implies t = \frac{60}{4.9} \approx \mathbf{12.24 \text{ s}}$$

---

### **4. Determine the Maximum Height ($H$)**
The maximum height occurs when the vertical velocity is zero ($v_y = 0$).
$$60 - 9.8t = 0 \implies t_{peak} = \frac{60}{9.8} \approx \mathbf{6.12 \text{ s}}$$
Now, plug $t_{peak}$ into the $y(t)$ equation:
$$y(6.12) = 60(6.12) - 4.9(6.12)^2$$
$$H \approx 367.2 - 183.6 \approx \mathbf{183.6 \text{ m}}$$

---

### **5. Determine the Range ($R$)**
The range is the horizontal distance traveled during the total time of flight ($T \approx 12.24 \text{ s}$).
$$R = x(12.24) = 80 \cdot 12.24$$
$$R \approx \mathbf{979.2 \text{ m}}$$

---

### **Final Results Summary**
| Parameter | Equation / Value |
| :--- | :--- |
| **Equations of Motion** | $x(t) = 80t$ and $y(t) = 60t - 4.9t^2$ |
| **Time of Flight** | $\approx 12.24 \text{ s}$ |
| **Maximum Height** | $\approx 183.6 \text{ m}$ |
| **Range** | $\approx 979.2 \text{ m}$ |
