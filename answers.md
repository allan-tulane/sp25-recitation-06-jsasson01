# CMPS 2200 Recitation 06
## Answers

**Name:**_______Joshua Sasson________________
**Name:**__________Aaron Gershkovich___________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
W = W(n-1) +W(n-2) + O(1)
Level one: W= 1
level 2: W = 2
level 3: W = 4
this is leaf dominated W O(2^n) each level doubles work and there are n levels 

- **3)**
S = S(n-1) +S(n-2) + 0(1)
Level one: span of 1
level two span of 1
balanced 
S is O(n) since has to iterate through list decreasing n-1 at a time 

- **4)**
As n increases the counts of the lower numbers increases alot this is because as higher numbers are used
they all have to call fib(2) and fib(3) and so on so the higher the n the more the lower counts are repeated

- **6)**
the maximum times any fib will be called on a number n is one
this leads to a work of O(n) and since the algorithm iterates through the span is also O(n)

- **8)**
the maximum times a fib number will be computed is once this leads to a work of O(n) and since there is a iterative
for loop the span is also O(n)
