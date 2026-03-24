$^nC_r =$ selection of $n$ objects from $r$ objects (grouping of $r$ objects)
    
- $^nC_r = \dfrac{n!}{r!(n-r)!}$
    
- $^nC_r = ^nC_{n-r}$
    
- if $^nC_x = ^nC_y$  
    i) $x+y = n$  
    ii) $x = y$
    
- $^nC_r + ^nC_{r-1} = ^{n+1}C_r$
    

**Example (a):** If $^{17}C_8 = ^{17}C_a$, find $^{n}C_{17}$.

$8+9 = n, ; n = 17$  
So, $^{17}C_{17} = 1$

---

## **Q1:** In how many ways can a team of 3 boys and 3 girls be grouped from 5 boys and 4 girls?

**A:** In selection, order doesn’t matter.

$^5C_3 \times ^4C_3 = 10 \times 4 = 40$

---

## **Q2:** In how many ways can a student choose a program of 5 courses if 9 courses are available and 2 specific courses are compulsory?

**A:** $^7C_3 = 35$

(Out of 9, two are compulsory. Out of 5, two are already selected.)

## Q3: A group consists of 4 girls and 7 boys. In how many ways can a team of 5 members be formed if

i) No girl  
ii) At least one boy and one girl  
iii) At least 3 girls

---


i) $^7C_5 = 21$

ii) $^{11}C_5 - ^7C_5 = 462 - 21 = 441$ (total-case where no boys are there, theres is no case with all girls since 4)

iii) $^4C_3 \cdot ^7C_2 + ^4C_4 \cdot ^7C_1 = 84 + 7 = 91$
(the r value has to add up to total number of members in a team. We are selecting from each with min being 3,so make cases.)


---
## Q4:There are 12 questions in the question paper of an examination, divided into two parts—Part I and Part II—with 5 and 7 questions respectively. A student must attempt at least 8 questions in total, choosing at least 3 from each part. In how many ways can the student select the questions?

T-12

$P_1 = 5, ; P_2 = 7$
n value has to add up to total questions and r has to add up to total value per section
$^5C_3 \times ^7C_2 = 10 \times 21 = 210$

$^5C_2 \times ^7C_3 = 10 \times 35 = 350$

$^5C_4 \times ^7C_1 = 5 \times 7 = 35$

So, $210 + 175 + 35 = 420$

---



## **Q5:**Question:** What is the number of ways of choosing 4 cards from a pack of 52 playing cards? In how many of these:

i) All four cards belong to the **same suit**  
ii) All four cards are from **four different suits**  
iii) All four cards are **face cards** (Jacks, Queens, Kings)  
iv) Two cards are **red** and two are **black**  
v) All four cards are of the **same color** (either all red or all black)**

$^{13}C_4 + ^{13}C_4 + ^{13}C_4 + ^{13}C_4 = 4 \cdot {^{13}C_4}$

(ii) $({^{13}C_1})^4$

(iii) $^{12}C_4$ – 4 out of 12 face

(iv) $(^{26}C_2)^2$

(v) $^{26}C_4 + ^{26}C_4 = 2 \cdot {^{26}C_4}$
**Note:** When they are dependent we multiply.


[[PNC basics]]