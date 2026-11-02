

### 12.1 What Are Semiconductors?

Semiconductors are materials whose electrical conductivity lies between that of conductors and insulators.

Examples:

- Silicon (Si).
    
- Germanium (Ge).
    

Their conductivity can be controlled by temperature, doping and applied electric fields.

### 12.2 Energy Band Theory

In solids, individual atomic energy levels combine to form energy bands.

Important bands:

**Valence Band**

The highest energy band that is normally occupied by electrons.

**Conduction Band**

The energy band in which electrons can move freely and contribute to electrical conduction.

**Forbidden Energy Gap**

The energy gap between the valence band and conduction band.

### 12.3 Conductors, Semiconductors and Insulators

|Property|Conductors|Semiconductors|Insulators|
|---|---|---|---|
|Energy gap|Zero or overlapping bands|Small|Large|
|Conductivity|High|Intermediate|Very low|
|Temperature effect|Generally resistance increases with temperature|Conductivity generally increases with temperature|Generally remains low|
|Examples|Cu, Al|Si, Ge|Glass, rubber|

### 12.4 Intrinsic Semiconductors

An intrinsic semiconductor is a pure semiconductor without intentional impurity doping.

Examples: pure silicon and germanium.

Properties:

- Each atom forms four covalent bonds.
    
- At absolute zero, the ideal intrinsic semiconductor has no thermally generated free charge carriers.
    
- At higher temperatures, some electrons gain sufficient energy to enter the conduction band.
    
- Electron-hole pairs are produced.
    

For an intrinsic semiconductor:

$n_e=n_h=n_i$

Where:

- $n_e$ = electron concentration.
    
- $n_h$ = hole concentration.
    
- $n_i$ = intrinsic carrier concentration.
    

### 12.5 Electron-Hole Pair Formation

When a valence electron gains sufficient energy:

- It moves into the conduction band.
    
- A vacancy is left behind in the valence band.
    
- This vacancy behaves like a positive charge and is called a hole.
    

Both electrons and holes contribute to electrical conduction.

### 12.6 Extrinsic Semiconductors

Extrinsic semiconductors are formed by adding a small, controlled amount of impurity to a pure semiconductor.

This process is called doping.

There are two types:

1. n-type semiconductor.
    
2. p-type semiconductor.
    

### 12.7 n-Type Semiconductor

An n-type semiconductor is formed by doping silicon or germanium with a pentavalent impurity.

Examples:

- Phosphorus.
    
- Arsenic.
    
- Antimony.
    

Four electrons form covalent bonds with neighbouring atoms.

The fifth electron is loosely bound and can become a free electron.

Properties:

- Electrons are majority carriers.
    
- Holes are minority carriers.
    
- The impurity is called a donor impurity.
    

### 12.8 p-Type Semiconductor

A p-type semiconductor is formed by doping silicon or germanium with a trivalent impurity.

Examples:

- Boron.
    
- Aluminium.
    
- Gallium.
    

Only three covalent bonds can be completed, leaving a hole.

Properties:

- Holes are majority carriers.
    
- Electrons are minority carriers.
    
- The impurity is called an acceptor impurity.
    

### 12.9 Comparison of n-Type and p-Type Semiconductors

|Property|n-Type|p-Type|
|---|---|---|
|Dopant|Pentavalent|Trivalent|
|Majority carriers|Electrons|Holes|
|Minority carriers|Holes|Electrons|
|Impurity|Donor|Acceptor|
|Examples|P, As, Sb|B, Al, Ga|

**Important:** Both n-type and p-type semiconductors are electrically neutral overall.

### 12.10 p-n Junction

A p-n junction is formed when p-type and n-type semiconductor regions are joined together.

When the junction is formed:

- Electrons diffuse from n-side to p-side.
    
- Holes diffuse from p-side to n-side.
    
- Electrons and holes recombine near the junction.
    
- A depletion region is formed.
    
- Immobile ions create an internal electric field.
    

### 12.11 Depletion Region

The depletion region is the region near the junction that is depleted of mobile charge carriers.

It contains:

- Positive immobile donor ions on the n-side.
    
- Negative immobile acceptor ions on the p-side.
    

