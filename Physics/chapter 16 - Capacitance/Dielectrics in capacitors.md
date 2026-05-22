
##  Dielectric in a Parallel Plate Capacitor
![[Pasted image 20260522201415.png]]
### **1. Initial Setup (Before Dielectric Insertion)**

- **Capacitor Plates:** Two parallel conducting plates with opposite surface charge densities ($+\sigma$ and $-\sigma$).
    
- **External Electric Field ($E_0$):** * Created by the charged plates.
    
    - Directs from the positive plate to the negative plate (left to right).
        
    - Formula in vacuum:
        
        $$E_0 = \frac{\sigma}{\varepsilon_0}$$
        

### **2. Behavior of Dielectric (Upon Insertion)**

- **Nature of Dielectric:** An insulating material with no free electrons.
    
- **Polarisation:** The external field ($E_0$) exerts forces on the bound charges within the dielectric molecules.
    
    - **Negative charges (electrons):** Displaced slightly _against_ the field (toward the $+\sigma$ plate).
        
    - **Positive charges (nuclei):** Displaced slightly _with_ the field (toward the $-\sigma$ plate).
        
    - This creates microscopic electric dipoles aligned with the field.
        

### **3. Induced Charges and Fields**

- **Induced Surface Charge Density ($\sigma_i$):** * Due to alignment, net charges appear on the outer boundaries of the dielectric.
    
    - $-\sigma_i$ forms on the left surface (facing the positive plate).
        
    - $+\sigma_i$ forms on the right surface (facing the negative plate).
        
- **Induced Electric Field ($E_i$):** * Created by the induced charges ($\sigma_i$).
    
    - Acts from right to left, directly **opposing** the external field ($E_0$).
        

### **4. Final Effects on Capacitor Parameters**

- **Net Electric Field ($E$):** Reduced inside the dielectric.
    
    $$E = E_0 - E_i = \frac{E_0}{K}$$
    
    _(where $K$ is the dielectric constant, $K > 1$)_
    
- **Potential Difference ($V$):** Decreases because $V = E \cdot d$.
	$$V=\frac{V_{0}}{K}$$
-  relationship between the induced surface charge density ($\sigma_i$) and the free surface charge density ($\sigma$) on the capacitor plates:

$$\sigma_i = \sigma \left(1 - \frac{1}{K}\right)$$
- **Capacitance ($C$):** **Increases.** Since $C = \frac{Q}{V}$ and voltage decreases for a given charge, the capacity to store charge rises:
#Derivation 
    $$C = K \cdot C_0$$
    $$C = \frac{Q}{V_{0}}K $$
    $$C = \frac{Q}{E_{0}d}K $$
    $E_{0}=\frac{Q}{A\varepsilon_{0}}$
    $$\boxed{C = \frac{\varepsilon_{0}A}{d}K} $$

### Advantages of dielectric


- **Increases Capacitance:** It reduces the internal electric field and voltage, multiplying the charge-storing capacity by the dielectric constant ($C = K \cdot C_0$).
    
- **Prevents Electrical Breakdown:** It acts as a superior insulator compared to air, allowing the capacitor to handle much higher operating voltages without sparking.
    
- **Mechanical Support:** It serves as a physical spacer that keeps the oppositely charged plates from pulling together and short-circuiting, allowing them to be placed closer together.

***Note:*** ------
For metals (and all perfect conductors), the dielectric constant is **infinite**:

$$K = \infty$$
 $$\sigma_{i}=\sigma\ (otherwise\ \sigma_{i}<\sigma)$$
 Why?

When a metal is placed in an external electric field, its free electrons move instantly to the surface until they create an internal induced electric field that exactly equals and cancels out the external field.

Since the net electric field inside a metal is zero ($E = 0$), and the relationship is defined as $E = \frac{E_0}{K}$, the value of $K$ must be infinity to reduce the internal field to zero.



## Capacitor partially filled with dielectric slab


- $d$ = Total separation distance between the capacitor plates.
- $t$ = Thickness of the dielectric slab inserted between the plates.
- $(d - t)$ = The remaining distance filled with air/vacuum.
- $E_0$ = Electric field in the air region ($E_0 = \frac{\sigma}{\varepsilon_0} = \frac{Q}{A\varepsilon_0}$).
- $\frac{E_0}{K}$ = Reduced electric field inside the dielectric slab due to polarization.

### Derivation Steps for Potential Difference ($\Delta V$)


- The total potential difference between the plates is the sum of the potentials across the air region and the dielectric region ($\Delta V = E_1d_1 + E_2d_2$):
	
	$$\Delta V = E_0(d - t) + \left(\frac{E_0}{K}\right)t$$
	
	Factor out the external field $E_0$:
	
	$$\Delta V = E_0 \left(d - t + \frac{t}{K}\right)$$
	
	Substitute $E_0 = \frac{Q}{A\varepsilon_0}$ into the equation:
	
	$$\Delta V = \frac{Q}{A\varepsilon_0} \left(d - t + \frac{t}{K}\right)$$

### Final Capacitance Formula

Using the fundamental definition of capacitance ($C = \frac{Q}{\Delta V}$), substituting the value of $\Delta V$ yields the final boxed equation:

$$C = \frac{\varepsilon_0 A}{d - t + \frac{t}{K}}$$

#### **Special Case**

If you insert a **conducting/metal slab** instead of a dielectric:

- Since $K = \infty$ for metals, the term $\frac{t}{K}$ becomes $\frac{t}{\infty} = 0$.
    
- The capacitance formula simplifies directly to:
    
    $$C = \frac{\varepsilon_0 A}{d - t}$$