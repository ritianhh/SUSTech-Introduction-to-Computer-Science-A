# Assignment 7
## 11510837 吴昊宇
-------------------
### 1. How many cells can be in a computer’s main memory if each cell’s address can be represented by two hexadecimal digits? What if four  are used? [4 marks]

> **ANSWER:**
>
> For 2 hexadecimal digits: it provide 32 bits, **2<sup>32</sup> = 4**GB, for cells, one cell is 8 bits so it can use **2<sup>32</sup> = 4294967296** cells.
>
> For 4 hexadecimal digits: it provide 64 bits, **2<sup>64</sup> = 1.844674407370955e+19** cells. (However, Windows 64 system can only support 192GB, the  cells can be in a computer’s main memory is also related to the Operating System).



### 2. What is the value of the most significant bit in the bit patterns represented by the following hexadecimal notations? [4 marks]

**a. 8F**   **b. FF** **c. 6F** **d. 1F**

>**ANSWER:**
>
>**a. 8F**  MSB is **1** 
>
>**b. FF** MSB is **1** 
>
>**c. 6F** MSB is **1** 
>
>**d. 1F** MSB is **1** 

### 3. Express each of the following values in binary notation: [4 marks]

**a. 5.75**  **b. 15.9375**  **c. 5.375** **d. 1.25**

> **ANSWER:**
>
> a. 5.75**   (101.11)<sub>b</sub>
>
> **b. 15.9375**  (1111.1111)<sub>b</sub> 
>
> **c. 5.375**  (101.011)<sub>b</sub> 
>
> **d. 1.25**  (1.01)<sub>b</sub> 

###  4. Suppose a digital camera has a storage capacity of 256MB. How many photographs could be stored in the camera if each consisted of 1024 pixels per row and 1024 pixels per column if eachpixel required three bytes of storage? [4 marks]

> **ANSWER:**
>
> 256MB = 256 * 1024KB/MB * 1024B/KB = 2<sup>8+10+10</sup> = 2<sup>28</sup>
>
> For each picture, it will occupies" 1024 * 1024 * 3 = 3 * 2<sup>20</sup>
>
> So in the storage, can store 2<sup>28</sup> / 3 * 2<sup>20</sup> = **85** pictures

### 5. The half-adder is an arithmetic circuit block by using this circuit block we can add wo bits. Ithas two inputs terminals and as well as two outputs terminals, with one producing the SUMoutput and the other producing the CARRY. Below figure shows the truth table of a half-adder,showing all possible input combinations and the corresponding outputs along with block. [4marks]

- ![avatar](https://github.com/ritianhh/SUSTech-Introduction-to-Computer-Science-A/blob/master/Assignment%207/image/Assignment7-5.png)



**a. Please write the relation between input and the SUM and CARRY outputs in Boolean expression.**

> **ANSWER:**
>
> ![](https://github.com/ritianhh/SUSTech-Introduction-to-Computer-Science-A/blob/master/Assignment%207/image/S.png)
>
> ![](https://github.com/ritianhh/SUSTech-Introduction-to-Computer-Science-A/blob/master/Assignment%207/image/C.png)

**b. Draw the circuit diagram of half adder using logic diagram symbol.**

> **ANSWER:**
>
> ![](https://github.com/ritianhh/SUSTech-Introduction-to-Computer-Science-A/blob/master/Assignment%207/image/half-add.png)



