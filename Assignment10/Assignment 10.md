# Assignment 10

## 11510837 吴昊宇

### 1. A Python function **Modify** is defined by

```python
def Modify (Y):
	Y= Y * 3
	print(X)
	print(Y)
```

Suppose that X is a global variable.

#### (a) If parameters are passed by value, what will be printed when the following program segment is executed? [2pts]

#### (b) What if parameters are passed by reference? [2pts]

```python
X= 5
Modify(X)
print(X)
```

> **ANSWER:**
>
> a.  If parameters are passed by value, the output will be 
>
> > 5
> >
> > 15
> >
> > 5
>
> b.  if parameters are passed by reference, the output will be 
>
> >15
> >
> >15
> >
> >15

### 2. What will be the output of the following C code? Explain your answer.[2pts]
![](https://github.com/ritianhh/SUSTech-Introduction-to-Computer-Science-A/blob/master/Assignment10/image/10.2.png)

> **ANSWER:**
>
> The output will be **900**. cuz sqr(X) is defined that calculate X * X, in the  C code, k =sqr( 20 +10) will first calculate 20 + 10, get **30**, then **sqr(30)** will be **30 * 30**, so the value of **k** will be **900.** in **printf("%d", k )** will print the value of k, so the output will be **900** .

### 3. Suppose the function f expects two numeric values as its inputs and returns their addition as its output value, and g is a function that returns the subtraction of the two values given as its input. If a and b represent numeric values, what is the result returned by f(f(a,b), g(a,b))? [2pts] 
> **ANSWER:**
>
> **f(a, b) = a + b;**
>
> **g(a, b) = a - b;**
>
> **f(f(a,b), g(a,b)) = f((a+b), (a - b)) = (a+b) + (a - b) = a + b + a - b = 2a**

### 4. Summarize the following rat’s-nest routine with a single if-else statement:[2pts]

```
	if X > 5 then goto 80
	X = X +1
	goto 90
80  X = X +2
90  stop
```
> **ANSWER:**
>
> ```
> if(X > 5){
> 	X = X + 2;
> }else X = X +1;
> ```

