To find the maximum range analytically, we treat the range $R(\theta)$ as a function of the angle $\theta$ and use calculus to find its maximum.

---

### **Step-by-Step Optimization**

#### **1. The Range Function**
The horizontal range $R$ of a projectile is given by the formula:
$$R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$$
* $v_0$ is the initial velocity (constant).
* $g$ is the acceleration due to gravity (constant).
* $\theta$ is the launch angle (variable).

#### **2. Applying the First Derivative Test**
To find the maximum of a function, we take its first derivative with respect to $\theta$ and set it to zero:
$$\frac{dR}{d\theta} = 0$$

Differentiating the function:
$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot \frac{d}{d\theta}[\sin(2\theta)]$$

Using the chain rule:
$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot 2\cos(2\theta)$$

#### **3. Solving for $\theta$**
Set the derivative to zero:
$$\frac{2v_0^2 \cos(2\theta)}{g} = 0$$

Since $v_0$ and $g$ are non-zero constants, we focus on the cosine term:
$$\cos(2\theta) = 0$$

The angle where cosine is zero (within the physical limits of a launch $0^\circ < \theta < 90^\circ$) is $90^\circ$:
$$2\theta = 90^\circ$$
$$\theta = \mathbf{45^\circ}$$

---

### **4. Verifying the Maximum (Logic Check)**
The range formula depends directly on the value of $\sin(2\theta)$. 
* The maximum possible value for any sine function is **1**.
* $\sin(2\theta) = 1$ when the argument is $90^\circ$.
* Therefore, $2\theta = 90^\circ \implies \theta = 45^\circ$.


---

### **Conclusion**
Analytically, the derivative $\frac{dR}{d\theta}$ equals zero at $\theta = 45^\circ$. Since the second derivative $\frac{d^2R}{d\theta^2} = -\frac{4v_0^2}{g}\sin(2\theta)$ is negative at this point, $\theta = 45^\circ$ represents the **maximum range**.

**Maximum Range Formula:**
$$R_{max} = \frac{v_0^2}{g}$$
