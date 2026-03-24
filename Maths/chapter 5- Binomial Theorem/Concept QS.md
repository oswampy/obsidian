# **Q1:**
Find sum of coefficients of $x^{32}$ and $x^{-18}$ in expansion of $\left(2x^3 - \dfrac{3}{x^2}\right)^{14}$

**General term:**  
$T_{r+1} = \binom{14}{r} (2x^3)^{14 - r} \left(-\dfrac{3}{x^2}\right)^r$
$= \binom{14}{r} \cdot 2^{14 - r} \cdot (-3)^r \cdot x^{3(14 - r)} \cdot x^{-2r}$
$= \binom{14}{r} \cdot 2^{14 - r} \cdot (-3)^r \cdot x^{42 - 3r - 2r}$
$= \binom{14}{r} \cdot 2^{14 - r} \cdot (-3)^r \cdot x^{42 - 5r}$
We want $x^{42 - 5r} = x^{32}$  
$\Rightarrow 42 - 5r = 32$  
$\Rightarrow r = 2$

Also for $x^{-18}$:  
$42 - 5r = -18$  
$\Rightarrow r = 12$

Now find coefficients by substituting $r = 2$ and $r = 12$ into the general term.
### For $r = 12$:
$\binom{14}{12} \cdot 2^2 \cdot (-3)^{12}$  
$= \binom{14}{2} \cdot 4 \cdot 531441$
### For $r = 2$:

$\binom{14}{2} \cdot 2^{12} \cdot (-3)^2$  
$= \binom{14}{2} \cdot 4096 \cdot 9$
Now take the sum:
$\binom{14}{2} \cdot \left( 4096 \cdot 9 + 4 \cdot 531441 \right)$
$= \binom{14}{2} \cdot \left( 36864 + 2125764 \right)$  
$= \binom{14}{2} \cdot 2162628$
$\boxed{\binom{14}{2} 3^2 + 2^2(2^{10}  \cdot 3^{12})}$ 

---
# **Q2:**

Find values of $a$, $x$, $n$ if 2nd, 3rd and 4th terms in $(ax^2)^n$ are $240$, $720$, $1080$

Given:

$T_2 = 240$  
$T_2 = \binom{n}{1} a x^{n-1} = 240$
$T_3 = \binom{n}{2} a^2 x^{n-2} = 720$
$T_4 = \binom{n}{3} a^3 x^{n-3} = 1080$

$\dfrac{T_3}{T_2} = \dfrac{720}{240} = 3$

So:

$\dfrac{\binom{n}{2} a^2 x^{n-2}}{\binom{n}{1} a x^{n-1}} = 3$

$\Rightarrow \dfrac{\binom{n}{2}}{\binom{n}{1}} \cdot \frac{x}{a} = 3$ (re arranging powers)

## Use formula:    (only for mcqs)
$\dfrac{\binom{n}{r}}{\binom{n}{r - 1}} = \dfrac{n - r + 1}{r}$

$\dfrac{\binom{n}{2}}{\binom{n}{1}} = \dfrac{n - 1}{2}$
Thus:
$\Rightarrow \dfrac{n - 1}{2} \cdot \frac{x}{a} = 3 \quad \text{(1)}$


$\dfrac{T_4}{T_3} = \dfrac{1080}{720} = \dfrac{3}{2}$

So:

$\dfrac{\binom{n}{3} a^3 x^{n-3}}{\binom{n}{2} a^2 x^{n-2}} = \dfrac{3}{2}$  
$\Rightarrow \dfrac{\binom{n}{3}}{\binom{n}{2}} \cdot \frac{x}{a} = \dfrac{3}{2}$

Use identity again:

$\dfrac{\binom{n}{3}}{\binom{n}{2}} = \dfrac{n - 2}{3}$

$\dfrac{n - 2}{3} \cdot \frac{x}{a} = \dfrac{3}{2} \quad \text{(2)}$

Now divide Equation (1) by Equation (2):

$\dfrac{\dfrac{n - 1}{2}}{\dfrac{n - 2}{3}} = \dfrac{3}{\dfrac{3}{2}}$  (x/a cancels)

$\dfrac{n - 1}{2} \cdot \dfrac{3}{n - 2} = 2$
$3n - 3 = 4n - 8$  
$\Rightarrow \boxed{n = 5}$
putting 5 in (1)
$\frac{5-2}{3} \cdot \frac{x}{a}=\frac{3}{2}$
$x=\frac{3a}{2}$
putting x in $T_{2}$

$T_2 = \binom{5}{1} a^{5-1} \frac{3a}{2} = 240$
$5a^4\cdot \frac{3a}{4}=240$
$\boxed{a=2}$
puttin a in eq
$\boxed{x=3}$

---
# Q3:
For all positive integers $n$, show that:  $50^n - 49n - 1$ is divisible by $49^2$ $(50)^n = (1+49)^n$ $= \binom{n}{0}49^0 + \binom{n}{1}49^1 + \binom{n}{2}49^2 + \ldots$ $50^n = 1 + 49n + 49^2\left[\binom{n}{2} + \binom{n}{3}49 + \ldots + \binom{n}{n}49^{n-2}\right]$ $50^n - 49n - 1 = 49^2[\text{positive integer}]$ $\therefore$ it is a multiple of $49^2$ so it will be divisible by $49^2$ 

