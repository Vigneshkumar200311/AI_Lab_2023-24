# Ex.No: 5   Logic Programming – Factorial of number   
### DATE: 9\3\2024                                                                            
### REGISTER NUMBER : 212221060305
### AIM: 
To  write  a logic program for finding the factorial of given number using SWI-PROLOG. 
### Algorithm:
1. STEP 1: Start the program
2. STEP 2:  Write a rules for finding factorial of given program in SWI-PROLOG.
3.   a)	factorial of 0 is 1 => written as factorial(0,1).
4.   b)	factorial of number greater than 0 obtained by recursively calling the factorial    function.
5. STEP 3: Run the program  to find answer of  query.
6. STEP 4: Stop the program.

### Program:
```
factorial(0,1).
factorial(A,B) :-  
           A > 0, 
           C is A-1,
           factorial(C,D),
           B is A*D.
```


### Output:
![WhatsApp Image 2024-03-23 at 15 14 49_bd9aa606](https://github.com/Vigneshkumar200311/AI_Lab_2023-24/assets/160318706/1555f8a0-9ef7-4529-bb28-ae0a5dc3fabb)



### Result:
Thus the factorial of given number was found by logic programming. 
