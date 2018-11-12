# Assignment 8

## 11510837 吴昊宇

### Part I. Multiple choice, each of the following questions has only one correct answer

1. What is the composition of the CPU?[2 points]
   A. Control Unit
   B. ALU
   C. Control Unit, ALU and Register Unit
   D. Control Unit and ALU

   > **ANSWER: C**

2. Which part is NOT included in a fetch-execute cycle? [2 points]

   A. Fetch instruction
   B. Decode instruction
   C. Execute instruction
   D. Encode instruction

   > **ANSWER: D**

3. Which of the following descriptions of ROM is correct? [2 points]
   A. The contents in locations in ROM can be changed.
   B. Each cell in ROM can be directly accessed.
   C. The contents in ROM can be stored in a long time

   > **ANSWER: C**

4. Was Von Neumann architecture independently invented by von Neumann in 1940s？[2 points]
   A. Yes
   B. No

   > **ANSWER: B**

5. Most PC’s architecture of CPU is：[2 points]
   A. CISC
   B. RISC 

   > **ANSWER: A**

-------------------------------------------------------------------

### Part II

> #### a. The following are instructions written in the machine language described in [Appendix C.](https://github.com/ritianhh/SUSTech-Introduction-to-Computer-Science-A/blob/master/Assignment%208/image/Appendix%20C.png) Rewrite them in English.[6 points]
>
> ##### 1) 368A
>
> ##### 2) BADE
>
> ##### 3) 803C

**ANSWER:**

1) **368A**:   would cause the contents of register 6 to be placed in the memory cell whose address is 8A.

2)** BADE**:  would first compare the contents of register A with the contents of register 0. If the two were equal, the pattern DE would be placed in the program counter so that the next  instruction executed would be the one located at that memory address. Otherwise, nothing would be done and program execution would continue in its normal sequence.

3) **803C**:  would cause the result of ANDing the contents of registers 3 and C to be placed in register 0.

> #### b. Here are some instructions in English. Translate each of them into the machine language of Appendix C.[4 points]
>
> ##### 1) LOAD register number 3 with the hexadecimal value 56.
>
> ##### 2) ROTATE register number 5 three bits to the right.

**ANSWER:**

1) : 2356

2) : A503

