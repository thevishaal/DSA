# Data Structure & Algorithms in Python

**Data** - information  
**Structure** - Array, Linked List, Stack, Queue, Tree, Graph  
**Algorithm** - Set of instructions

# Time Complexity

Video link - [Youtube](https://youtu.be/QUX18Ba9cd8?si=BvZpP4O-9Un5pB_a)

## Comparison 

> 1 < log log n < n < n<sup>2</sup> < n <sup>3</sup> < ......  < 2 <sup>n</sup>...  
n = size of input , if n is very large

## Mathematical Equation

1. Constant equation :-  ex:- x = 5 
2. Linear equation :- ex:- y = 2x+5
3. Quadratic equation :- ex:- y = 2x<sup>2</sup>+3x-5 
4. Cubic equation :- ex:- y = 3x<sup>3</sup>-2x<sup>2</>-5
5. Logarithmic equation ex:- y = log x + 3
6. Exponatial equation :- ex:- 3<sup>x</sup>+3

## Types of Analysis

1. Best Case:- $\Omega$   -> Omega notation
2. Average Case:- $\theta$ -> Theta notation 
3. Worst Case:- $O()$ -> Big O-notation

### for worst case
1. Constant Time Complexity:-  $O(1)$
    ex :-  
    ~~~python  
    n = 10
    print(n)
    ~~~
2. Linear Time Complexity:- $O(n)$  
    ex :-  
    ~~~python
    n = 5
    print(n)
    for i in range(0,n):
        print(i)
    for j in range(0,n):
        print(j*j)
    for k in range(0,n/2):
        print("Hello")
    ~~~
3. Quadratic Time Complexity:- $O(n^2)$  
    ex :-  
    ~~~python 
    n = 5
    m = 10
    print(n+m)
    for i in range(0,n):
        for j in range(0,m):
            print("Helo")

    for k in range(0,n):
        print("Welcome") 
    ~~~
4. Cubic Time Complexity:- $O(n^3)$  
    ex :-  
    ~~~python
    n = 5
    m = 10
    print(n+m)
    for i in range(0,n):
        for j in range(0,m):
            for k in range(0,n):
                print("Welcome")
    
    for l in range(0,n):
        print("Hello")
    ~~~
5. Logarithmic Time Complexity:- $O(log n)$  
    ex 1:-  
    ~~~python
    n = 10
    while (n>=1):
        print("Hello")
        n = n//2
    ~~~
    ex 2:-
    ~~~python
    n = 1
    while (i<10):
        print("Hello")
        i = i*2
    ~~~
    #### for test purpose code :-
    ~~~python
    n = 10
    print(n)
    for i in range(0,n):
        print("Hello")

    for j in range(0,n):
        for k in range(o,n):
            print("Chai Aur Code")

    while (n>=1):
        print("Hitesh Sir & Prateek Sir")
        n = n//2
    ~~~
    **Time Complexity :- $O(n^2)$** 