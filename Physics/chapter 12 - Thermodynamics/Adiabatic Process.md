
## Definition

**Adiabatic Process**: When heat exchange between system and surrounding in a process is 0, then we call it an adiabatic process.

Heat exchange will be 0 if the process is sudden so have no time to exchange heat or when container is thermally insulated.

## Equations

$$\Delta u = -w$$

(If gas in doing work then its $\Delta u$ will decrease)

### Equation of adiabatic process:

$$PV^{\gamma} = k \text{ (constant)}$$

$$P^{1-\gamma}T^{\gamma} = k_1$$

$$V^{\gamma-1}T = k_2$$

(Different constants $\gamma$ are not related)

### Finding slope of $PV^{\gamma} = k$:

$$\frac{dPV^{\gamma}}{dV} = -PV \cdot V^{\gamma-1} dV \quad \text{(diff w.r.t } V\text{)}$$

$$\frac{dP}{dV} = -\gamma(P)$$

---

## Slope of PT

$$P^{1-\gamma}T^{\gamma} = k_1$$

$$\gamma T^{\gamma-1}P^{1-\gamma} = -P^{-\gamma}T^{\gamma}(1-\gamma) \frac{dP}{dT}$$

$$\frac{dP}{dT} = \frac{-\gamma P^{-3}T^{\gamma-1}}{P^{-3}T^{\gamma}(1-\gamma)}$$

$$\frac{dP}{dT} = \frac{\gamma P T^{-1}}{(\gamma-1)}$$

$$\frac{dP}{dT} = \frac{\gamma}{(\gamma-1)} \cdot \frac{P}{T}$$

---

## Slope of VT

$$TV^{\gamma-1} = k_3$$

$$T(\gamma-1)V^{\gamma-2}dV = -V^{\gamma-1}dT$$

$$\frac{dV}{dT} = \frac{-V}{T(\gamma-1)}$$

$$\frac{dV}{dT} = \frac{V}{T(1-\gamma)}$$

(negative slope because $\gamma > 1$ so $1-\gamma < 0$)

[Small sketch showing negative slope on VT graph]

---

## Work done in adiabatic process

$$\Delta w = -\Delta u$$

$$dw = -nC_v dT$$

Integrating:

$$\Delta w = -nC_v \Delta T \quad \text{(If } C_v \text{ and } \Delta T \text{ known)}$$

$$P\Delta V = -nC_v \Delta T$$

$$\frac{\Delta V}{\partial T} = \frac{-nC_v}{P}$$

$$\frac{V}{T(1-\gamma)} = \frac{-nC_v}{P}$$

---

## Work in Pressure-Volume terms:

$$w = \int P dV$$

$$PV^{\gamma} = k$$

$$P = \frac{k}{V^{\gamma}}$$

$$w = k \int dV \cdot V^{-\gamma}$$

$$w = \frac{k V^{1-\gamma}}{(1-\gamma)} \bigg|_{V_i}^{V_f}$$

$$w = \frac{k}{(1-\gamma)} \cdot V_f^{1-\gamma} - V_i^{1-\gamma}$$

$$w = \frac{P_fV_f - P_iV_i}{\gamma - 1}$$

$$w = \frac{nR\Delta T}{1-\gamma}$$

---

## Problem

A container having slightly conducting walls has air at $T_i = 47°C$, $V_i = 400 \text{ cm}^3$

Find rise in $\Delta T_i$ if gas is compressed to $V_f = 200 \text{ cm}^3$, $\gamma (\gamma_{\text{air}}) = 1.4$ or $7/5$

i) Compressed quickly in short time  
ii) Long time ($\Delta T = 0$)

$$\frac{T_1}{V_1^{\gamma-1}} = \frac{T_2}{V_2^{\gamma-1}}$$

$$370 \times 1.3 \approx T_2$$

$$476 = T_2$$

$$\Delta T = 96 \text{ K}$$