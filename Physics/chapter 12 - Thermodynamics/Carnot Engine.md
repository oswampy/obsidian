## **Carnot Engine**

The **Carnot Engine** is a theoretical thermodynamic cycle which extracts the maximum possible efficiency of a heat engine during conversion of heat into work while working between 2 reservoirs.

### **Carnot Theorem**

According to this, any system working between $T_1$ (hot reservoir) and $T_2$ (cold reservoir) can never have more efficiency than the Carnot engine operating between the same reservoirs.

### **Carnot Cycle**

An ideal reversible closed thermodynamic cycle consists of 4 consecutive operations:

1. **(i)** Isothermal expansion
2. **(ii)** Adiabatic expansion
3. **(iii)** Isothermal compression
4. **(iv)** Adiabatic compression

---

### **Carnot Cycle Diagram**

![[Pasted image 20251210170535.png]]


### **Isothermal Expansion (A → B)**

- $\text{Gas expands from } (P_1, V_1, T_H) \text{ to } (P_2, V_2, T_H).$
    
- $\Delta T = 0,\ \Delta U = 0$
    
- $\Delta Q_{AB} = \Delta W_{AB} = n R T_H \ln\left(\frac{V_2}{V_1}\right)$
    

---

### **Adiabatic Expansion (B → C)**

- $\text{Gas expands adiabatically from } (P_2, V_2, T_H) \text{ to } (P_3, V_3, T_C).$
    
- $\Delta Q_{BC} = 0$
    
- $\Delta U_{BC} = \Delta W_{BC}$
    
- $\Delta W_{BC} = nR \frac{T_H - T_C}{\gamma - 1}$
    

---

### **Isothermal Compression (C → D)**

- $\text{Gas compressed isothermally from } (P_3, V_3, T_C) \text{ to } (P_4, V_4, T_C).$
    
- $\Delta T = 0,\ \Delta U = 0$
    
- $\Delta W_{CD} = n R T_C \ln\left(\frac{V_4}{V_3}\right)$
    

---

### **Adiabatic Compression (D → A)**

- $\text{Gas compressed adiabatically from } (P_4, V_4, T_C) \text{ to } (P_1, V_1, T_H).$
    
- $\Delta Q_{DA} = 0$
    
- $\Delta W_{DA} = \Delta U$
    
- $\Delta W_{DA} = nR \frac{T_C - T_H}{\gamma - 1}$
    

---

### **Total Work in Cycle**

- $W = W_{AB} + W_{BC} + W_{CD} + W_{DA}$
    
- $W = n R T_H \ln\left(\frac{V_2}{V_1}\right) + n R T_C \ln\left(\frac{V_4}{V_3}\right)$
    
- $Q_{\text{in}} = n R T_H \ln\left(\frac{V_2}{V_1}\right)$
    
- $Q_{\text{out}} = n R T_C \ln\left(\frac{V_4}{V_3}\right)$
    

---

### **Efficiency**
Defined as ratio work done by the system to heat absorbed by system
- $\eta = \dfrac{W}{Q_{\text{in}}}$
    
- $\eta = 1 - \frac{Q_3}{Q_1}$
    
- $\eta = 1 - \frac{T_C}{T_H}$
    
#Q
- **The Temperature Limit:** A Carnot engine operates between a hot reservoir at **$500\text{ K}$** and a cold reservoir at **$300\text{ K}$**. What is its maximum theoretical efficiency?
    a) 0.4
- **Work Output:** If a heat engine has an efficiency of **$40\%$** and it absorbs **$5000\text{ J}$** of heat from the boiler, how much useful work does it perform?
	a)2000J