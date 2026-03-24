Permutation $\rightarrow$ Arrangement
$^nP_r =$ arrangement of $n$ different objects taken $r$ at a time

$^nP_r = \dfrac{n!}{(n-r)!}$

$^nC_r = \dfrac{^nP_r}{r!}$

---

## Q) Find value of $n$

i) $^nP_5 = 42 \cdot {}^nP_3 \quad (n > 4)$
	A)$\dfrac{n!}{(n-5)!} = 42 \cdot \dfrac{n!}{(n-3)!}$
	
	$\dfrac{(n-1)(n-2)(n-3)}{1} = 42$
	
	$n^2 - 4n - 3n + 12 - 42 = 0$
	$n^2 - 7n - 30 = 0$
	$n^2 - 10n + 3n - 30 = 0$
	$n(n-10) + 3(n-10)$
	$(n-10)(n+3) = 0$
	$n = 10$
(ii)$\dfrac{^nP_4}{^{n-1}P_4} = \dfrac{5}{3}$

$n-1 \geq 4$
$n \geq 5$
$\dfrac{n!}{(n-4)!} \cdot \dfrac{(n-1-4)!}{(n-1)!} = \dfrac{5}{3}$

$\dfrac{n}{(n-4)} = \dfrac{5}{3}$

$3n = 5(n-4)$
$3n = 5n - 20$
$n = 10$

---

## Q2) Find $r$ if $5\cdot^4P_r = {}6\cdot^5P_{r-1}$

$\dfrac{5\cdot4!}{(5-r)!} = \dfrac{6\cdot5!}{(5-(r-1))!}$

$\dfrac{5\cdot4!}{(5-r)!} = \dfrac{6\cdot5!}{(6-r)!}$

$\dfrac{5}{(4-r)!} = \dfrac{30}{(6-r)!}$

$(6-r)(5-r)=6$
$r^2-11r+24=0$
$r=8,3$
$r=3$ ($r \ne 8$ because it cannot be greater than n)



# **GAP Method**

How many ways 6 girls and 3 boys be seated so no two boys are together

$x , G_1 , x , G_2 , x , G_3 , x , G_4 , x , G_5 , x , G_6 , x$

Girls arranged in $6!$ ways

Boys can be placed in $x$ spots so ${}^7P_3$

$\Rightarrow 6! \times {}^7P_3 = 151200$

---

Permutations of objects which are repeated or not distinct

Take total no. of objects and divide by no. of repeating objects

$\dfrac{n!}{p_1! p_2! \dots p_m!}$

where $n =$ total objects, $p_1, p_2, \dots$ are repeating letters of different kinds


ROOT → $\dfrac{4!}{2!}$

ALLAHABAD → $\dfrac{9!}{4! \cdot 2!}$

---

## **Ex-16**: find no of arrangements of letters in 'INDEPENDENCE'

$E = 4$, $D = 2$, $N = 3$

Total $= 12$ letters

$\dfrac{12!}{3! \cdot 4! \cdot 2!} = 1663200$

---

i)if P is fixed in the beginning 
$P$ is fixed so $11$ left

$\dfrac{11!}{4! \cdot 3! \cdot 2!}$

ii)all vowels occur together
$5$ vowels = $1$ object

Total $= 7+1 = 8$ objects

$\dfrac{8!}{3! \cdot 2!} \times \dfrac{5!}{4!}$ 

In $8$ objects, $N$ and $D$ repeat ($E$ is repeated in other object). Inside vowel box we can arrange in $5!$ but $E$ repeats.

iii)where vowels dont occur together

$\dfrac{12!}{3! \cdot 4! \cdot 2!} - \Big( \dfrac{8!}{3! \cdot 2!} \times \dfrac{5!}{4!} \Big)$

iv)if vowels I and P are fixed beginning and end respectively
$\dfrac{10!}{3! \cdot 4! \cdot 2!}$

v) $I$ and $P$ at extreme

$\dfrac{10!}{3! \cdot 4! \cdot 2!} \times 2$

