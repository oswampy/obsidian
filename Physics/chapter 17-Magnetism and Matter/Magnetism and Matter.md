## Properties of Magnetic Field Lines

- **These are imaginary lines,** the **tangent to which gives the direction of magnetic field at that point.**
    
- **Magnetic field lines always form closed loops.** They do not have any starting or end point.
    
- **No two magnetic field lines can intersect each other.** Because at the point of intersection, there will be two directions of magnetic field, which is not possible.
    
- **Larger the number of field lines crossing per unit area, the stronger is the magnitude of magnetic field $B$.**
    
- **Inside the bar magnet, the field lines are from south to north, and outside the bar magnet, the field lines are shown north to south.**

## Bar magnet as an Equivalent Solenoid

When a current is passed through a solenoid, it behaves like a bar magnet.

Some observations of similar behavior are as follows:

1. **A current carrying solenoid suspended freely always comes to rest in north-south direction.**
    
2. **Two current-carrying solenoids exhibit mutual attraction and repulsion when brought close to one another.**

Here is the transcribed and structured content from the image, incorporating the appropriate Markdown and LaTeX formatting for the formulas and units:

## Magnetic Moment ($M$)

It is defined as the product of **pole strength** with the **separation between them**.
- **SI unit** is $\text{A}\cdot\text{m}^2$.
### Pole Strength

- It represents the **strength of a magnetic pole**, which can be written as $m$ or $q_m$.
- **SI unit of pole strength** is $\text{A}\cdot\text{m}$.

$$\vec{M} = q_m \cdot 2\vec{l}$$

-Where:
- $\vec{M}$ = Magnetic moment
- $q_m$ = Pole strength
- $2\vec{l}$ = Separation distance between the poles
### Analogies and Related Formulas

- **Electric Dipole Analogy:** Comparing a magnetic dipole to an electric dipole where charges $-q$ and $+q$ are separated by a distance $2l$:
    $$p = q \cdot 2l$$
- **For a Current-Carrying Loop:**
    The magnetic moment can also be expressed for a current loop as: 
    $$M = I \cdot A$$
    Where $I$ is the current and $A$ is the area of the loop.
## Cutting of Magnet

Let the original bar magnet have a pole strength $m$ and an effective length $2l$.

Its initial magnetic moment is given by:

$$M = m \cdot 2l$$

### a) Cutting along the length of magnet

When a bar magnet is cut longitudinally (lengthwise) into two equal halves along its principal axis:

- **Pole Strength:** The cross-sectional area of each pole is halved, so the pole strength of each piece becomes half of the original:
    
    $$m' = \frac{m}{2}$$
    
- **Length:** The length of each piece remains unchanged:
    
    $$(2l)' = 2l$$
    

