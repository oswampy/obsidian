if theres a q like find no of POSITIVE integer solutions of xyz = n then use this:

ex taking n as 24:
i) factorize 24: $2^{3}*3$
now the three numbers have to have some combination of these powers.
x= $2^{\alpha_{1}}3^{\beta_{1}}$
y=$2^{\alpha_{2}}3^{\beta_{2}}$
z=$2^{\alpha_{3}}3^{\beta_{3}}$
now multiplying
xyz=$2^{\alpha_{1}+\alpha_{2}+\alpha_{3}}3^{\beta_{1}+\beta_{2}+\beta_{3}}$
clearly $\alpha_{1}+\alpha_{2}+\alpha_{3}$=3 and $\beta_{1}+\beta_{2}+\beta_{3}$=1
using beggers method of $^{n+r-1}C_{r-1}$ (taking n as lhs of eqn and r as the no of alpha/beta) we multiply both selections.
no of possible positive solns is 10 x 3 = 30