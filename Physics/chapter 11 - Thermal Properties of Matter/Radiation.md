

All objects emit radiation continously at any temperature above absolute temperature. These are in the form of E.M waves and emitted due to vibration of charged particle.

Radiation emitted from higher temperature object will have higher frequency and lower λ and vice versa. These radiation will be reflected, refracted and contract like light. These will follow inverse square low

# Absorptive Power, Reflectivity, and Transmitivity

## Absorptive Power (a)

The ratio of energy absorbed by any material to radiation incident to it.


$$a = \frac{E_a}{E}$$

## Reflectivity (r)

The ratio of radiation reflected by any body to radiation incident on it


$$r = \frac{E_r}{E}$$

## Transmitivity (t)

The ratio of radiation transmitted through any body to radiation incident on it


$$t = \frac{E_t}{E}$$

---

## Energy Balance and Perfect Bodies

**Note:** Any radiation falling on any body will be either absorbed, transmitted or reflected.

Let E be amount of radiation incident on any body surface

$$ \quad E_r = rE \text{ will be reflected}$$ $$E_{oa} = aE \text{ will be absorbed}$$ $$E_{ot} = tE \text{ will be transmitted}$$
$$rE + aE + tE = E$$ $$a + r + t = 1$$

## • Perfect reflector

$$r = 1$$ $$a = t = 0$$

## • Perfect transmitter

$$t = 1$$ $$r = a = 0$$

---

# Black Body


$$a = 1$$

any body that absorbs all the radiation falling on it

## Properties of Black Body

- It is a perfect absorber and perfect emitter
    
- Black body will absorb all radiation incident on it, irrespective of wavelength
    
- Black body will emit radiation uniformly in all direction
    
- All black colored surfaces are black bodies But all black body are not black
    
- At a given temperature, black body will emit more radiant energy than any other body.
    

---

## Emissive Power, Emissivity, and Gray Body

## Emissive Power

Total energy emitted by any body per unit time per unit area of surface - unit $W/m^2$

## Emissivity ($\varepsilon$)

ratio of energy emitted by a body per unit time per unit time area to a black body at same temperature

$$\varepsilon = \frac{E(T)}{E_B(T)} \quad 0 \leq \varepsilon \leq 1$$

• $\varepsilon$ of black body is 1

## Gray body

Any body whose $\varepsilon$ remains constant with time

---

# Stefan's Law

At a particular temperature T, total radiation emitted by a black body per unit time per unit area of all possible wavelength is directly proportional to fourth power of absolute temperature

$$E_{tot} \propto T^4$$ 

$$E_{nt} = \sigma A \Delta t  T^4 \quad \text{(For a black body)}$$ $$\sigma = 5.67 \times 10^{-8} , W/m^2 \text{-} K^4$$

$$E_{nt} = \sigma \varepsilon A \Delta t  T^4 \quad \text{(For a Non-black body)}$$
OR
$$P = \sigma \varepsilon A   T^4 \quad \text{(For a Non-black body)}$$
# Spectral Emissive Power

Energy emitted by any body per unit area per unit time of a particular wavelength is called spectral Emissive Power of that body at that wavelength

$$E_\lambda = \frac{E}{\Delta t A}$$

$$e = \int_0^\infty e_\lambda d\lambda$$

# Wien's Displacement Law

At a given temperature, spectral emissive power will be maximum for a particular wavelength such that product of that wavelength and given temperature is constant

$$T \longrightarrow \lambda_1$$

$$T\lambda_{max} = b = 2.89 \times 10^{-3} , mK$$

$\lambda_{max}$ is wavelength at which spectral emissive power is max
---

# Newton's Law of Cooling

[Graph showing $e_\lambda$ vs $\lambda$ with three curves at different temperatures]

$$\lambda_3 > \lambda_2 > \lambda_1$$ $$T_1 > T_2 > T_3$$

For small difference in temperature between a body and its surrounding, the rate of cooling of the body is directly proportional to temperature difference and surface area exposed
#Derivation 
Energy emitted = $A\sigma \Delta t \varepsilon T_0^4$

Energy absorbed = $A\sigma \Delta t \varepsilon T_s^4$

$$dQ = A\sigma \varepsilon \Delta t (T_0^4 - T_s^4)$$

$$\Delta T = T_0 - T_s \quad (\text{cooling so } T_0 > T_s)$$

$$T_0 = T_s + \Delta T$$

$$\Delta Q = A\sigma \varepsilon \Delta t ((T_s + \Delta T)^4 - T_s^4)$$

$$\varepsilon \Delta Q = A\sigma \varepsilon \Delta t (T_s^4(1 + \frac{\Delta T}{T_s})^4 - T_s^4)$$

$$\Delta Q = A\sigma \varepsilon \Delta t (T_s^4(1 + \frac{4\Delta T}{T_s}) - T_s^4) \quad \text{(Binomial approximation)}$$

$$\Delta Q = A \varepsilon \sigma \Delta t (4 \Delta T \frac{T_s^3}{T_s})$$

$$\Delta Q = 4 A \varepsilon \sigma \Delta t T_s^3$$

---

$$\frac{\Delta Q}{\Delta t} = 4 A \varepsilon \sigma T_s^3 \quad -(i)$$

From calorimetry

$$\frac{dQ}{dt} = mc \frac{\Delta T}{dt} \quad -(ii)$$

$$(i) = (ii)$$

$$mc \frac{dT}{dt} = 4 A \varepsilon \sigma T_s^3 \Delta T$$

$$m \frac{dT}{dt} = \frac{4 A \varepsilon \sigma T_s^3}{mc} \Delta T$$

$$\frac{dT}{dt} = -K \Delta T \quad (\text{'-ve' as it is cooling})$$

$$\int_{T_i}^{T_f} \frac{dT}{\Delta T} = -K \int dt$$

$$\ln(T_f - T_s)\Big|_{T_i}^{T_f} = -K \Delta t$$

$$\ln(T_f - T_s) = -K \Delta t$$

$$T_f - T_s = (T_i - T_s)e^{-K\Delta t}$$

---

# Limitation of Newton's Law

- $\Delta T$ should be small
- There should be no loss of heat to conduction/convection
- Temp of surrounding must be constant

## Problem

**Q)** A body at 40°C temp is kept in 20°C temp. If the body cools down to 35°C in 10m, find how much more time it will take to cool to 30°C

**Solution:**

$$35 - 20 = (40 - 20)e^{-Kt}$$

$$or, \frac{\ln 4}{10} = K$$

now

$$\ln\left(\frac{30-20}{35-20}\right) = -\frac{1}{10}\ln 4 \cdot t$$

$$t = 10 \ln 2 - \ln 3$$

$$= \frac{\ln 3 - \ln 4}{t}$$

$$t = 14.06  \min$$
