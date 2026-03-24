
Heat is a form of energy which flows from higher temperature to lower temperature. The transfer of heat from one body to another takes place through:

1. **Conduction:** Material medium is needed for heat transfer but material will not move. Only heat energy moves.
    
2. **Convection:** Material medium needed for heat transfer and it will move with it.
    
3. **Radiation:** No material medium needed. Heat transferred through E.M waves.
    

---


## Conduction

## Temperature Gradient

**Change:** The fall in temperature per unit length of a conductor:

$\frac{dT}{dx}$ (temp gradient)

If we have a conductor of length $L$ and cross section area $A$ then rate of flow of heat through conduction is:

```
()────────────────()A
        L
```

$\frac{dQ}{dt} \propto A \frac{dT}{dx}$

$\frac{dQ}{dt} = -KA \frac{dT}{dx}$

$(K \text{ is thermal conductivity of material})$

The '-ve' sign shows from high to low temp

## · Steady State

If temperature of a cross-section at any point in the conductor remains constant with time, the conductor is said to be in steady state.

Temperature of two different position may vary.

If any conductor is in steady state, it means no heat is absorbed or emitted from any surface except its two ends. For any conductor in steady state, $\frac{dT}{dx} = 0$ is constant.

$\frac{dT}{dx} = \frac{\Delta T}{\Delta x}$

$\frac{dT}{dx} = \frac{T_c - T_H}{L}$ (w.r.t whole length $L$)

Now rate of heat flow for a conductor can be written as (cross-section $A$ will be taken $\perp$ to $Q$)

$\frac{dQ}{dt} = -KA \frac{(T_c - T_H)}{L}$

$\frac{dQ}{dt} = \frac{KA(T_H - T_c)}{L}$

$\int dQ = \int \frac{KA \Delta T}{L} dt$

$Q = \frac{KA \Delta T}{L} \Delta t$

$Q$ is amt of heat flow.

**Q)** One face of an Al cube of edge 2m is maintained at 100°C, other end maintained at 0°C. All other surfaces are insulated. $K = 209$

**A)** $\frac{209 \times 4 \times 100 \times S}{2} = 2.09 \times 10^5$

---

## Heat Current ($I_H$)

rate of flow of Heat

$I_H = \frac{dQ}{dt} = \frac{Q}{\Delta t}$

$I_H = \frac{KA \Delta T}{L}$

If temperature difference is treated as potential difference Resistance of conduction will be

$R = \frac{L}{KA}$ 

$I_H = \frac{\Delta T}{R}$ (I=V/R)

---
## Kirchhoff's Current Law

Total current going at a junction point should add up to zero

```
   I₁ ──→ ──→ I₂     I₁ = I₂
```

```
        I₂
         ↓
    I₁ ──X── I₃   I₁ - I₂ + I₃ - I₄ = 0
         ↑
        I₄         I₁ + I₃ = I₂ + I₄
```



##  Thermal Conductors Connected in Series



If two conductors are connected such that heat current is flowing through both conductors it is said to be in series

[Diagram showing two conductors R₁ and R₂ in series with temperatures TH, T, I₂, and TL marked]

I₁ = (TH - T)/R₁ 
I₂ = (T - TL)/R₂

If we want to replace both by one equivalent Resistance (I)($R_{eq}$)

R₁I₁ = TH - T I 
R₂I₂ = T - TL

R₁I₁ + R₂I₂ = TH - TL R₁I₁ + R₂I₂ = Req I (I₁ = I₂ = I)
$$R₁ + R₂ = R_{eq}$$

---

##  Parallel Combination

**Parallel combination**

When Temperature difference across conductors are same:

[Diagram showing parallel conductors with labels TH, TL, A₁, A₂, K₁, K₂]

I₁ = (TH - TL)/R₁ I₂ = (TH - TL)/R₂

To replace with one conductor I = (TH - TL)/(Req)

Since I = I₁ + I₂

$$1/Req = 1/R₁ + 1/R₂$$

For series: Req = Σ Ri

For parallel: Req = (Σ 1/Ri)⁻¹

---



