$n(A∪B)=n(A)+n(B)−n(A∩B)$

if n(A) =3 and n(B) = 4

- **Maximum** Union of two sets
To maximize union we need to **minimize intersection**(aka disjoint sets)
so n(A∩B) = 0
n(AUB)= 3 + 4 - 0
**max** n(AUB) = 7

- **Minimum** Union of two sets
To minimize union we need to **maximize intersection**
the most elements A and B can have in common - min(n(A),n(B)) = min(4,3) = 3
n(AUB) = 4+3 -3
**min** n(AUB) = 4

- **Maximum** intersection of two sets
To maximize intersection we need the min value between both sets
min(4,3) = 3 
**max** n(A∩B) = 3
Because the intersection can never be more than the size of the smaller set.

- **Minimum** intersection of two sets
To minimize intersection we want no overlap between sets, so they are disjoint
 **min** n(A∩B) = 0
### Tips
n(A-B) = n(A)-n(A$\cap$B)

- to solve proving qs:
A-(BUC) = $A \cap (BUC)'$
A-B = $A\cap B'$
'-' becomes intersection and whatever is after is complemented
### Equivalent sets
two sets are said to be equivalent if n(A)=n(B)
A= {1,2,3,4}
B={4,3,6,5}
equal sets are always equivalent but equivalent sets may not be equal

### Power Sets
Let A = {1,2,{3,4},5} which are true:
- $\{3,4\}\subset A$ -F
- $\{3,4\}\in A$ -T
- $\{\{3,4\}\}\ \subset A$- T
- $2 \in A$ -T
belongs to $(\in)$ works only for elements and subset$(\subset)$ works only for sets