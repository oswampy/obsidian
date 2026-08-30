## Hydrolysis of Strong Base and Weak Acid

## Reaction:

$CH_3COO^- + H_2O \rightleftharpoons CH_3COOH + OH^-$

| Time       | Species concentrations |
| ---------- | ---------------------- |
| $t=0$      | Product-$C$            |
| $t=t_{eq}$ | Reactant-$C(1-h)$      |

Where $h << 1$

## Equilibrium Constants:

### Hydrolysis constant:

$K_h = \frac{[CH_3COOH][OH^-]}{[CH_3COO^-]}$

$K_h = \frac{Ch \times Ch}{C(1-h)} = \frac{Ch^2}{1-h}$

### Relationship between constants:

$K_h \times \frac{[CH_3COOH][OH^-]}{[CH_3COO-]}$
we multiply and divide by opposite ion of denominator so its an anion so we multiply by the cation ${H+}$ on both sides

$\frac{[OH^-][H^+]}{1} = K_w$

$\boxed{\therefore K_h = \frac{K_w}{K_a}}$

### Degree of hydrolysis:

$Ch^2 = \frac{K_w}{K_a}$

$h = \sqrt{\frac{K_w}{CK_{a}}}$

### pH calculation:

From $eq^n$, $Ch = [OH^-]$

$\therefore C \times \sqrt{\frac{K_w}{CK_a}} = \sqrt{\frac{K_wC}{K_a}}$

$pOH = -\log[OH^-]$ (taking log both sides)

$pOH = \frac{-1}{2}\left(\log K_w - \log C + \log K_a\right)$

$pOH = \frac{-1}{2}\left(pK_w - pK_a - \log C\right)$

$pOH = 7 + \frac{1}{2}(pK_a + \log C)$ where $pK_w = 14$

- **pH calculation:**
	$pH = 14 - pOH$
	
	$pH = 7 - \frac{1}{2}(pK_a + \log C)$
---

### Example Problem:

**Q)** Weak acid has $K_a = 10^{-5}$ M. It forms a salt $NaX$ on reaction with alkaline solution. What will be degree of hydrolysis of 0.1 M $sol^n$?

A)
$Ch^2 = \frac{K_w}{K_a}$

$h = \sqrt{\frac{K_w}{CK_a}}$

$h = \sqrt{\frac{10^{-14}}{10^{-5}(10^{-1})}}$
$h = \sqrt{10^{-8}}$
$h = 10^{-4}$
**% hydrolysis** = $100h = 0.01 \text{\%}$



---

# Hydrolysis of Weak Base and Weak Acid

## Reaction:

$NH_4^+ + CH_3COO^- + H_2O \rightleftharpoons CH_3COOH + NH_4OH$

|Time|Species concentrations|
|---|---|
|$t=0$|$C$|
|$t=t_{eq}$|$C(1-h)$|

### Hydrolysis constant:

$Kh = \frac{Ch \times Ch}{C(1-h) \times C(1-h)} = \frac{h^2}{(1-h)^2}$

If $h^2 << 1$: $\frac{1}{K_a} \times \frac{1}{K_b} = K_w$

$hh = \sqrt{\frac{K_w}{K_aK_b}}$

### pH calculation:

From $eq^n$:

$pH = [H^+] = \sqrt{\frac{K_wK_a}{K_b}}$

$pH = -\log\sqrt{\frac{K_wK_a}{K_b}}$

$pH = 7 + \frac{1}{2}(pK_a - pK_b)$


---

| Salt type | Example           | Nature                | pH                                   | $Degree\ of \ hydrolysis ( \alpha )$ |
| --------- | ----------------- | --------------------- | ------------------------------------ | ------------------------------------ |
| WASB      | $CH(_3)COONa$     | Basic                 | $( \tfrac12(pK_w + pK_a + \log C) )$ | $( \sqrt{\dfrac{K_w}{K_a,C}} )$      |
| SAWB      | $NH(_4)Cl$        | Acidic                | $( \tfrac12(pK_w - pK_b - \log C) )$ | $( \sqrt{\dfrac{K_w}{K_b,C}} )$      |
| WAWB      | $NH(_4)CH(_3)COO$ | Depends on (K_a, K_b) | $( \tfrac12(pK_w + pK_a - pK_b) )$   | $( \sqrt{\dfrac{K_w}{K_a,K_b}} )$    |
| SASB      | NaCl              | Neutral               | (7)                                  | (0)                                  |
 



---

# Buffer Solution

**Definition:** The $sol^n$ which resists the change in pH on dilution or with addition of small amt of acid.

