
## Molar Heat Capacity ($C$)

**Definition:** Heat energy required to increase the **temperature of 1 mole of a substance by $1^{\circ}\text{C}$ or $1\text{K}$**.

### 1. Molar Heat Capacity at Constant Pressure ($\text{C}_P$)

$$\delta Q = n \text{C}_P \Delta T$$

The whole heat will go into the change in internal energy and work done: $\delta Q = \Delta U + P \Delta V$.

$$n \text{C}_P \Delta T = \Delta U + P \Delta V$$

### 2. Molar Heat Capacity at Constant Volume ($\text{C}_V$)

$$\Delta Q = n \text{C}_V \Delta T$$

At constant volume, $\Delta V=0$, so the work done is $W = P \Delta V = 0$.

The whole heat supplies the change in internal energy: $\delta Q = \Delta U$.

$$n \text{C}_V \Delta T = \Delta U$$

### Relation between $\text{C}_P$ and $\text{C}_V$ 

From the First Law of Thermodynamics:

$$\Delta Q = \Delta U + \Delta W$$

For a constant pressure process:

$$\Delta Q = \Delta U + P \Delta V$$

Substitute expressions for $\Delta Q$ and $\Delta U$:
#Derivation 
$$\begin{split} n \text{C}_P \Delta T &= n \text{C}_V \Delta T + P \Delta V \quad (\text{Since } \Delta U = n \text{C}_V \Delta T \text{ is true for ideal gases}) \\ \end{split}$$

From the Ideal Gas Law: $\quad P V = n R T$

For a constant pressure change, $\quad P \Delta V = n R \Delta T$

Substitute $P \Delta V$:

$$n \text{C}_P \Delta T = n \text{C}_V \Delta T + n R \Delta T$$

Dividing by $n \Delta T$ gives Mayer's Formula:

$$\text{C}_P - \text{C}_V = R$$

---


        

---

##  Heat Capacity Ratio ($\gamma$)

Definition: The ratio of $\text{C}_P$ to $\text{C}_V$.

$$\gamma = \frac{\text{C}_P}{\text{C}_V}$$

### Relation between $\gamma$ and Degrees of Freedom ($f$)

Degrees of Freedom ($f$) is the number of independent ways a molecule can store energy (translational, rotational, vibrational).

The relation between the heat capacities and $f$ is:

$$\text{C}_V = \frac{f R}{2} \quad \text{and} \quad \text{C}_P = \text{C}_V + R = \frac{f R}{2} + R = R \left( \frac{f}{2} + 1 \right) = R \left( \frac{f+2}{2} \right)$$

Therefore, the ratio $\gamma$ is:

$$\gamma = \frac{\text{C}_P}{\text{C}_V} = \frac{\frac{f R}{2} + R}{\frac{f R}{2}} = \frac{R \left( \frac{f+2}{2} \right)}{\frac{f R}{2}}$$

$$\gamma = \frac{f+2}{f} = 1 + \frac{2}{f}$$

### Specific Values (Based on the notes)

1. **Monoatomic Molecule**
    
    - Degrees of Freedom: $f=3$ (3 translational)
        
    - $\text{C}_V = \frac{3 R}{2}$
        
    - $\text{C}_P = \frac{3 R}{2} + R = \frac{5 R}{2}$
        
    - $\gamma = \frac{\text{C}_P}{\text{C}_V} = \frac{5 R / 2}{3 R / 2} = \frac{5}{3} \approx **1.67**$
        
    - The notes also list $\gamma_{\text{diatomic}} = **1.4**$ and $\gamma_{\text{triatomic}} = **1.33**$.
        

### Example Calculation (Based on the notes)

Problem: 2 moles of a diatomic gas at $300\text{K}$ are enclosed in a cylinder. Assume the temperature is increased by $\Delta T = 100\text{K}$.

(A diatomic gas has $\text{C}_V = \frac{5 R}{2}$ and $\text{C}_P = \frac{7 R}{2}$, corresponding to $f=5$ at moderate temperatures.)

1. Piston free to move (Isobaric Process, $\Delta P = 0$)

Heat absorbed $\Delta Q = n \text{C}_P \Delta T$

$$\Delta Q = 2 \times \frac{7 R}{2} \times 100 = **700 R**$$

2. Piston fixed (Isochoric Process, $\Delta V = 0$)

Heat absorbed $\Delta Q = n \text{C}_V \Delta T$

$$\Delta Q = 2 \times \frac{5 R}{2} \times 100 = **500 R**$$