**New Magnetic Moment ($M'$):**

$$M' = \frac{m}{2} \times 2l$$

$$M' = m \cdot l = \frac{M}{2}$$

### b) Cutting perpendicular to the length of magnet

When a bar magnet is cut transversely (transverse slice) into two equal halves perpendicular to its length:

- **Pole Strength:** The cross-sectional area of the poles remains the same, so the pole strength is unchanged:
    
    $$m' = m$$
    
- **Length:** The length of each piece becomes half of the original length:
    
    $$(2l)' = l$$
    

**New Magnetic Moment ($M'$):**

$$M' = m \cdot l = \frac{M}{2}$$

## Coulomb's Law in Magnetism

Coulomb stated that the force between two magnetic poles is directly proportional to the product of their pole strengths and inversely proportional to the square of the distance between them.

This force could be **repulsive or attractive** in nature (like poles repel, unlike poles attract).

### Mathematical Derivation

Let $m_1$ and $m_2$ be the pole strengths of two magnetic poles separated by a distance $r$.

- **Proportionality to pole strengths:**
    $$F \propto m_1 m_2$$
    
- **Inverse-square dependency on distance:**
$$F \propto \frac{1}{r^2}$$
Combining both relationships:

$$F \propto \frac{m_1 m_2}{r^2}$$

### Vector Formula

By introducing a constant of proportionality, the equation becomes:

$$F = \frac{\mu_0}{4\pi} \frac{m_1 m_2}{r^2}$$

- Where:
	- $F$ = Magnetic force between the poles
	    
	- $m_1, m_2$ = Pole strengths
	    
	- $r$ = Distance between the two poles
	    
	- $\frac{\mu_0}{4\pi}$ = Proportionality constant (where $\mu_0$ is the permeability of free space, equal to $4\pi \times 10^{-7} \text{ T}\cdot\text{m/A}$)


## Magnetic Field Intensity / Magnetic Induction ($\vec{B}$)

It describes the actual strength and direction of the magnetic field at any given point in space and determines the force exerted on moving charges or magnetic poles.

### 1. Definition via Magnetic Force (Lorentz Force)

The fundamental way to define $\vec{B}$ is by looking at the magnetic force ($\vec{F}$) it exerts on a charge $q$ moving with a velocity $\vec{v}$:

$$\vec{F} = q(\vec{v} \times \vec{B})$$

In terms of magnitude:

$$F = qvB\sin\theta$$

Where $\theta$ is the angle between the velocity vector $\vec{v}$ and the magnetic field vector $\vec{B}$. If we rearrange this to isolate $B$:

$$B = \frac{F}{qv\sin\theta}$$

> **Physical Definition:** Magnetic field intensity $B$ at a point is numerically equal to the force experienced by a unit charge moving with unit velocity perpendicular to the direction of the magnetic field.

### 2. Definition via Pole Strength (Coulomb's Law Analogy)


The magnetic field intensity $\vec{B}$ at a point is the magnetic force experienced per unit pole strength placed at that point:

$$\vec{B} = \frac{\vec{F}}{m_0}$$

If you calculate the field at a distance $r$ from a single isolated pole of strength $m$:

$$B = \frac{\mu_0}{4\pi} \frac{m}{r^2}$$

### 3. Units of $B$

- **SI Unit:** **Tesla (T)**
    $$1 \text{ T} = 1 \text{ N}\cdot\text{A}^{-1}\cdot\text{m}^{-1} = 1 \text{ Wb/m}^2$$
    
- **CGS Unit:** **Gauss (G)**
    
- **Conversion Factor:**
    
    $$1 \text{ Tesla} = 10^4 \text{ Gauss}$$
    

### 4. Key Properties

- It is a **vector quantity**.
    
- **Direction:** Outside a magnet, the direction of $\vec{B}$ is away from the North pole and toward the South pole. The tangent drawn at any point on a magnetic field line gives the direction of $\vec{B}$ at that point.
    
- It can be visually mapped by the density of field lines (closer lines = stronger $B$).

## Magnetic Dipole Moment for a Revolving Electron

If an electron is revolving in an orbit, its motion constitutes a tiny electric current loop, which produces a magnetic moment.

### Step-by-step Derivation

#### 1. Time Period of Revolution

For 1 complete revolution of an electron moving with velocity $v$ in a circular orbit of radius $r$, the time period $T$ is given by:

$$T = \frac{2\pi r}{v}$$

#### 2. Equivalent Electric Current

Electric current ($I$) is defined as the rate of flow of charge. Since the charge of an electron is $e$:

$$I = \frac{q}{T} = \frac{e}{T}$$

#### 3. Magnetic Moment Calculation

The magnetic dipole moment ($M$) of a current loop is given by:

$$M = I \cdot A$$

Where $A$ is the area of the circular orbit ($A = \pi r^2$).

Substituting the expressions for $I$ and $T$:

$$M = \left( \frac{e}{\frac{2\pi r}{v}} \right) \cdot \pi r^2$$

$$M = \frac{e \cdot v}{2\pi r} \cdot \pi r^2$$

Simplifying by canceling out common terms ($\pi$ and $r$):

$$M = \frac{evr}{2}$$


---
## Questions
**Q1:** A closely wound solenoid of $800$ turns and carrying a current of $4\text{ A}$ having area of cross-section $2.5 \times 10^{-4}\text{ m}^2$. If it can be treated as a bar magnet, then find its magnetic moment.

**Ans:** Given: $N = 800$, $I = 4\text{ A}$, $A = 2.5 \times 10^{-4}\text{ m}^2$

Formula: $M = N \cdot I \cdot A$

Calculation: $M = 800 \times 4 \times (2.5 \times 10^{-4}) = 8000 \times 10^{-4} = 0.8\text{ A}\cdot\text{m}^2$

Correct Option: **(C)**

---

**Q:** A bar magnet of dipole moment $3\text{ A}\cdot\text{m}^2$ is pivoted at its centre. A force $F$ acts at $90^\circ$ to its axis, $10\text{ cm}$ from the pivot. An external magnetic field of $0.25\text{ T}$ holds it in equilibrium at $30^\circ$ with the field. Find $F$ and the effect if $F$ is withdrawn.

**Ans:** Given: $M = 3$, $B = 0.25$, $\theta = 30^\circ$, $r = 10\text{ cm} = 0.1\text{ m}$

In equilibrium, Deflecting Torque = Restoring Torque

$$F \cdot r = MB\sin\theta$$

$$F \times 0.1 = 3 \times 0.25 \times \sin 30^\circ$$

$$F \times 0.1 = 0.375 \implies F = 3.75\text{ N}$$

- **Value of $F$:** $3.75\text{ N}$ (Option B)
- **If $F$ is withdrawn:** The unbalanced magnetic torque will rotate the magnet until it aligns parallel to the external magnetic field ($\theta = 0^\circ$).

---

**Q:** A magnetic dipole of dipole moment $m$ is aligned parallel to an external magnetic field $B$. Work of $0.25\text{ J}$ has to be done in order to turn it through an angle of $60^\circ$. Find the external counter torque that is required in order to maintain the dipole at this angle.

**Ans:** Given: $W = 0.25\text{ J}$, initial angle $\theta_1 = 0^\circ$, final angle $\theta_2 = 60^\circ$

1. **Find $mB$ using Work Done formula:**
    $$W = mB(\cos\theta_1 - \cos\theta_2)$$$$0.25 = mB(\cos 0^\circ - \cos 60^\circ)$$
    $$0.25 = mB\left(1 - \frac{1}{2}\right) = mB\left(\frac{1}{2}\right)$$$$mB = 0.25 \times 2 = 0.5\text{ J}$$
    
2. **Calculate Counter Torque ($\tau$) at $60^\circ$:**
    
    $$\tau = mB\sin\theta_2$$
    
    $$\tau = 0.5 \times \sin 60^\circ =  \frac{\sqrt{3}}{4} $$

---
gauss law