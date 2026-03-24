
### Comparison Table

|**Translational**|**Rotational**|
|---|---|
|$\Delta r$|$\Delta \theta$|
|$v$|$\omega$|
|$a$|$\alpha$|
|$m$|$M.O.I$ $(I)$|
|$\vec{F}$|$\vec{\tau}$ - Torque|
|$\vec{p}$|$\vec{L}$ - Angular momentum|
|$K = \frac{1}{2}mv^2$|$R.K.E$|

### Moment of Inertia $(I)$

- $(I)$ is defined as product of mass and square of distance of mass from axis $$I = mr^2$$
- If we move the particle along a line parallel to axis of rotation or rotate it about axis keeping distance of particle $(r)$ same, The $(I)$ will remain unchanged.

## Moment of Inertia of Continuous Object

**1) M.O.I of a thin uniform thin rod of mass $m$ and length $L$ about axis $\perp$ to its length and passing through its CM.**

$I = \int r^2 dm$

$\lambda = \frac{m}{L}$
taking a small part(dx) of rod as uniform L 
$dm = \frac{m}{L} dx$
$\int dI = \int r^2 dm$
$\int_{-L/2}^{+L/2} r^2 dm$
$I = \frac{m}{L} \int_{-L/2}^{+L/2} x^2 dx$
$I = \frac{m}{L} \int_{-L/2}^{+L/2} x^2 dx$
$I = \frac{m}{3L} \left[\frac{L^3}{8} - \frac{(-L)^3}{8}\right]$

$I = \frac{mL^2}{12}$

---
## Parallel Axis Theorem

For any object, If $I_c$ is moment of inertia about axis passing through CM, the moment of inertia parallel to center CM axis and at distance $d$ is given as:

$$I = I_c + md^2$$

For an axis on perimeter of Ring:

$I_c = mR^2$

$I = I_c + mR^2$

$I = 2mR^2$

## Perpendicular Axis Theorem

If moment of inertia of a 2-D object about its 2 axis perpendicular to each other is $I_{1} \;\text{and}\; I_{2}$ and is lying in its plane, then moment of inertia about an axis perpendicular to its plane and passing through the intersection of other 2 perpendicular axis

$$I_{\perp} = I_1 + I_2$$

For axis on diameter of Ring:

$I_\perp = I_D + I_D$ (Same by symmetry)

$mR^2 = 2I_D$

$I_D = \frac{mR^2}{2}$

## Additive & Subtractive System

**Additive:**
-dia
	![[Additive_system.excalidraw]]
$I_{CA} = ma^2 + m(3a)^2 = 10ma^2$ ($I_{CA}$=I of Circle about point A)

$I_{SA} = \frac{ma^2}{6} + ma^2 = \frac{7ma^2}{6}$

We can add them now since they are about point A:

$\therefore I_{CA} + I_{SA} = \frac{67ma^2}{6}$

**Subtractive:**

$m_{SQ} = 16a^2\sigma$, $m_c = \pi a^2\sigma$

$I_{SO} = \frac{16a^2\sigma \times a^2}{6}$

$I_C = \frac{\pi a^2\sigma \times a^2}{2}$

$I_{CO} = \frac{\pi a^2\sigma \times a^2}{2} -\pi a^2\sigma \times a^2 = -\frac{3\pi a^4\sigma}{2}$

Now we can add them (one is already negative):
$I_{SO}+I_{CO}=\frac{16a^4\sigma}{6}\;-\;\frac{9\pi a^{4}\sigma}{6}$
$I_{SO}+I_{CO}=\frac{a^4\sigma(16-9\pi)}{6}$

---
## Torque ($\vec{\tau}$) 

Defined as cross product of position vector from axis of rotation to point of application of force and force vector

$$\vec{\tau} = \vec{r} \times \vec{F}$$

$\tau = |r| \times |F| \times \sin \theta$

or with components:

$\vec{\tau} = r \times F_{\perp}$

$\vec{\tau} = r_{\perp} \times F$

- If force is parallel to axis of rotation or along radius vector then its torque will be 0
    
- Force will have non-zero torque only if it is **perpendicular** to **axis of rotation** **as well as position vector**

### Angular Momentum ($\vec{L}$)

- Defined as cross product of radius vector and linear momentum vector, all rules defined for torque will apply here too.


