1. Rank of 'RANDOM'
Letters sorted: A, D, M, N, O, R

- First letter 'R': letters smaller than 'R' = 'A,D,M,N,O' → 5 choices. Each gives 5! words.  
    5×5! = 600.

- Second letter 'A' (prefix 'R'): remaining 'A,D,M,N,O'. Letters < 'A' = 0.  
    Add 0.
    
- Third letter 'N' (prefix 'RA'): remaining 'D,M,N,O'. Letters < 'N' = 'D,M' → 2×3! = 12.  
    Add 12.
    
- Fourth letter 'D' (prefix 'RAN'): remaining 'D,M,O'. Letters < 'D' = 0.  
    Add 0.
    
- Fifth letter 'O' (prefix 'RAND'): remaining 'M,O'. Letters < 'O' = 'M' → 1×1! = 1.  
    Add 1.
    
- Last letter 'M': add 0.
    

Include the word itself: +1.

Rank = 600 + 0 + 12 + 0 + 1 + 0 + 1 = 614.

In my own words:

select the letters from the alphabetically arranged group (aag) in order of the actual word.once we have a letter we check all the letters before it and keep that number in mind as **n** now we go back to the og word and fix that letter in its spot and count how many spaces left (**m**) and multiply $n*m!$

so in BRIGHT its arranged
B,G,H,I,R,T
1)select B
	there are no letters before it so n=0 ($n*m! =0$)
	s=0
2)select R
	there is G,H,I before it in aag(prefix is BR currently so ignore B) so n=3 and if we fix R we can see there are 4 spots left so 
	$3*4! =72$
	s=72
3)select I
	there is G,H before in aag so n=2 and if we fix in word theres m=3 spots available
	$2*3! =12$
	s=12
4)select G
	there is no letters before it since B is in prefix alr
	s=0
5)select H
	there is no letters before it since B,G is in prefix alr
	s=0
6)select T
	there is no letters before it since B,G,H,I,R is in prefix alr
	s=0
7)once were done we have to count BRIGHT as a word
	s=1
add up all the individual s we get the rank of **BRIGHT as 85**


---
# **double letters**---
## BALLOON
**Word:** BALLOON  
Letters (sorted): **A, B, L, L, N, O, O**

---
### Step 1: First letter 'B'

Smaller than 'B' = {A} → 1 letter  
Remaining = 6 letters with repeats (L ×2, O ×2, A, N)  
Arrangements =180  
Contribution = 1 × 180 = **180**  
Total = 180

### Step 2: Prefix 'BA'

Remaining = {L, L, O, O, N}  
Next letter = 'A'  
Smaller than 'A'? None  
Contribution = 0  
Total = 180

### Step 3: Prefix 'BAL'

Remaining = {L, O, O, N}  
Next letter = 'L'  
Smaller than 'L'? None (since 'A' is gone, 'B' used, and next left are L, O, N — only N, O are greater)  
Contribution = 0  
Total = 180

### Step 4: Prefix 'BALL'

Remaining = {O, O, N}  
Next letter = 'L'  
Smaller than 'L'? None  
Contribution = 0  
Total = 180


### Step 5: Prefix 'BALLO'

Remaining = {O, N}  
Next letter = 'O'  
Smaller than 'O' = {N} → 1 letter  
Arrangements = 2!1!=2\frac{2!}{1!} = 21!2!​=2  
Contribution = 2  
Total = 182

### Step 6: Prefix 'BALLOO'

Remaining = {N}  
Next letter = 'O'  
Smaller than 'O'? {N} → 1 letter  
Arrangements = 1! = 1  
Contribution = 1  
Total = 183

### Step 7: Full word 'BALLOON'

Add 1 for the word itself → **+1**

**Final Rank = 184** 
## another ex-SMALL
**Word:** SMALL  
Letters sorted: **A, L, L, M, S**

#### Step 1: First letter 'S'

Smaller than 'S' = {A, L, L, M} → 4 letters  
Remaining letters = 4 → 4!=244! = 244!=24  
But we divide by 2!2!2! (since 2 L’s repeat) → 24/2=1224/2 = 1224/2=12  
Contribution = 4 × 12 = **48**  
Total = 48

---

### Step 2: Prefix 'SM'

Remaining = {A, L, L} (sorted → A, L, L)  
Next letter = 'M'  
Smaller than 'M' = {A, L, L} → 3 letters  
Remaining = 3 → 3!=63! = 63!=6, divide by 2!2!2! → 3  
Contribution = 3 × 3 = **9**  
Total = 57

### Step 3: Prefix 'SMA'

Remaining = {L, L}  
Next letter = 'A'  
Smaller than 'A' = none → Contribution = 0  
Total = 57

### Step 4: Prefix 'SMAL'

Remaining = {L}  
Next letter = 'L'  
Smaller than 'L' = none → Contribution = 0  
Total = 57

---

### Step 5: Word 'SMALL'

Add 1 for the word itself → **+1**

✅ **Rank(SMALL) = 58**


[[PNC basics]]