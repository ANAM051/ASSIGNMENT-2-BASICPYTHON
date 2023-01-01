```python
1.	Two values of Boolean data types are True and False.
True value indicate the information is correct and False value indicates the 
information is incorrect
```


```python
2.	Three different types of Boolean operators are AND, OR , NOT .
```


```python
3. Truth table for AND:
   INPUT A        INPUT B           OUTPUT A AND B
    0              0                  0 (FALSE)
    0              1                  0 (FALSE)
    1              0                  0  (FALSE)
    1              1                  1 (TRUE)
    
  
    
```


```python
Truth table for OR :
    INPUT A               INPUT B         OUTPUT A OR B
    0                       0                  0 (FALSE)
    0                       1                  1  (TRUE)
    1                       0                  1 (TRUE)
    1                       1                  1  (TRUE)
```


```python
Truth table for NOT:
    INPUT                  OUTPUT 
    0                        1        
```


```python
4.	False
False
True
False
False
True

```


```python
5.	Six comparison operators are;
Equal to (==)
Not equal to (!=)
Less than (<)
Greater than ( >)
Less than or equal to ( <= )
Greater than or equal to ( >= )

```


```python
6.	Equal to used to perform comparison operations  eg 
(i) 12 == 13
It will return false
(ii) “gate” == “gate”
It will return true
 assignment operator is used to assign values to a variable .eg a = 10,
    b = ineuron

```


```python
7.. Identify the three blocks in this code:
spam = 0
if spam == 10:
print('eggs')
if spam > 5:
print('bacon')
else:
print('ham')
print('spam')
print('spam')
 
ANS:

print('ham')
print('spam')
print('spam')
      
```


```python
#8. Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is 
#stored in spam, and prints Greetings! if anything else is stored in spam.
def anam (spam):
    if spam == 1:
        print ("Hello")
    elif spam == 2:
        print("Howdy")
    else:
        print("Greetings!")
    return
anam(1)
anam(2)
anam(3)
```

    Hello
    Howdy
    Greetings!
    


```python
#9.If your programme is stuck in an endless loop, what keys you’ll press?
#ANS : I will press "i" key two times ,to interrupt the kernel and it will stop executing the code if 
it is in endless loop, this is for jupyter notebook. for other than jupyter notebook CTRL + C  is used to get out of endless
loop.

```


```python
#10. How can you tell the difference between break and continue?
 ANS : break and continue both are jump statements and work differrently.
    break is used for the immediate termination of the loop.If break is used in 
    a loop,it will stop its iteration and come out of the loop.
    continue transfers the control to the next iteration of the loop.
```


```python
#11.In a for loop, what is the difference between range(10), range(0, 10), and range(0, 10, 1)?
ANS.
There is no difference between these ,all will gave the same output.
range(10) , means upper bound is 10 ,which is excluded,the default lower bound  is o ,and default jump is 1.
range (0,10), means upper bound is 10 ,lower bound is 0 ,which is included and default jump is 1.
range(0,10,1),means upper bound is 10,lower bound is 0 and jump is 1.
```


```python
#12. Write a short program that prints the numbers 1 to 10 using a for loop. Then write an equivalent
program that prints the numbers 1 to 10 using a while loop.
```


```python
for i in range (10):
    print (i+1)
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    


```python

```


```python
i = 0
while i<10:
    print (i+1)
    i == 1
```


```python
#13. If you had a function named bacon() inside a module named spam, how would you call it after
importing spam?

ANS :
    import spam
        spam.bacon()
```


```python

```