The internal electric field opposes further diffusion of majority carriers.

### 12.12 Barrier Potential

The potential difference developed across the depletion region is called the barrier potential.

It opposes the further diffusion of majority carriers.

Typical approximate values at room temperature:

- Silicon: $0.7\ V$.
    
- Germanium: $0.3\ V$.
    

These are approximate values, not fixed universal constants.

### 12.13 Forward Bias

A p-n junction is forward biased when:

- p-side is connected to the positive terminal.
    
- n-side is connected to the negative terminal.
    

Effects:

- Barrier potential decreases.
    
- Depletion layer becomes narrower.
    
- Majority carriers cross the junction more easily.
    
- Current increases significantly after the knee region.
    

### 12.14 Reverse Bias

A p-n junction is reverse biased when:

- p-side is connected to the negative terminal.
    
- n-side is connected to the positive terminal.
    

Effects:

- Barrier potential increases.
    
- Depletion layer becomes wider.
    
- Majority carrier current becomes very small.
    
- A small reverse saturation current flows due to minority carriers.
    

At sufficiently high reverse voltage, breakdown occurs.

### 12.15 V-I Characteristics of a p-n Junction Diode

**Forward bias**

- Current is initially small.
    
- Current increases rapidly after the knee voltage.
    
- Silicon has a typical knee voltage of approximately $0.7\ V$.
    
- Germanium has a typical knee voltage of approximately $0.3\ V$.
    

**Reverse bias**

- A small reverse saturation current flows.
    
- At breakdown voltage, reverse current increases sharply.
    

### 12.16 Diode Equation — JEE Extension

The current through an idealised p-n junction diode is described by:

$I=I_s\left(e^{qV/\eta k_BT}-1\right)$

Where:

- $I_s$ = reverse saturation current.
    
- $q$ = magnitude of electronic charge.
    
- $V$ = applied voltage.
    
- $\eta$ = ideality factor.
    
- $k_B$ = Boltzmann constant.
    
- $T$ = absolute temperature.
    

This equation explains the exponential increase in forward current.

---

## 13. Applications of Semiconductor Diodes

### 13.1 Diode as a Rectifier

A rectifier converts alternating current into unidirectional current.

There are two major types:

1. Half-wave rectifier.
    
2. Full-wave rectifier.
    

### 13.2 Half-Wave Rectifier

A half-wave rectifier uses one diode.

**Working:**

- During the positive half-cycle, the diode is forward biased and current flows.
    
- During the negative half-cycle, the diode is reverse biased and current is blocked.
    
- The output consists of only one half of the input waveform.
    

For an ideal half-wave rectifier:

Average DC output voltage:

$V_{dc}=\dfrac{V_m}{\pi}$

RMS output voltage:

$V_{rms}=\dfrac{V_m}{2}$

Ripple frequency:

$f_r=f$

### 13.3 Full-Wave Rectifier

A full-wave rectifier uses both halves of the AC input.

It can be constructed using:

- Two diodes and a centre-tapped transformer.
    
- Four diodes in a bridge configuration.
    

**Working:**

- During the positive half-cycle, one conducting path is established.
    
- During the negative half-cycle, a different conducting path is established.
    
- Current through the load remains in the same direction.
    

For an ideal full-wave rectifier:

Average DC output voltage:

$V_{dc}=\dfrac{2V_m}{\pi}$

RMS output voltage:

$V_{rms}=\dfrac{V_m}{\sqrt{2}}$

Ripple frequency:

$f_r=2f$

### 13.4 Comparison of Half-Wave and Full-Wave Rectifiers

|Property|Half-wave|Full-wave|
|---|---|---|
|Diodes|1|2 or 4|
|AC cycles used|One half|Both halves|
|Average output|$V_m/\pi$|$2V_m/\pi$|
|Ripple frequency|$f$|$2f$|
|Efficiency|Lower|Higher|
|Output smoothness|More ripple|Less ripple|

### 13.5 Filter Capacitor

A capacitor can be connected across the load to reduce fluctuations in the rectified output.

- It charges near the peaks of the rectified waveform.
    
- It discharges through the load between peaks.
    
- The output becomes smoother DC.
    

