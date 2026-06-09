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

 Step-by-step Derivation
1. Time Period of Revolution

For 1 complete revolution of an electron moving with velocity $v$ in a circular orbit of radius $r$, the time period $T$ is given by:

$$T = \frac{2\pi r}{v}$$

 2. Equivalent Electric Current

Electric current ($I$) is defined as the rate of flow of charge. Since the charge of an electron is $e$:

$$I = \frac{q}{T} = \frac{e}{T}$$

 3. Magnetic Moment Calculation

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
## Gauss's Law in Magnetism

Gauss's Law for magnetism states that the net magnetic flux ($\phi_{\text{net}}$) through any closed surface is always equal to zero.

$$\phi_{\text{net}} = \oint \vec{B} \cdot d\vec{A} = 0$$

### Key Concept: Non-Existence of Magnetic Monopoles

Unlike electrostatics—where isolated positive or negative charges can exist independently—**isolated magnetic poles (monopoles) do not exist** in nature. Magnetic poles always occur in equal and opposite pairs (North and South).

- If you break a bar magnet in half, you do not separate the North pole from the South pole; instead, you get two smaller magnets, each possessing its own North and South poles.
    
- Because every North pole is inextricably linked with a South pole, any closed Gaussian surface enclosing part of or an entire magnet will always contain a net magnetic pole strength of zero ($m_{\text{net}} = 0$).


### Field Line Behavior

Because monopoles do not exist, magnetic field lines do not start or stop at a single point.

- They form continuous, closed loops.
    
- Outside a magnet, they travel from the North pole to the South pole.
    
- Inside a magnet, they continue from the South pole back to the North pole.
    

> **Physical Meaning:** For any arbitrary closed surface, the number of magnetic field lines entering the surface will always be exactly equal to the number of field lines exiting that surface. No lines can originate or terminate inside the volume.


Here are the quick-reference notes and definitions based on the terminologies shown in your latest screenshot.

## Magnetizing Intensity ($H$)

**Magnetizing Intensity** (also called magnetic field strength) measures the capability of an external factor (like a current-carrying solenoid) to induce magnetism in a material medium.

It depends entirely on the external currents producing the field and is independent of the nature of the medium inside.

### Mathematical Formula

For a core inside a long solenoid with $n$ turns per unit length carrying a current $I$:

$$B_0 = \mu_0 n I$$

Since $H = n I$, the magnetic induction in a vacuum ($B_0$) can be written as:

$$B_0 = \mu_0 H$$

Isolating $H$:

$$H = \frac{B_0}{\mu_0}$$

- Where:
	- $H$ = Magnetizing intensity
	    
	- $B_0$ = Magnetic flux density (magnetic induction) in free space
	    
	- $\mu_0$ = Permeability of free space ($4\pi \times 10^{-7} \text{ T}\cdot\text{m/A}$)


### Units of $H$

- **SI Unit:** **$\text{A}\cdot\text{m}^{-1}$** (Ampere per meter)

## Intensity of Magnetization ($I$ or $M$)

**Intensity of Magnetization** measures the extent to which a magnetic material gets magnetized when placed in an external magnetizing field. It represents the degree of alignment of atomic magnetic dipoles within the material.

### Mathematical Formulas

There are two equivalent ways to define and calculate it mathematically:

1. **Per Unit Volume Definition:**
    
    It is defined as the net magnetic dipole moment ($M$) developed per unit volume ($V$) of the material.
    
    $$I = \frac{\text{Magnetic moment}}{\text{Volume}} = \frac{M}{V}$$
    
2. **Per Unit Area Definition:**
    
    For a uniform bar magnet, it can also be expressed as the magnetic pole strength ($m$) developed per unit cross-sectional area ($A$).
    
    $$I = \frac{\text{pole strength}}{\text{Area of cross-section}} = \frac{m}{A}$$
    

#### Derivation Connection:

$$I = \frac{M}{V} = \frac{m \times l}{A \times l} = \frac{m}{A}$$

_(Where $l$ is the geometric length/distance between poles)._

### Units of I

- **SI Unit:** **$\text{A}\cdot\text{m}^{-1}$** (Ampere per meter)

