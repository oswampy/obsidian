# Stress-Strain Curve

## Key Points on the Curve:

**O-A: Proportional Limit**

- At origin, strain and stress are 0
- From O to A, material will show elastic behaviour as well as follow Hooke's Law

**B: Upper yield stress point**

**C: Lower yield stress point**

**D: Ultimate stress point**

**E: Fracture**

---

## Behavior Regions:

### 1) Elastic Behaviour (O to A)

- **OA**: The material will show elastic behaviour but it will not follow Hooke's law; the stress-strain curve is no more linear

### 2) Strain Hardening (A to B)

- **AB**: The material will show elastic behaviour, but it will not follow Hooke's law; the stress-strain curve is no more linear

### 3) Plastic Deformation (B to C)

- **BC**: If we increase strain further after point B, the stress will start to decrease. Here (B) plastic deformation starts and at point C, stress reaches its minimum value. Here at B to C, material dimensions will be changed easily

### 4) Strain Hardening/Necking (C to D)

- **CD**: If we increase strain further after point C, the stress will again start to increase due to internal strengthening and at point D, stress will reach its maximum value. In this section, the material will show plastic behaviour, but it will become stronger

### 5) Fracture (D to E)

- **DE**: This is called breaking or fracture point. Here, cross-section of material decreases rapidly and then breaks

---

# Modulus of Elasticity

$K = \frac{\text{stress}}{\text{strain}}$

- K is dependent on nature of material
- K is independent on dimension of material

## Three types of Modulus of Elasticity:

### 1) Young's Modulus (Y)

$Y = \frac{\text{longitudinal stress}}{\text{longitudinal strain}} = \frac{F\ell}{A\Delta\ell}$

**Example**: Find change in length of rod due to own weight $(m, \ell, A, Y)$

- Stress = $\frac{m'g}{A}$
- Strain = $\frac{d(\Delta\ell)}{d\ell}$

Where:

- $m' = \frac{M}{L} \times \ell$
- $m'g$ represents tension $T$

**Derivation**:

$Y = \frac{m'g}{A} \times \frac{d\ell}{d(\Delta\ell)}$

$Y = \frac{Mg}{LA} \times \frac{d\ell}{d(\Delta\ell)}$

$d(\Delta\ell) = \frac{mg}{LAY} \times d\ell$

**Integrating**:

$\int d(\Delta\ell) = \frac{mg}{LAY} \int_0^\ell \ell , d\ell$

**Result**: $\boxed{\Delta\ell = \frac{mg\ell^2}{2AY}}$

---

### 2) Modulus of Rigidity ($\eta$)

$\eta = \frac{\text{shear stress}}{\text{shear strain}} = \frac{F}{A \tan\theta}$

- If $\tan\theta$ is small
- $\eta \approx \frac{F}{A\theta}$

---

### 3) Bulk Modulus (K)

$K = \frac{\text{volume stress}}{\text{volume strain}} = \frac{-PV}{\Delta V}$

or $K = \frac{PV}{\Delta V}$

**Note**:

- Compressibility: reciprocal of Bulk modulus = $\frac{1}{K}$
- Bulk modulus of solid is about 50 times that of liquid and for gases it is $10^{-8}$ of solids

$B_s = 50 B_L$

$B_g = 10^{-8} B_s$