- An equation involving one or more trigonometric ratios of unknown angles is called a trigonometric equation

## solution of trigonometric equations
- Principle Solution: $[0,2\pi)$

- General solution: a formula or pattern for all possible solutions, ex: $(2n+1)\frac{\pi}{2}$

| Function                | angle    | General Solution                                               |
| ----------------------- | -------- | -------------------------------------------------------------- |
| $sin\theta$             | 0        | $\theta=n\pi$                                                  |
| $cos\theta$             | 0        | $\theta=(2n+1)\frac{\pi}{2}$                                   |
| $tan\theta$             | 0        | $\theta=n\pi$                                                  |
| $sin\theta = sin\alpha$ | $\alpha$ | $\theta=n\pi+(-1)^{n}\alpha$(n can be even or odd,2m and 2m+1) |
| $cos\theta=cos\alpha$   | $\alpha$ | $\theta=2n\pi \pm \alpha, \alpha \in [0,\pi]$                  |
| $tan\theta=\tan\alpha$  | $\alpha$ | $\theta = n\pi+\alpha$                                         |
General solutions of certain questions:

***Type 1***: $a\cos x+b\sin x = c$
How to solve: we multiply and divide by $\sqrt{ a^2+b^2 }$
Ex: $sinx +\sqrt{ 3 }\cos x = \sqrt{ 2 }$
$2\left( \frac{1}{2}sinx +\frac{\sqrt{ 3 }}{2}\cos x= \sqrt{ 2 } \right)$
$\sin\left( x+\frac{\pi}{3} \right)=\frac{1}{\sqrt{ 2 }}$
$\sin\left( x+\frac{\pi}{3} \right)=\sin\left( \frac{\pi}{4} \right)$
(gen solution for sine has two cases for when n is odd/even)
**Case 1: n is odd**
	$(-1)^n$ is -1
$x+\frac{\pi}{3}= n\pi-\frac{\pi}{4}$
$x=n\pi-\frac{7\pi}{12}$
**Case 2: n is even**
	$(-1)^n$ is 1
$x+\frac{\pi}{3}= n\pi+\frac{\pi}{4}$
$x =n\pi-\frac{\pi}{12}$
since we have both solutions we need to take intersection for final value
$\boxed{x\in \{n\pi-\frac{7\pi}{12}, n = odd\}\cup\{x =n\pi-\frac{\pi}{12},n =even\}}$

***Type 2***: Homogenous Solutions (making same power) 
$5\sin^2x-7\sin x\cos x+16\cos^x=4$
$5\sin^2x-7\sin x\cos x+16\cos^x=4(\sin^2x+\cos^2x)$ 
$\tan^2x-7\tan x+12$ (dividing by cos^2)
$\tan x = y$
$y^2-7y+12$
$(y-4)(y-3)$
$\tan x = 3,4$
$x = \tan^{-1}3,\tan^{-1}4$
$\boxed{x = n\pi +\tan^{-1}3 \;or \;n\pi+\tan^{-1}4}$

## solving equations with graph
- Q) find no of solutions of $\sin x = \frac{x}{10}$
A) $\sin x \in [-1,1]$
$-10\le x\le10$
now we can notice in the graph of sine $3\pi$ is about 9.42 which is just before 10 so it ranges from $-3\pi\; to\; 3\pi$
the second equation is a linear polynomial ($\frac{x}{10}$) and is in the range of the sine function so it intersects the sine graph
-dia
	![[graph_equations.excalidraw]]
	since the linear polynomial has to be a straight line passing through the origin, it will intersect certain points on the right side and same on the left + the origin
	**there are totally 7 points**

- Q) $\sin x\ge \frac{1}{2}$
-dia
	![[sine_q.excalidraw]]
	$\sin x \;is\; \frac{1}{2} \;at \frac{\pi}{6} and \frac{5\pi}{6}$
	we want only the green area above that, which repeats after every $2\pi$
	$x \in \cup\left[ 2n\pi+ \frac{\pi}{6}, 2n\pi + \frac{5 \pi}{6} \right]$


--- 
## Questions
1) if $K\cos x - 3\sin x = k+1$ find range of K
	$K\le{4}$
2) $\sqrt{ 3 }\sin \theta - \cos \theta = \sqrt{ 2 }$
	$\theta \in \{n\pi+\frac{5\pi}{12}, n = even\}\cup\{x =n\pi-\frac{\pi}{12},n =odd\}$
3) $\sqrt{ 2 }(\sin x+\cos x)=\sqrt{ 3 }$
	$x\in \{n\pi-\frac{7\pi}{12}, n = odd\}\cup\{x =n\pi+\frac{\pi}{12},n =even\}$
4) $\tan \theta + \sec \theta = \sqrt{ 3 }, \theta \in[0,2\pi]$
	when expanding the expression cos theta is in the denominator so eliminate any undefined ranges
	$\theta = \{\frac{\pi}{6}-n\pi\}$
5) $1+\sin^2\theta= 3\sin \theta \cos \theta$  
	$\theta =x = n\pi +\tan^{-1} \frac{1}{2} \;or \;n\pi+\tan^{-1}\frac{\pi}{4}$
6) $\cos4 \theta + \sin 5 \theta = 2$
	for this q both have to be 1 for it to be true to both max values, evaluate seperately, once u get both general solutions find value for n and m (the variable for cos and sine solutions) and take common value
7) $\sin x\le \frac{1}{\sqrt{ 2 }}$
8) $\cos x \ge -\frac{1}{2}$




bl
[[Trigonometry]]
[[Graphs of Trigonometric Ratios]]