---
## Magnetic Permeability ($\mu$)

**Magnetic Permeability** measures a material's ability to allow magnetic field lines to pass through it, indicating how easily it can become magnetized by an external field.

### Key Formulas

- **Absolute Permeability of a Medium ($\mu_m$):**$$\mu_m = \mu_0 \mu_r$$
- **Relative Permeability ($\mu_r$):**$$\mu_r = \frac{\mu_m}{\mu_0}$$
    

Where $\mu_0$ is the permeability of free space ($4\pi \times 10^{-7}\text{ T}\cdot\text{m/A}$).

### Classification of Materials Based on Permeability

The behavior of magnetic field lines changes significantly depending on the type of material placed in the field:

|**Material Type**|**Permeability Relationship**|**Relative Permeability**|**Behavior of Field Lines**|
|---|---|---|---|
|**Diamagnetic**|$\mu_1 < \mu_0$|$\mu_r < 1$|Expels magnetic field lines; lines tend to pass around the material.|
|**Paramagnetic**|$\mu_2 > \mu_0$|$\mu_r > 1$|Feebly attracts magnetic field lines; lines concentrate slightly inside.|
|**Ferromagnetic**|$\mu_3 \gg \mu_0$|$\mu_r \gg 1$|Strongly concentrates magnetic field lines densely inside the material.|
![[Pasted image 20260609213648.png]]

---

## Magnetic Susceptibility ($\chi_m$)

**Magnetic Susceptibility** is a dimensionless property that measures how easily and to what extent a magnetic material becomes magnetized when placed in an external magnetizing field.

It is defined as the ratio of the intensity of magnetization ($I$) induced inside the material to the magnetic intensity ($H$) of the external field.

### Mathematical Formula

$$\chi_m = \frac{I}{H}$$

- Where:
	- $\chi_m$ = Magnetic susceptibility
	    
	- $I$ = Intensity of magnetization
	    
	- $H$ = Magnetizing intensity

### Key Properties

- **Units:** Since both $I$ and $H$ share the exact same SI unit ($\text{A}\cdot\text{m}^{-1}$), their units cancel out. Therefore, magnetic susceptibility is a **pure number with no units or dimensions**.
    
- **Relation with Relative Permeability ($\mu_r$):**
    
    $$\mu_r = 1 + \chi_m$$
#Derivation 
 Step 1: Total Magnetic Induction ($B$)

When a magnetic material is placed inside an external magnetizing field, the total magnetic field $B$ inside the material is the sum of the external magnetic field in free space ($B_0$) and the magnetic field induced due to the magnetization of the material ($B_m$):

$$B = B_0 + B_m$$

 Step 2: Substitute Field Relations

We know from the definitions of magnetizing intensity ($H$) and intensity of magnetization ($I$):
- $B_0 = \mu_0 H$
- $B_m = \mu_0 I$

$$B = \mu_0 H + \mu_0 I$$

$$B = \mu_0(H + I)$$
 Step 3: Introduce Permeability and Susceptibility

1. By definition, the total magnetic field inside a medium with absolute permeability $\mu_m$ is:
    $$B = \mu_m H$$
2. By definition, the intensity of magnetization is related to magnetic susceptibility ($\chi_m$) by:
    $$I = \chi_m H$$
### Step 4: Combine and Simplify

Substitute $B$ and $I$ back into the factored equation from Step 2:

$$\mu_m H = \mu_0(H + \chi_m H)$$

Divide the entire equation by $H$ on both sides:

$$\mu_m = \mu_0(1 + \chi_m)$$

Divide by $\mu_0$:

$$\frac{\mu_m}{\mu_0} = 1 + \chi_m$$

Since relative permeability is defined as $\mu_r = \frac{\mu_m}{\mu_0}$:

$$\mu_r = 1 + \chi_m$$

---
### Values for Different Materials

The sign and magnitude of $\chi_m$ tell us how a material will respond to an external magnetic field:

- **Diamagnetic Materials:** Have a **small, negative** value ($\chi_m < 0$). They are weakly magnetized in a direction opposite to the external field.
    
