# **Turning of Object on Road**
-dia
	![[Turning_on_road.excalidraw]]
From diagram (cross-section of road):  
$f_s = f_c$ (**static friction** provides the centripetal acceleration)

$\mu_{s} N = \frac{mv^2}{R}$  
$\mu_{s} mg = \frac{mv^2}{R}$  
$v = \sqrt{\mu_{s} g R}$

- When a vehicle is moving on road, at the point of turning, the vehicle needs centripetal force which is provided by static friction.
    
- Since the static frictional force has a limit, the centripetal force will have some limit
---
**Q1:**  
A bike of $50, \text{kg}$ is moving on a curved plane road with $R = 20, \text{m}$ and $\mu_{s} = 0.5$. Find $v_{\text{max}}$

**Solution:**  
$v_{\text{max}} = \sqrt{20 \times 5 \times 10}$  
$v_{\text{max}} = 10, \text{m/s}$

$f_s = \mu_s N$  
$f_s = 0.5 \times 500$  
$f_s = 250 \text{N}$
---
# **Banking of Road**

To increase the maximum speed on a curved road, banking is done on the turning. Here, inner side of the road is at less height and outer side is at more height, which makes the road an inclined plane.
-dia
	![[Banking_road.excalidraw]]
From diagram:  
$N \sin \theta$ provides $f_c$  
$f_c = \frac{mv^2}{R} = N \sin \theta$

- If we increase velocity, $R$ will also have to increase because it is equal to $N \sin \theta$ which is always constant.
    
- If we increase velocity, we go upslope and $f_s$ acts downward.
- Friction will avoid the sliding of vehicle up or down

In vertical direction:  
$mg = N \cos \theta - f \sin \theta \quad \text{...(i)}$

In horizontal direction:  
$f_c = N \sin \theta + f \cos \theta$

For max value of $v$ ($f_{c}$), friction should be max, i.e., $f = \mu N$

$\frac{mv^2}{R} = N \sin \theta + \mu N \cos \theta \quad \text{...(ii)}$


divide (ii) by (i)
$mg = N \cos \theta - f \sin \theta = N (\cos \theta - \mu \sin \theta)$

So,  
$\frac{v^2}{Rg} = \frac{N (\sin \theta + \mu \cos \theta)}{N (\cos \theta - \mu \sin \theta)}$  
$\Rightarrow \frac{v^2}{Rg} = \frac{\sin \theta + \mu \cos \theta}{\cos \theta - \mu \sin \theta}$

Divide numerator and denominator by $\cos \theta$  
$\boxed{v_{\text{max}} = \sqrt{Rg \cdot \frac{\\tan \theta +\mu }{1 - \mu \tan \theta}}}$
 and
$\boxed{v_{\text{min}} = \sqrt{Rg \cdot \frac{\\tan \theta -\mu }{1 + \mu \tan \theta}}}$
[[Forces]]
