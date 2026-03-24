When two particles interact with each other, where they apply a huge force on each other, this event is called **collision**.

1. During collision, force involved is very huge and time of action of force is very small, hence resulting in finite change in momentum of individual particle ($\infty \times 0 \to \text{finite}$).

2. Any finite force acting during collision will not change momentum of individual particles.

---
## Terms

-**Line of Impact**  
The line along which force is applied on both the particles during collision.  
	For regular objects like spheres, line of impact is center to center, but for other objects it may not be center to center.

-**Velocity of Approach**  
The relative velocity with which two particles are coming close to each other.
- **Case 1**: If particle 1 with velocity $V_1$ moves towards the right and particle 2 with velocity $V_2$ moves towards the left:
    - $V_{12} = V_{1g} - V_{2g}$
    - $V_{12} = V_1 - (-V_2)$
    - $V_a = V_1 + V_2$

- **Case 2**: If both particle 1 with velocity $V_1$ and particle 2 with velocity $V_2$ move to the right:
    - $V_{12} = V_{1g} - V_{2g}$
    - $V_{12} = -V_1 - (-V_2)$
    - If $V_2 > V_1$, then $V_a = V_2 - V_1$
If $r$ (distance) is known:  
$V_s = -\dfrac{dx}{dt}$ (cannot be -ve, distance decreases so function is negative hence the '-')

-**Velocity of separation** 
The relative velocity at which 2 particles are getting separated from each other.
-  **Case 1**: If particle 1 with velocity $V_1$ moves towards the right and particle 2 with velocity $V_2$ moves towards the left:
	$V_s = V_1 + V_2$
- **Case 2**: If both particle 1 with velocity $V_1$ and particle 2 with velocity $V_2$ move to the right
	$V_s = V_2 - V_1$
If $r$ (distance) is known:  
$V_s = \dfrac{dx}{dt}$

Collision is classified into two types on basis of velocity of approach and line of impact:

1. **Head-on Collision** – When $V_a$ is along line of impact. Everything is along a straight line, so it’s also called **1D collision**.

2. **Oblique collision (2D, 3D)** – When line of impact and velocity of approach are not along the same straight line, the collision is called oblique (2D/3D).


---

## **Conservation of Momentum**
#Derivation 
The direction in which net external force acting on any system of particles is $0$ then total linear momentum along that direction will remain conserved.
$\sum F_{\text{ext}} = 0$

Newton’s 2nd law:  
$a = 0$
$\dfrac{d\vec{v}}{dt} = 0$

$0 = m \dfrac{d\vec{v}}{dt}$  ($F = ma$)

$0 = \dfrac{d\vec{p}}{dt}$
$\Delta \vec{p} = 0$
Momentum is conserved.
### Example
Imagine a gun of mass M which fires a bullet of mass m with velocity u, the gun has a recoil velocity of V:
- In this system the initial momentum ($P_{i}$) is 0, therefor the final momentum($P_{f}$) should also be 0
- $P_{M}+P_{m}=0$
- $-MV+mu=0$ (negative velocity because gun recoils away from bullet)
- $MV=m u$
- $V = \frac{m u}{M}$

we can observe greater mass of gun(M); less recoil(V) and less mass of bullet(m) less recoil(V)

---
-dia
	![[excalidraw/COM.excalidraw]]

Although the total momentum of entire system is conserved, the momentum of individual particles will change because they apply force on each other.

$p_{1i} + p_{2i} = p_{1f} + p_{2f}$  (initial momentum = final momentum, individual $mv$ is different but total is constant).

**Conservation of momentum will be valid in all types of collisions.**

---

### **Example (Q1):**

$2kg ,4\text{kg}$ body with $4m/s,2\text{m/s}$ → collides with $2kg,4\text{kg}$ body with $v_{1}\;m/s,2\text{m/s}$
find $v_{1}$
Equation:  
$8 + 8 = 2v_1 + 12$

$16 - 12 = 2v_1$

$v_1 = 2 ,\text{m/s}$

(All due to $\Sigma F_{\text{ext}} = 0$, so ignore external forces.)

---


## **Impulse–Momentum Theorem**

During collision, impulse applied on any particle is equal to **change in momentum**, and direction of impulse is same as force applied on particle.

$\vec{J} = \Delta \vec{p}$

$\vec{J} = \int F_{\text{ext}}  dt$

When two particles collide, impulse imparted to both particles will **be equal and opposite.**

---

## **Conservation of Kinetic Energy**

When two particles collide, their K.E. gets converted into deformation P.E. After collision, if this P.E. gets converted back into K.E., the collision is called **elastic collision**.

Here, total K.E. before and after collision will remain conserved.
- If K.E. during collision gets converted into heat, then K.E. before and after collision is not conserved and is called **inelastic collision**.
    
- During collision, K.E. is never conserved. In **elastic collision** only, K.E. is conserved before and after.


