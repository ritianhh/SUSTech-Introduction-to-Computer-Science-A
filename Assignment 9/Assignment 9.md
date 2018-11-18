

# Assignment 9 

## 11510837 吴昊宇

### 1.In each of the following cases, write a short program in the machine language described in   Appendix C to perform the requested activities. Assume that each of your programs is placed in memory starting at address 00.[6 points] 

​	a. Move the value at memory location D8 to memory location B3. 

​	b. Interchange the values stored at memory locations D8 and B3. 

​	c. If the value stored in memory location 44 is 00, then place the value 01 in memory location 46; otherwise, put the value FF in memory location 46. 

> **ANSWER:**
>
> **a. 4D8B3**
>
> **b. AD8B3**
>
> **c. 846440**

###  2. Perform the indicated operations.[2 points] 

​	a.             11111111 

​		OR   00101101 

​	b.             01001011 

​		XOR 10101011 

> **ANSWER:**
>
> **a. 11111111**
>
> **b.  11100000**

### 3.What is the result of performing a 1-bit left circular shift on the following bytes represented in hexadecimal notation? Give your answer in hexadecimal form.[8 points] 

​	a.  AB  

​	b.  5C  

​	c.  B7 

​	d.  35

> **ANSWER:**
>
> 

###   4.Using the machine language of Appendix C, write a program that copies the middle 4 bits from memory cell E0 into the least significant 4 bits of memory cell E1, while placing 0s in the most significant 4 bits of the cell at location E1. [4 points] 

> **ANSWER:**
>
> ```
> 15E0    // EO -> R5
> A502    // R5 right move 2 bits
> 260F    // 0F -> R6  0000 1111
> 8056    // R5 AND R6 -> R0
> 30E1    // R0 -> E1
> C000    
> ```
>
> 

​	



