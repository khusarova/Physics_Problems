### Problem Analysis

We are given a function representing the amount of electric charge flowing through a wire over time, and we need to calculate the electric current at a specific moment.

**Given:**

* Charge function: $Q(t) = 5t^2 + 5$
* Target time: **$t = 3$ s**

---

### The Physics Principle

To solve this, you need to understand the relationship between electric charge and electric current. Electric current ($I$) is defined as the rate at which electric charge ($Q$) flows through a surface over time ($t$).

Mathematically, instantaneous current is the first derivative of the charge function with respect to time:


$$I(t) = \frac{dQ(t)}{dt}$$

---

### Step-by-Step Solution

**1. Find the derivative of the charge function**
To find the formula for current at any given time $t$, we must differentiate the given charge function $Q(t)$ with respect to $t$.

* We start with: $Q(t) = 5t^2 + 5$
* Applying the power rule of differentiation, the derivative of $5t^2$ becomes $10t$.
* The derivative of a constant number ($5$) is $0$.
* This gives us our current function: $I(t) = 10t$

**2. Substitute the given time into the current function**
The problem asks for the current specifically at **3 seconds**. We plug this value into the $I(t)$ function we just found.

* $I(3) = 10 \cdot 3$
* $I(3) = 30$

---

### Final Answer

Assuming standard SI units where charge is measured in Coulombs and time in seconds, the current at 3 seconds is **30 A** (Amperes).
