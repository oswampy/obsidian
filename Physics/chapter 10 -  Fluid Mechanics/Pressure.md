
$P = \frac{F}{A}$ $\frac{N}{m^2}$

$1 \text{ atm} = 10^5 \text{ Pa}$

Pressure created by a fluid at rest is equal in all directions at a point. When a fluid is at rest it exert a force ⊥ to and surface in its contact.

**Atmospheric pressure:** The pressure exerted by atmosphere on earth's surface. Normal atmospheric pressure at sea level is 1 atm.

**Absolute pressure & gauge pressure:** The pressure of any fluid in a container is called absolute pressure. The excess pressure above atmospheric pressure of that fluid is called gauge pressure.

---

**Gauge pressure** = $P - P_0$

Absolute pressure is always greater than or equal to zero while gauge can be -ve, 0, or +ve.

---

## **Variation in pressure with depth**

If the weight of the fluid is ignored, the pressure of the liquid will be the same throughout its volume. But we don't have massless fluid, so weight of fluid will change pressure with depth.

If we have some liquid (ρ) in container, we consider a thin element of liquid at height $y$ from bottom surface of area $A$ and thickness $dy$.
-dia
	![[Pressure.excalidraw]]
[Small diagram showing element with labels: ρ, dy, y, (P+dP)A, PA, w]

The force equation for that element of area A:
#Derivation 
$(P+dP)A + w = PA$

$w = \rho V g \Rightarrow \rho A dy g$ 

$(P+dP)A + \rho g dy A = PA$

$P + dP + \rho g dy = P$

$dP = -\rho g dy$

$\frac{dp}{dy} = -\rho g$

(-ve sign as measured from bottom, i.e. +ve otherwise)

Any surface in contact with atmosphere will feel 1 atm on ground.

---

### **Deriving relation b/w $P_0$ and $P_h$:**

$dp = \rho g dy$

$\int_{P_0}^{P} dp = \int_0^h \rho g dy$

$P - P_0 = \rho g h$

$P = \rho g h + P_0$

or $\Delta P = \rho g h$

**∴ Pressure in fluid increases with depth, density, acceleration due to gravity**

- **Pressure in a liquid at different points at same height is the same**

---

# Pascal's Law

According to Pascal's Law, pressure applied to an enclosed fluid is transmitted undiminished to every portion of the fluid and surfaces in contact.

We use Pascal's law in hydraulic lift.

_[Diagram showing two connected tubes with different areas A₁ and A₂, with forces F₁ and F₂ applied]_



According to Pascal's law, pressure at surface of both tubes should be same.

$$P_1 = P_2$$

$$F_1A_1 = F_2A_1$$

If we apply F₂ force on right tube, force applied on left tube is $F_1 = \frac{F_2A_1}{A_2}$

If $A_2 > A_1 \Rightarrow F_2 > F_1$

---

# Manometer

A device used to measure pressure of a gas inside container.

_[Diagram showing a U-tube manometer with mercury column heights Hg₂ and Hg₃, and height h]_

$$P_g = P_{Hg}$$

$$\boxed{P_g = \rho_{Hg}gh}$$

## Barometer

Used to measure atmospheric pressure.

_[Diagram showing a barometer with mercury column of height h, with pressure P₀ at top and P₀ at bottom]_

$$P_0 = P_{Hg}$$

$$P_0 = \rho_{Hg}gh$$

---

# FBD of Liquid

-dia
	![[FBD_LIQ.excalidraw]]
$$PA + w = PA + \rho ghA$$

## Free surface of accelerated liquid
-dia
	![[accel_surface.excalidraw]]


$$(P + dp)A - PA = mA$$

$$(P + dp)A - PA = \rho Adxa$$

$$dp = \rho adx$$

$$\frac{dp}{dx} = \rho a$$

$$\tan\theta = \frac{dh}{dx}$$

$$\frac{dp}{dh}\tan\theta = \rho a$$

$$\frac{\rho g dh \tan\theta}{dh} = \rho a$$

$$\tan\theta = \frac{a}{g}$$

 If any liquid is accelerating in vertical direction

$$\frac{dP}{dy} = -\rho g_{eff}$$
where $g_eff$can be g+a or g-a

---

# Archimedes Principle

If any object is fully or partially immersed in a fluid, an upward force is applied on that object which is equal to the weight of the liquid displaced by it. **Buoyant force**
-dia
	![[archimedes.excalidraw]]


$V_0$ submerged = $Ax$, $V_0$ outside = $A(L-x)$

$V_L$ displaced = $Ax$, mass of liquid displaced = $\rho Ax$

weight of liquid displaced = $\rho Axg$


$$\rho_0 = \rho Axg = wL$$

# Law of Floatation

## 1) If $\rho_L > \rho_0$

$$F_B = AL\rho_Lg$$ (Assume whole object in liquid)

$$w_0 = AL\rho_0g$$

$$F_B > w_0$$ (wrong Assumption that it's fully submerged)

So the object will float on surface and object will not be submerged fully. The object will be partially submerged such that:

$$F_B = w_0$$

$$\rho L\rho_Lg = \rho L\rho_0g$$

$$\rho L = L\rho_0$$

$$\rho = \frac{L\rho_0}{\rho_L}$$

## 2)  $\rho_L = \rho_0$, so 
$$F_B = w_0,$$

$$\frac{V}{V_0}\rho_\alpha g = \frac{V}{V_0}Lg$$

$$\rho = L$$

So object will be fully submerged in liquid & will not go to bottom.

## 3) $\rho_L < \rho_0$

Here, object will be fully submerged and will go to bottom of container such that $F_B + N = w_0$