- **Paramagnetic Materials:** Have a **small, positive** value ($\chi_m > 0$). They are weakly magnetized in the same direction as the external field.
    
- **Ferromagnetic Materials:** Have a **large, positive** value ($\chi_m \gg 0$). They get strongly magnetized in the direction of the external field.

## Paramagnetic Materials

**Paramagnetic Materials** are substances that get feebly (weakly) magnetized in the direction of an external magnetizing field. When placed in a non-uniform magnetic field, they tend to move slowly from weaker parts to stronger parts of the field.

### Key Properties & Atomic Origin

- **Unpaired Electrons:** Paramagnetism arises primarily due to the presence of **unpaired electrons** in the atoms, ions, or molecules of the material. The spin of these unpaired electrons provides a net intrinsic magnetic moment.
    
- **Permanent Atomic Dipoles:** Unlike diamagnetic substances, the individual constituent atoms of a paramagnetic material **possess a permanent magnetic dipole moment** of their own.
    
- **Random Thermal Motion:** In the absence of an external magnetic field, these atomic dipoles are oriented completely at random due to thermal agitation. As a result, their magnetic moments cancel each other out, making the **net macroscopically observed dipole moment equal to zero**

- **Magnetic Field Enhancement:** When placed in an external magnetic field, the net internal magnetic field increases slightly.
    
- **Relative Permeability ($\mu_r$):** It is **slightly greater than one** ($\mu_r > 1$).
    
- **Magnetization Behavior:** They get feebly (weakly) magnetized in the same direction as the external magnetic field.
    
- **Field Line Interaction:** Magnetic field lines are weakly attracted and tend to concentrate slightly inside a paramagnetic sample.
    
- **Mechanical Tendency:** If placed in a non-uniform magnetic field, these materials experience a weak force pulling them from regions of **weak magnetic field to strong magnetic field**.
    
- **Magnetic Susceptibility ($\chi_m$):** It is **slightly positive** ($\chi > 0$).
    
- **Common Examples:** Aluminium ($\text{Al}$), Chromium ($\text{Cr}$).
### Behavior in an External Field

When an external magnetic field ($B_0$) is applied:

1. The field exerts a torque on the permanent atomic dipoles, trying to align them along the direction of the field lines.
    
2. At room temperature, thermal motion partially disrupts this alignment, resulting in a weak net alignment parallel to the field.

---

## Diamagnetic Materials

**Diamagnetic Materials** are substances that develop a feeble (weak) magnetization in a direction opposite to that of an external magnetizing field. When placed in a non-uniform magnetic field, they experience a weak repulsive force that pushes them from stronger parts to weaker parts of the field.

### Key Properties & Atomic Origin

- **Paired Electrons:** Diamagnetism is a fundamental property found in all materials, but it is dominant in substances where the atoms, ions, or molecules have completely **paired electrons**.
    
- **Zero Intrinsic Dipole Moment:** Because the electrons are completely paired up, their orbital and spin magnetic moments cancel each other out perfectly. Consequently, individual constituent atoms of a diamagnetic material **possess no permanent magnetic dipole moment** of their own.
    
