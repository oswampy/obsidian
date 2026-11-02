
### 15.1 Introduction

Logic gates are electronic circuits that perform logical operations on binary inputs.

The two binary states are:

- 0 = LOW.
    
- 1 = HIGH.
    

### 15.2 AND Gate

The output is 1 only when all inputs are 1.

Boolean expression:

$Y=A\cdot B$

Truth table:

|A|B|Y|
|---|---|---|
|0|0|0|
|0|1|0|
|1|0|0|
|1|1|1|

### 15.3 OR Gate

The output is 1 when at least one input is 1.

Boolean expression:

$Y=A+B$

Truth table:

|A|B|Y|
|---|---|---|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|1|

### 15.4 NOT Gate

The NOT gate reverses the input.

Boolean expression:

$Y=\overline A$

Truth table:

|A|Y|
|---|---|
|0|1|
|1|0|

### 15.5 NAND Gate

The NAND gate is the inverse of the AND gate.

Boolean expression:

$Y=\overline{A\cdot B}$

Truth table:

|A|B|Y|
|---|---|---|
|0|0|1|
|0|1|1|
|1|0|1|
|1|1|0|

### 15.6 NOR Gate

The NOR gate is the inverse of the OR gate.

Boolean expression:

$Y=\overline{A+B}$

Truth table:

|A|B|Y|
|---|---|---|
|0|0|1|
|0|1|0|
|1|0|0|
|1|1|0|

### 15.7 XOR Gate — JEE Extension

The XOR gate produces 1 when the inputs are different.

Boolean expression:

$Y=\overline A B+A\overline B$

Truth table:

|A|B|Y|
|---|---|---|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|0|

### 15.8 XNOR Gate — JEE Extension

The XNOR gate produces 1 when the inputs are equal.

Boolean expression:

$Y=AB+\overline A\overline B$

Truth table:

|A|B|Y|
|---|---|---|
|0|0|1|
|0|1|0|
|1|0|0|
|1|1|1|

### 15.9 Universal Gates

NAND and NOR are called universal gates because any basic logic gate can be constructed using only NAND gates or only NOR gates.

**Using NAND gates:**

NOT:

$Y=A\ NAND\ A=\overline A$

AND:

$Y=(A\ NAND\ B)\ NAND\ (A\ NAND\ B)$

OR:

$Y=(A\ NAND\ A)\ NAND\ (B\ NAND\ B)$

**Using NOR gates:**

NOT:

$Y=A\ NOR\ A=\overline A$

OR:

$Y=(A\ NOR\ B)\ NOR\ (A\ NOR\ B)$

AND:

$Y=(A\ NOR\ A)\ NOR\ (B\ NOR\ B)$

### 15.10 De Morgan's Laws

First law:

$\overline{A+B}=\overline A\cdot\overline B$

Second law:

$\overline{A\cdot B}=\overline A+\overline B$