$$\vec{L} = \vec{r} \times \vec{p}$$

$|\vec{L}| = r \cdot p \cdot \sin \theta$

	**In components:**  
	$\vec{L} = r_{\perp} \cdot p$
	
	$\vec{L} = r \cdot p_{\perp}$

**S.I. Unit:** $\text{kg m}^2 \text{s}^{-1}$

---

### **Example:**
-dia
	![[ball_ang_acc.excalidraw]]
$V{cg} = V_0$
$V_{ac} = \omega R$
$V_{bc} = -\omega R$
$V_{ac} = V_{ag} - V_{cg}$
$\boxed{V_{ag} = V_0 + \omega R}$
$V_{bc} = -\omega R$
$V_{bc} = V_{bg} - V_{cg}$
$\boxed{V_{bg} = V_0 - \omega R}$

_(There will be slipping if $V_0$ is less and $\omega R$ will be more.)_
#concept 
#### Condition for no slipping

- “No slipping” means the **point of the body in contact with the surface** has **zero velocity relative to the surface**.
    
- Let the **center of mass move forward with speed v**.
    
- The body also **rotates** with angular speed ω.
    
- The linear speed of the point at the bottom (relative to CM) = R ω backward
    
- For the bottom point to have **zero net speed relative to ground**:  
    **v − R ω = 0**


---
## Rotational Equilibrium

A body is said to be in rotational equilibrium if net torque acting on the body about the axis of rotation is 0.

**Case I:** It may be possible that an object is in translational equilibrium but not in rotational equilibrium.$\sum \tau \ne0$ but $\sum F_{ex}=0$

**Case II:** An object may be in rotational equilibrium but not in translational equilibrium.$\sum \tau =0$ but $\sum F_{ex}\ne0$

---

## Problem Solution
-dia
	![[Q_dia4.excalidraw]]
Using translational equations:

- $N_2 = F_{f}$ (x-axis equation)          - i
- $N_1 = mg$ (y-axis equation)              - ii

Using rotational equation about A:
$\tau = -mg\cos\alpha \cdot \frac{L}{2} + N_2\sin\alpha \cdot L$          - iii

($\tau$ is +ve in anti-clockwise direction;vector method)

Solve 3 equations, 3 variables.



---

## Hinge Force

When any object is hinged at any point, the force applied by hinge on the object is called hinge force.

**Note:** If any rigid object is hinged, it will rotate about that hinged point. If not hinged, it will rotate about center of mass.
-dia
	![[Hinge.excalidraw]]
$\alpha$ is to be 0:
$H_1 = mg$
$H_2 = 0$

---

## Radius of Gyration

If we convert any object into a ring such that its mass and $MoI$ remain same, then radius of ring is called **radius of gyration**.

For Circular Ring:  
$M r^2 = M n^2$  
$K = r$

---

#### **Pure rolling & slipping**

**Case I**  (slipping)
If $v_0 > \omega R$  
$v_{\text{bg}} \to$ forward  
friction $\to$ backward  

**Case II**  (pure rolling)
If $v_0 = \omega R$  
$v_{\text{bg}} = 0$  
friction  

**Case III**  ( slipping)
If $v_0 < \omega R$  
$v_{\text{bg}} \to$ backward  
friction $\to$ forward

---

#Q**Pulley problem**
-dia
	![[Weight_pulley.excalidraw]]
Rotational eqn (pulley):  
$TR = I \alpha$  
$TR = \dfrac{MR^2}{2}\alpha \quad \cdots (i)$

Translational eqn (block):  
$mg - T = ma_c$  
$a_c = \alpha R \quad \cdots (ii)$

From (i):  
$TR = \dfrac{MR^2}{2}\cdot \dfrac{a_c}{R}$  
$T = \dfrac{Ma_c}{2}$

From (ii):  
$mg = ma_c + \dfrac{Ma_c}{2}$  
$a_c = \dfrac{2g}{3}$

---

## **Rotational work done and energy**

$W_r = \vec{\tau} \cdot \Delta \vec{\theta}$

---

### **Work–Energy theorem**

$\Delta R.K.E = \sum W_r$

$R.K.E$ = sum of translational K.E. of all the individual particles in a system of particles or any object, is called **rotational K.E.**

If work done by non-conservative torque is zero, then

$\Delta M.E = 0$
$\Delta P.E + \Delta R.K.E$