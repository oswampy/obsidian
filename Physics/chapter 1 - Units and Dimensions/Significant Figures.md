Rules for sigfigs:
1- all nonzero digits
	4.89 ->3 sigfigs
2-If zero is present between 2 sigfigs
	8.006 -> 4
3- if zero is written after decimal in end
	4.400 -> 4
4- Initial zero is insignificant
	0.0042 -> 2
5- Powers of 10 do not count
	6.43 x $10^4$ -> 3
6-when decimal is written it makes trailing and leading zeroes significant
	100 ->1 but 100.0 -> 4
7-constants have inf sigfigs
	c -> $\infty$

### Rounding Off
rounding off to x digits:
if digit after xth digit sigfig is:
	>5: +1 to previous digit and remove the *comparing* digit
		3.4*7* -> 3.5
	<5: remove the *comparing* digit
		3.4*1* -> 3.4
	=5:
		if no before 5 is:
		odd: +1 to previous digit and remove 5
			2.35-> 2.4
		even: keep the digits and remove 5
			2.45 -> 2.4

## Addition/Subtraction
Take the form with least sigfig digits after decimal
	8.31 +0.5 -> 8.8
## Multiplication/Division
Take overall least sigfigs
	0.34 x 10.1 -> 3.4'
	$\frac{0.48}{0.24}$ -> 2.0






bl

