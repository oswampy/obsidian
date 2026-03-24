- Arranging $n$ objects around a circle  
    $\rightarrow (n-1)!$
    
    One object has to be fixed and $(n-1)$ then arranged.  
    ★ When using $(n-1)!$, only do so once per question (reference object already set).
    
- If in **necklace** or **garland**, it is symmetric, so we consider half  
    $\rightarrow \dfrac{1}{2}(n-1)!$
    

---

- **Selection of one or more objects from $n$ different objects**  
    $\rightarrow 2^n - 1$


- **Selection of 0 or more objects from $n$ identical objects**  
    $\rightarrow n + 1$ ways
    
    At least one $\rightarrow n$ ways
---


**Q1.**  A person is permitted to select at least one and at most $n$ coins from $(2n+1)$ different coins.  
If the total number of ways in which he can select coins is $255$, find $n$.

A:  
$^{2n+1}C_1 + {}^{2n+1}C_2 + {}^{2n+1}C_3 + \dots + {}^{2n+1}C_n = 255$ (given)

We know,  
${}^{2n+1}C_0 + {}^{2n+1}C_1 + \dots + {}^{2n+1}C_{2n+1} = 2^{2n+1}$  
$2[ {}^{2n+1}C_1 + \dots + {}^{2n+1}C_{2n+1}]+2 = 2^{2n+1}$
and the terms form symmetric pairs.

So,  
$2 \times 255 + 2 = 2^{2n+1}$  
$512 = 2^{2n+1}$  
$2n + 1 = 9$  
$n = 4$

**Q2.**  Given $N = 35700$, find:  
(i) Number of divisors  
(ii) Proper divisors  
(iii) Even divisors  
(iv) Odd divisors  
(v) Sum of all divisors

**Solution:**  
$35700 = 2^2 \times 3^1 \times 5^2 \times 7^1 \times 17^1$

Selecting at least one from similar objects:  
$(2+1)(1+1)(2+1)(1+1)(1+1)$  
$= 72$

(i) Number of divisors = $72$

(ii) Proper divisors → exclude $1$ and $35700$  
$= 72 - 2 = 70$

(iii) Number of even divisors  
For even divisors, the power of 2 can be $2^1$ or $2^2$ (not $2^0$),  
so:  
$2 \times (1+1)(2+1)(1+1)(1+1)$  
$= 48$

(iv) Odd divisors  
$= \text{Total} - \text{Even} = 72 - 48 = 24$

(v) Sum of all divisors is the product of sums of powers:  
$(2^0 + 2^1 + 2^2)(3^0 + 3^1)(5^0 + 5^1 + 5^2)(7^0 + 7^1)(17^0 + 17^1)$=124992