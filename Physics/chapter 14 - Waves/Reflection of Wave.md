

Wave travelling on string or any another medium when it hits a rigid support or obstacle and gets reflected back

1 - original wave $y = a\sin(\omega t - kx)$

2 - reflected wave $y = a\sin(\omega t + kx + \pi)$
if sign bw wt and kx is different then it is travelling in + x direction otherwise -x
# 1) Reflection from Rigid end
-dia
	![[pulse_string.excalidraw]]


- when pulse reaches right end clamped at wall - the right element will exert a force on the clamp and hence clamp will also exert equal and opposite force on it. this pulse goes in -ve x dir$^n$
    
- The incident and reflected pulse hence superimpose and displacement of particle on string will be found using superposition of wave.
    
- Displacement of particle at clamped end is 0
    
- If incident wave is
    
    $y_i = a\sin(\omega t - kx)$
    
    the reflected wave will be given as
    
    $y = a\sin(\omega t + kx + \pi)$
    
    $y = -a\sin(\omega t + kx)$
    
    $Y = y_i + y_r$
    
    $Y = a(\sin(\omega t - kx) - \sin(\omega t + kx))$
    
    $Y = -2a\cos(\omega t)\sin(kx)$
    

---

Here we can see that displacement of any particle on the string depends on position of particle and time

In the equation

$y = -2a\sin(kx)\cos(\omega t)$

if value of x y fixed then whole $-2a\sin(kx)$ is constant and for y becomes SHM where $-2a\sin(kx)$ is representing Amplitude

- Different point on string will do SHM with same frequency $\omega$ but different Amplitude
    
- Amplitude of Vibration of any particle at position x given by
    
    $A = 2a\sin(kx)$
    
    If $x = n\lambda$, $n = 0, 1, 2...$
    
    $A = 2a\sin(2\pi n)$
    
    $A = 0$

Velocity of particle:

$v_p = \frac{dy}{dt} = -2a\omega\sin(kx)\cos(\omega t)$

Strain: $\frac{dy}{dx} = -2ak\sin(kx)\cos(\omega t)$

stress $\Rightarrow dp$

Elasticity $= \frac{\text{stress}}{\text{strain}} = \frac{dp}{\frac{dy}{dx}}$

$dp = E\frac{dy}{dx}$

## Node:

When standing wave is on string or any other medium, the point which always remains at rest is called nodes

$\Rightarrow$ Amplitude $= 0$

$2a\sin(kx) = 0$

$kx = n\pi$

$x = \frac{n\lambda}{2}$ (A will be 0 if $x =$ integral multiple)

---

$v_p = \frac{2a\omega\sin(kx)d}{2}\sin(\omega t)$

$v_p = 0$

$y = 0$ - At nodal point

$A = 0$

### Antinode:

Points which vibrate with max amplitude are called antinode

$A = 2a\sin(kx)$

$A_{max} = 2a$

$\sin(kx) = 1$

$kx = \frac{(2n+1)\pi}{2}$

$x = \frac{(2n+1)\lambda}{4}$

$V_p = 2a\omega\sin(\omega t)$ - At antinode

$y = -2a\cos(\omega t)$

At node strain and stress are maximum while at antinode both are 0 (Because when you hold up a string the point on finger has no pressure (antinode))

---

# 2)Reflection of wave from free End

When wave will reach free end of any string the restoring force is missing at that point, so the displacement of right end will be more than height of pulse. due to this one wave will be reflected by free end without inversion

[Diagram showing wave reflection with equations:]

- $+ve$ x → $y_i = a_i\sin(\frac{\omega t - kx}{\omega t})$
- $y_i = a_i\sin(kx + \omega t)$
- $-ve$ x ←

After superimposition of incident and reflected wave: $Y = Y_i + Y_r$

$Y = a(\sin(\frac{\omega t - kx}{\omega t}) + \sin(kx + \omega t))$

$Y = 2a\sin(\omega t)\cos(kx)$
$A = 2a\cos(kx)$
$v_p = 2a\omega\cos(kx)\cos(\omega t)$
$\frac{dy}{dx} = -2ak\sin(kx)\sin(\omega t)$

$dp = E\frac{dy}{dx}$

### Node:

$A = 2a\cos(kx) = 0$
$kx = \frac{(2n+1)}{2}\pi$ $n \in (0,1,2...)$
$x = \frac{(2n+1)\lambda}{4}$
$v_p = 0$ $y = 0$

Node in free end is at same place as antinode of fixed end

### Antinode:

$A = 2a\cos(kx)$
$kx = n\pi$
$x = \frac{n\lambda}{2}$
$V_p = 2a\sin(\omega t)$ $2a\omega\cos(\omega t)$
$A_{max} = 2a$
$y = 2a\sin(\omega t)$