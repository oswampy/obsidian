-dia
	![[Circular_motion.excalidraw]]
	s-> linear displacement
	$\theta$-> angular displacement
	$\theta = \frac{arc}{radius} = \frac{S}{R}$ 
	$\theta$ is dimensionless ($M^0L^0T^0$)

- Angular displacement is an axial vector, direction is found by curling fingers in direction of movement, thumb gives direction of angular displacement

- Angular Velocity($\omega$) = $\frac{\Delta \theta}{\Delta t}$
	Instantaneous velocity($\omega$) = $\frac{d\theta}{dt}\lim_{ t \to 0 }$
		dimension is $M^0L^0T^-1$
	it is also an axial vector 

for very small displacement $s ->\Delta s$
then small angular displacement $\theta\to\Delta \theta$
$\Delta \theta = \frac{\Delta s}{\Delta t}$

$\omega=\frac{\Delta \theta}{\Delta t} \implies\frac{\Delta}{\Delta t}\left( \frac{S}{R} \right)\implies \frac{1}{R}\left( \frac{S}{R} \right)(velocity)$
$\boxed{\omega=\frac{V}{R}}$
- $V = R\omega$  (only true for circular motion,(**linear speed/velocity**))
- $\omega = \frac{V_{\perp}}{R}$  (V perpendicular, true for all cases always correct)

### Frequency
frequency is the no of revolutions made in 1 second
$1\; revolution = 2\pi$
$f\; revolutions=2\pi f$
for 1 second
$\boxed{\omega =2\pi f}$      (**angular speed/angular velocity**) (when no of revolutions is given)


### Time Period
time taken for revolution in one rotation
f revolutions-> 1 second
1 revolution->$\frac{1}{f}$
$T = \frac{1}{f}$
$\boxed{\omega = \frac{2\pi}{T}}$   (when time is given)

## Centripetal Acceleration
Since acceleration is rate of change of velocity, if velocity is same at all points then there can still be acceleration due to change in direction of velocity,called centripetal acceleration
-dia
	![[centripetal_acc.excalidraw]]
- Always acts towards center
- Vector quantity
$$a_{c} = \frac{V^2}{R}$$
(with radius)
we know $v= R\omega$
$$a_{c} = R\omega^2$$ (with angular velocity)
$a_{c} \perp V$ always 

## Tangential Acceleration
it is caused by the change in magnitude of velocity aka change in speed.
- it is also called angular acceleration
$|\vec{v|}$ is just speed, so differentiating will give us the acceleration which is responsible for only change in speed($a_{T}$)

If velocity increases, $a_{T} \parallel V$
if velocity decreases, $a_{T}\; anti\parallel V$ 
-Parallel acceleration:
$$a_{T} = \frac{d|V|}{dt}$$ (in vector form)
$$a_{T}=\alpha R$$ (with angular acceleration)
- vector quantity

## Net acceleration
whenever any particle travels in a circular path, it experiences both accelerations.
$\vec{v}$ is the complete velocity vector, it can be broken into two components which are $a_{c}$ and $a_{T}$.

$a_{net} = |\frac{d \vec{v}}{dt}|=\frac{d|\vec{v}|}{dt}+\frac{V^2}{R}$ (total change in velocity)

$\tan \alpha = \frac{ac}{at}$
$$a_{net} = \sqrt{ ac^2+at^2 }$$   (2abcos 90 is 0)
- if any random force is applioed on any particle then
	The $\perp$component will act as $a_{c}$
	The $\parallel$ component will act as $a_{T}$

# Dynamics Of Circular Motion 

**Centripetal Force**
	Force which is responsible for circular motion of the particle, whether uniform or not, by providing the centripetal acceleration is called centripetal force.
	$F_{c}=ma_{c}$
	$F_{c}=\frac{mV^2}{R}$

**Tangential Force**
	Force which is responsible for change in speed of particle is called tangential force
	$F_{T}=\frac{md|\vec{v}|}{dt}$

$F_{net}=F_{c}+F_{T}$

Note: centripetal force is not any independant force, but some other force will act like centripetal force. Ex- when the earth revolves around the sun, gravitational force acts as centripetal force and it replaces it

---
# Uniform circular acceleration
- speed remains constant
- only $a_{c}$ acts
- $a_{T} =0\implies \frac{d|\vec{v|}}{dt}=0\implies\frac{ dv \vec{}}{dt}(a_{net})=\frac{V^2}{R}$
- the angle between 2 lines = angle between their displacement
-derivation of $a_{c} = \frac{V^2}{R}$
	![[uniform_acc.excalidraw]]
	$\frac{ds}{r} = \frac{dV}{V_{2}} = \frac{dV}{V}$($|V|$ is constant)
	$\frac{ds}{rdt} = \frac{dV}{vdt}$(dividing by dt)
	$\frac{V}{r} = \frac{a_{c}}{V}$
	$a_{c} = \frac{V^2}{R}$

## Kinematic equations in circular motion
only applies in cases with **constant angular acceleration($\alpha$)**

$v = \omega,u=\omega_{o},a=\alpha,s=\Delta \theta$

1) $\omega = \omega_{o}+\alpha t$
2) $\omega^2=\omega_{o}^2+2\alpha\Delta \theta$
3) $\Delta \theta = \omega_{o}t+\frac{1}{2}\alpha t^2$

---
# Radius Of Curvature
The radius of the circular path on which the particle is moving is called radius of curvature. Circular path may be a complete circle or a part of it
$$R_{c}=\frac{V^2_{\perp}}{a_{c}}$$

(make a and V perpendicular components)
observation
	if velocity is more we need a larger radius to make a turn.
	more acceleration means less radius.

if a body is travelling with velocity u with angle theta to the horizontal then:
	$R_{c}=\frac{u^2}{g\cos \theta}$ initially.(since g needs to be $\perp$we use the cos component) 
	at highest point:
	$R_{c}=\frac{u^2\cos^2\theta}{g}$

---

# Motion in a Vertical Circle
-dia
	![[Motion_vertical_circle.excalidraw]]
	$F_{c}=mg\sin \theta+T$ (along radial direction of particle P)
	$\frac{mV^2}{R}=T+mg\sin \theta$


- At the highest point (B) magnitude of tension will be maximum because gravitational force is also acting as $a_{c}$
- $T_{min} \;at\; B$
- $T_{max}\;at\;D$



bl
[[Vectors]]
[[Differentiation]]
[[Motion in a plane]]