---

### **Coefficient of Restitution ($e$)**

Defined as ratio of $V_s$ to $V_a$ of 2 particles colliding:

$e=\frac{V_s}{V_a}​​$

Value of $e$ is between $0$ and $1$.

- For **elastic collision**:  
    $e = 1 \quad \Rightarrow \quad \dfrac{V_s}{V_a} = 1 \quad \Rightarrow \quad V_s = V_a$
    
- For **inelastic collision**:  
    $0 < e < 1 \quad \Rightarrow \quad \dfrac{V_s}{V_a} < 1 \quad \Rightarrow \quad V_s < V_a$
    
- For **perfectly inelastic collision**:  
    $e = 0 \quad \Rightarrow \quad \dfrac{V_s}{V_a} = 0 \quad \Rightarrow \quad V_s = 0$

# 1-D Collision

## $\text{Head on collision}$

$u_1 = 3 \, \text{m/s}, \, u_2 = -3 \, \text{m/s}$ \\
$m_1 = 4 \, \text{kg}, \, m_2 = 2 \, \text{kg}, \, e = \tfrac{1}{2}$ \\

$\text{For equations use:}$ 
$\text{COLM and }$ $e$(coeff of rest.) if e = 1 we can use $\Delta KE=0$

$5 \times 4 + 3 \times 2 = 4 v_1 + 2 v_2 \quad (i)$ \\

$\frac{1}{2} = \frac{v_2 - v_1}{2} \quad \Rightarrow \quad v_2 - v_1 = 1 \quad (ii)$ \\

$2v_1 + v_2 = 12$ 
$+ v_2 - v_1 = 1$ 
$3v_1 = 12$ \
$v_1 = 4 \, \text{m/s}, \quad v_2 = 5 \, \text{m/s}$ 

$\text{- Calculate loss in K.E.}$

$\text{Before collision:}$
$KE = \tfrac{1}{2} \times 4 \times 3^2 + \tfrac{1}{2} \times 2 \times 3^2$ \\
$= 59 \, J$ 

$\text{After collision:}$ 
$KE = 57 \, J$
loss in KE = 2J (heat)

$\text{- For 4 kg mass specifically}$
$\Delta KE =KEi-KEf\implies 32 - 50 = -18 \, J$ loss in KE

Result: if two particles having same mass collide they will exchange velocities

### Questions:
(a) Tiger approaches person — how many bullets needed to stop it?  

Given: bullet mass 0.1 kg, bullet speed 400 m/s (to the right),  
tiger mass 100 kg, tiger speed 20 m/s (to the left).  

Require final velocity = 0 (to stop the tiger).  

Initial momentum:  
$p_i = n \times 0.1 \times 400 + 100(-20)$  
$p_i = 40n - 2000$  

Final momentum:  
$p_f = 0$  

Set $p_i = p_f$:  
$40n - 2000 = 0 \quad \Rightarrow \quad 40n = 2000$  
$n = 50$ bullets needed.  

---

(b)  

Diagram: a mass of 20 kg moving at 200 m/s and an 80 kg mass with unknown $v_2$; initial total momentum given as $p_i = 0$.  

Final momentum:  
$p_f = 200 \times 20 + v_2 \times 80$  

Conservation: $p_i = p_f$ gives  
$0 = 4000 + 80 v_2$  

$v_2 = -50 \ \text{m/s}$  (i.e. 50 m/s opposite to the 200 m/s direction).


# 2-D Collision

## $\text{Oblique Collision}$  

When $v_a$ and line of impact is not along the same direction, it is oblique collision.  

(a)  
-dia
	![[Oblique_coln.excalidraw]]
$e = \tfrac{1}{2}$  

COLM for system:  
$20 \times 0 + 2 \times 50 \times \cos 30 = -20v_1 + 2v_2 \sin \theta$  

$\Rightarrow 100 \cos 30 = -20v_1 + 2v_2 \sin \theta$  

COLM for 2 kg mass along $\hat{e_T}$:  
$2u \sin \theta = 2v_2 \cos \theta$  

Coefficient of restitution:  
$\tfrac{1}{2} = \dfrac{v_1 - v_2 \sin \theta}{u \cos \theta}$  

Solve 3 equations with 3 variables.

**Steps to solve oblique collision:**

1) Find line of impact between 2 particles.  
2) Define coordinate system along normal and tangential direction ($e_T$ and $e_N$).  
3) Assume velocity of both particles after collision.  
4) Break all velocity along normal and tangential directions.  
5) Develop equations using COLM, coefficient of restitution, and COR (if $e=1$).  
6) Solve equations and find all variables.  

• For the whole system, momentum will be conserved in all directions.  
• Along tangential direction, COLM is always conserved.




[[.md]]
[[Potential Energy]]
[[Newton's Laws of Motion]]