---
# Q4:
a) Term independent of $x$ in $\left(1 + 2x + \frac{2}{x}\right)^3$: $\left(1 + 2x + \frac{2}{x}\right)^3 = ^3C_0(1 + 2x)^3 + ^3C_1(1 + 2x)^2\left(\frac{2}{x}\right) + ^3C_2(1 + 2x)\left(\frac{2}{x}\right)^2$ $+ ^3C_3\left(\frac{2}{x}\right)^3$ $\Rightarrow$ Checking each term to be independent Last two terms won't cancel out '$x$'. 1st term - $1[1 + 8x^3 + 6x + 12x^2]$ = **1** is only independent of $x$ 
2nd term - $3[1 + 4x^2 + 4x] \cdot \frac{2}{x}$ 
$\frac{6}{x}[1+4x^2+4x]$
only if we multiply $\frac{6}{x}\; an d \;4x$ it will be independent of $x$, $\implies$ **24** is independant of x
both terms are being in expansion added so
independant term = 25


- also can set r = 0 if in **binomial** expansion when asked to find constant/independant of x term






# Q5:
Q) First 3 terms of $(8 - 5x)^{\frac{2}{3}}$

A)take 8 common to be in terms of $(1-x)^n$
$8^{\frac{2}{3}} \left(1 - \frac{5x}{8}\right)^{\frac{2}{3}}$

$8^{\frac{2}{3}} \left[ 1 + \frac{2}{3}x + \frac{\frac{2}{3}\cdot\left(-\frac{1}{3}\right)}{2!}x^2 \right]$

$4 \left[ 1 + \frac{2}{3}x - \frac{2}{9} \cdot \frac{1}{2} \left( -\frac{5x}{8} \right)^2 \right]$

$4 \left[ 1 + \frac{2}{3}\left( \frac{-5x}{8} \right) + \frac{1}{9} \cdot \frac{25x^2}{64} \right]$

$4 \left[ 1 - \frac{5x}{12} + \frac{25x^2}{576} \right]$

# Q6:
Q) Find coefficient of $x^{49}$ in $(x-1)(x-3)(x-5)(x-7)\dots(x-99)$

A) Total terms = $50$

If we multiply $(x-1)$ with all other terms, we will get a power of $x^{49}$.  
If we take any bracket and multiply $x^{49}$ common:  
$x^{49} \left[ -1 - 3 - 5 \dots -99 \right]$

$= -x^{49} \left( 1 + 3 + 5 + \dots + 99 \right)$ (n² sum of odd natural numbers)

$= -50^2 \cdot x^{49}$

$\Rightarrow -2500x^{49}$

# Q7:
Q) Find remainder when $64^{32^{32}}$ is divided by $9$

A) 

Let $t = 3^{3^{232}}$

$64^t \Rightarrow 8^{2t}$

$(9 - 1)^{2t}$ (taking $-1$ common)

$= (1 - 9)^t \quad \left[ \text{from } (1 - x)^n \right]$

$= \binom{t}{0} + \binom{t}{1} \cdot (-9) + \dots$

$= 1 + 9 \cdot \text{[some +ve integers]}$

$\therefore 1$ is the remainder.

# Q8:
in expansion of$(1+x)(1-x^2)\left(1+ \frac{3}{x} + \frac{3}{x^2} + \frac{1}{x^3}\right)\text{, sum of coeff. of } x^3 \text{ and } x^{-13} \text{ is:}$

$\text{Part a) } (1+x)(1-x^2)\left(1+ \frac{1}{x}\right)^{15}$

$(1+x)(1+x)(1-x)\left(1+ \frac{1}{x}\right)^{15}$

$= (1+x)^2(1-x)\left(\frac{x+1}{x} \right)^{15}$

$= \frac{(1+x)^{17}(1-x)}{x^{15}}$

$= \frac{(1+x)^{17} - x(1+x)^{17}}{x^{15}}$ (expanding numerator)

$\text{For } x^3 \text{ we need } x^{18} \text{ in numerator}$

$\text{For } x^{-13} \text{ we need } x^2 \text{ in numerator}$

$\text{Expand 2nd term in } -x(1+x)^{17}:$ (because even if we expand first term we wont get a power of 18)

$(1+x)^{17}\left[{}^{17}C_0 x^{17}\right] - x$
$(1+x)^{17} - 1 \cdot x^{18}$
$\text{Coeff of } x^{18} \text{ is } -1$
now we try to get coeff of $x^2$
$\frac{\left[{}^{17}C_{2} - {}^{17}C_1 x^2\right]}{x}$ (both terms can have a power of 2, and 2nd term is $^{17}C_{1}$because one x was alr taken out in ($-x(1+x)^{17}$))

${}^{17}C_2 - {}^{17}C_1 x^2$
$\text{Coeff of } x^{-13} \text{ is } 136$

$136 - 17 = 119 \text{ is coeff}$

$\text{Sum of coefficient is } 119 + (-1) = 118$





[[Binomial Theorem for integral n]]