- **Induced Opposition:** When an external magnetic field is applied, the orbital motion of the electrons shifts (in accordance with Lenz's Law). This induces a weak magnetic dipole moment in each atom that strictly **opposes the applied field**.

- **Magnetic Field Reduction:** When placed in an external magnetic field, the net internal magnetic field decreases slightly.
    
- **Relative Permeability ($\mu_r$):** It is **slightly less than one** ($\mu_r < 1$).
    
- **Magnetization Behavior:** They get feebly (weakly) magnetized in the **direction opposite** to the external magnetic field.
    
- **Field Line Interaction:** Magnetic field lines are weakly repelled by diamagnetic materials; the lines prefer to pass around and avoid the sample.
    
- **Mechanical Tendency:** If placed in a non-uniform magnetic field, these materials have a tendency to move from a **region of strong magnetic field to a weak magnetic field**.
    
- **Magnetic Susceptibility ($\chi_m$):** It is **slightly negative** ($\chi_m < 0$) and independent of temperature.
    
- **Common Examples:** Copper ($\text{Cu}$), Lead ($\text{Pb}$), Water, Bismuth, Silicon,Gold,Silver,Mercury.

### Behavior in an External Field

When a diamagnetic material is placed in an external magnetic field ($B_0$):

1. An induced magnetic dipole moment is developed within the atoms, oriented strictly in opposition to the applied field.
    
2. Because of this internal opposition, the magnetic field lines find it more difficult to pass through the material compared to free space, causing them to spread out and pass around the sample.


## Ferromagnetic Materials

**Ferromagnetic Materials** are substances that get strongly magnetized in the direction of an external magnetizing field. When placed in a non-uniform magnetic field, they experience a strong attractive force that pulls them quickly from weaker parts to stronger parts of the field.

### Key Properties & Atomic Origin

- **Domain Structure:** The atoms of ferromagnetic materials possess permanent magnetic dipole moments (similar to paramagnetic materials due to unpaired electrons). However, they interact with neighboring atoms through strong quantum mechanical forces, causing them to align spontaneously over tiny microscopic regions called **magnetic domains**.
    
- **Random Domain Orientation (Unmagnetized State):** In the absence of an external magnetic field, different domains are oriented in completely random directions. Even though each domain is highly magnetized internally, the macroscopic **net dipole moment of the entire material remains zero**.
    
- **Strong Domain Alignment (Magnetized State):** When an external magnetic field is applied, the domains aligned with the field grow larger, and other domains rotate to align parallel to the external field. This produces a massive net magnetization.

- **Magnetic Field Amplification:** When placed in an external magnetic field, the net internal magnetic field increases dramatically.
    
- **Relative Permeability ($\mu_r$):** It is **extremely large** ($\mu_r \gg 1$, typically on the order of hundreds or thousands).
    
- **Magnetization Behavior:** They get strongly magnetized in the **same direction** as the external magnetic field.
    
- **Field Line Interaction:** Magnetic field lines are strongly attracted by ferromagnetic materials; the lines crowd together and concentrate densely inside the sample.
    
- **Mechanical Tendency:** If placed in a non-uniform magnetic field, these materials have a strong tendency to move quickly from a **region of weak magnetic field to a strong magnetic field**.
    
- **Magnetic Susceptibility ($\chi_m$):** It is **large and positive** ($\chi_m \gg 0$) and decreases with an increase in temperature according to the Curie-Weiss law.
    
- **Common Examples:** Iron ($\text{Fe}$), Cobalt ($\text{Co}$), Nickel ($\text{Ni}$), Gadolinium ($\text{Gd}$).
    

### Behavior in an External Field

When a ferromagnetic material is placed in an external magnetic field ($B_0$):

1. The external field forces the pre-existing magnetic domains to line up perfectly parallel to the field lines.
    
2. This massive internal alignment acts like a booster, pulling almost all nearby magnetic field lines straight through the core of the material.


The user has uploaded a new image (`image_28aa5f.jpg`) showing a slide about the **Effect of Temperature on Magnetic Materials**. Here is the summary of **Curie's Law for Paramagnetic Materials** structured in the same style as your previous study notes.

---
## Effect of Temperature on Paramagnetic Materials (Curie's Law)

**Curie's Law** describes how the magnetic susceptibility of a paramagnetic material changes with absolute temperature. It states that the magnetic susceptibility ($\chi$) of a paramagnetic substance is inversely proportional to its absolute temperature ($T$).

### Mathematical Expression

$$\chi \propto \frac{1}{T}$$

To remove the proportionality sign, we introduce a constant called **Curie's Constant ($C$)**:

$$\chi = \frac{C}{T}$$

Since we know that magnetic susceptibility is also defined as $\chi = \frac{I}{H}$, we can equate the expressions:

$$\frac{C}{T} = \frac{I}{H} \implies I = \frac{HC}{T}$$

From this relationship, it follows that the intensity of magnetization ($I$) is inversely proportional to temperature:

$$I \propto \frac{1}{T}$$

- Where:
	
	- $\chi$ = Magnetic susceptibility
	    
	- $T$ = Absolute temperature (measured in Kelvin)
	    
	- $C$ = Curie's constant (characteristic of the material)
	    
	- $I$ = Intensity of magnetization
	    
	- $H$ = Magnetizing intensity
### Physical Explanation

The alignment of atomic magnetic dipoles in a paramagnetic material is a battle between two competing factors:

1. **The External Magnetic Field ($H$):** Tries to align the atomic dipoles parallel to the field lines to increase magnetization.
    
2. **Thermal Agitation (Temperature $T$):** Randomizes the orientation of the atomic dipoles due to thermal kinetic energy, disrupting the alignment.
    

- **At Low Temperatures:** Thermal agitation is weak, allowing the external field to successfully align more dipoles, resulting in higher magnetic susceptibility ($\chi$).
    
- **At High Temperatures:** Thermal agitation becomes very high, violently shaking the atomic dipoles out of alignment, causing the magnetic susceptibility ($\chi$) to drop.
    

### Graphical Representation

A plot of magnetic susceptibility ($\chi$) versus absolute temperature ($T$) forms a **rectangular hyperbola**, showing that $\chi$ drops rapidly as the material gets hotter.
![[Pasted image 20260609224044.png]]

Here is how temperature affects **Diamagnetic** and **Ferromagnetic** materials:

## Effect of Temperature on Diamagnetic Materials

Unlike paramagnetic substances, the magnetic susceptibility ($\chi$) of diamagnetic materials is **completely independent of temperature**.

### Physical Explanation

- Diamagnetism does not rely on permanent atomic dipoles that can be disrupted by heat.
    
- Instead, it arises from the **induced orbital motion of paired electrons** when an external field is applied.
    
- Because this induction is a direct consequence of electromagnetic interactions at the atomic level (governed by Lenz's Law), thermal shaking has no effect on it.
    

### Graphical Representation

A plot of magnetic susceptibility ($\chi$) versus absolute temperature ($T$) for a diamagnetic material is a **straight horizontal line** in the negative region.
![[Pasted image 20260609224033.png]]
## Effect of Temperature on Ferromagnetic Materials (Curie-Weiss Law)

The magnetic susceptibility of a ferromagnetic material **decreases with an increase in temperature**. When heated past a certain critical threshold, a ferromagnetic material loses its strong magnetic properties entirely and transitions into a standard **paramagnetic material**.

### Critical Temperature: The Curie Point ($T_C$)

The specific temperature at which a ferromagnetic material transitions into a paramagnetic material is called the **Curie Temperature ($T_C$)**.

- **Below $T_C$ ($T < T_C$):** The material remains ferromagnetic. The strong quantum mechanical interactions keep the magnetic domains locked in alignment.
    
- **Above $T_C$ ($T > T_C$):** The thermal energy is high enough to completely break the domain structure. The domains dissolve, leaving behind randomly oriented permanent atomic dipoles. The material now behaves exactly like a **paramagnetic material**.
    

### Mathematical Expression (The Curie-Weiss Law)

For temperatures above the Curie point ($T > T_C$), the magnetic susceptibility follows the **Curie-Weiss Law**:

$$\chi = \frac{C}{T - T_C}$$

- Where:
	- $\chi$ = Magnetic susceptibility (in the paramagnetic phase)
	    
	- $C$ = Curie's constant
	    
	- $T$ = Absolute temperature of the material
	    
	- $T_C$ = Curie temperature of the specific material

### Curie Temperatures of Common Materials

- **Iron ($\text{Fe}$):** $T_C \approx 1043\text{ K}$ ($770^\circ\text{C}$)
- **Nickel ($\text{Ni}$):** $T_C \approx 627\text{ K}$ ($354^\circ\text{C}$)
- **Cobalt ($\text{Co}$):** $T_C \approx 1388\text{ K}$ ($1115^\circ\text{C}$)

### Graphical Representation

A plot of magnetic susceptibility ($\chi$) versus temperature ($T$) shows high, changing values in the ferromagnetic region, which sharply drop following a hyperbolic curve once the temperature passes $T_C$.
![[Pasted image 20260609224017.png]]