## Types of Buffer:

### 1) Acidic Buffer ($pH < 7$)

Prepared by mixing weak acid with salt from a strong base

**Example:** $CH_3COOH + CH_3COONa$

### 2) Basic Buffer ($pH > 7$)

Prepared by mixing weak base with salt of strong acid

**Example:** $NH_4OH + NH_4Cl$

---

# Henderson-Hasselbalch Equation

If weak acid $HA$ ionize in water:

$HA + H_2O \rightleftharpoons H_3O^+ + A^-$

$K_a = \frac{[H_3O^+][A^-]}{[HA]}$

$[H_3O^+] = K_a\frac{[HA]}{[A^-]}$

$pH = pK_a - \log\frac{[HA]}{[A^-]}$

$pH = pK_a + \log\frac{[A^-]}{[HA]} (representation: \log\frac{[Salt]}{[Acid]})$

**Example:** If we prepare buffer $sol^n$ with acetic acid and sodium acetate, then $pK_a = 4.76$

**Note:** Volume × strength/Molarity = concentration



---

#  Concentrations of a multi step rxn
  
 

When a polyprotic acid (an acid that can donate more than one proton) is dissolved in water, it dissociates in successive steps, each with its own acid dissociation constant ($K_{a1}$, $K_{a2}$, $K_{a3}$, etc.).

For almost all practical calculations, the hydrogen ion concentration $[\text{H}^+]$ is determined solely by the first dissociation step ($K_{a1}$).

## 1. The General Rule: Focus on $K_{a1}$

Because $K_{a1} \gg K_{a2} \gg K_{a3}$ (usually by a factor of $10^4$ or more), the amount of $[\text{H}^+]$ produced by the second and third steps is entirely negligible. Furthermore, the $[\text{H}^+]$ produced in the first step shifts the equilibria of the subsequent steps to the left (via the common ion effect), suppressing them even further.

- Approximate Formula (if $c \gg K_{a1}$):  
    $$\mathbf{[\text{H}^+] \approx \sqrt{K_{a1} \cdot c}}$$  
    _(Where $c$ is the initial concentration of the polyprotic acid)._
- Exact Quadratic Formula (if the acid is dilute or $K_{a1}$ is relatively large):  
    $$[\text{H}^+]^2 + K_{a1}[\text{H}^+] - K_{a1}c = 0 \implies \mathbf{[\text{H}^+] = \frac{-K_{a1} + \sqrt{K_{a1}^2 + 4K_{a1}c}}{2}}$$

---

## 2. Concentration of Other Species at Equilibrium

If a problem gives you multiple $K_a$ values, it often asks for the concentrations of the intermediate or fully deprotonated anions. Once you know $[\text{H}^+] \approx \sqrt{K_{a1} \cdot c}$, you can use these shortcuts:

- For a Diprotic Acid ($\text{H}_2\text{A}$):
    
    - $[\text{H}_2\text{A}] \approx c - [\text{H}^+]$
    - $[\text{HA}^-] \approx [\text{H}^+]$
    - $[\text{A}^{2-}] \approx K_{a2}$ _(Remarkably, the concentration of the fully deprotonated anion is roughly equal to $K_{a2}$, completely independent of the acid concentration!)_
    
- For a Triprotic Acid ($\text{H}_3\text{A}$):
    
    - $[\text{H}_2\text{A}^-] \approx [\text{H}^+]$
    - $[\text{HA}^{2-}] \approx K_{a2}$
    - $[\text{A}^{3-}] \approx \frac{K_{a2} \cdot K_{a3}}{[\text{H}^+]}$
    

---

## 3. The Exception: When $K_{a2}$ Matters

The only common exception where you cannot ignore the subsequent steps is Sulfuric Acid ($\text{H}_2\text{SO}_4$).

- The first dissociation step is completely strong ($K_{a1} \to \infty$), so it releases $[\text{H}^+] = c$ instantly.
- The second step ($\text{HSO}_4^- \rightleftharpoons \text{H}^+ + \text{SO}_4^{2-}$) has a relatively large $K_{a2} \approx 1.2 \times 10^{-2}$.
- To find total $[\text{H}^+]$ for sulfuric acid, you set up an ICE table for the second step: $K_{a2} = \frac{(c + x)(x)}{c - x}$, where total $[\text{H}^+] = c + x$.

Do you have a specific polyprotic acid problem you are working on? If you share the values of $K_{a1}, K_{a2}$, and the initial concentration ($c$), I can calculate the exact $[\text{H}^+]$ and concentration of all species for you!