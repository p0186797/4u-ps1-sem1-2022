# 4u-ps1-sem1-2022

Create a java file called **ProblemSet.java** and upload it to this repo. For each program, do not have any extraneous print statements i.e. no prompts. The output must be exact.

---

Inside that file create a class called **GradeQuestion**.

Write a program that reads grades from the user until the user enters QUIT. It outputs the average as a letter grade.

If 80 <= grade <= 100 then the letter grade is A.

If 70 <= grade <= 79 then the letter grade is B.

If 60 <= grade <= 69 then the letter grade is C.

If 50 <= grade <= 59 then the letter grade is D.

If 0 <= grade < 50 then the letter grade is F.

&nbsp;&nbsp; **Sample Input 1**

    50
    43
    23
    89
    QUIT

&nbsp;&nbsp; **Sample Output 1**

    D

&nbsp;&nbsp; **Sample Input 2**
    
    89
    90
    100
    99
    QUIT

&nbsp;&nbsp; **Sample Output 2**

    A
   
---

Inside that file create a class called **LifePathQuestion**.

Write a program that reads 1 line of input from the user in the form: DD-MM-YYYY and outputs the user's life path number.

To calculate their life path number - add all the digits together. If the result is greater than 11, repeat the process.

For example suppose the user entered 11-29-1999.

1 + 1 + 2 + 9 + 1 + 9 + 9 + 9 = 41

41 is greater than 11 so I add its digits together.

4 + 1 = 5

I stop because 5 is less than or equal to 11.

The user's life path number is 5.

&nbsp;&nbsp; **Sample Input 1**

    11-29-1999

&nbsp;&nbsp; **Sample Output 1**

    5

&nbsp;&nbsp; **Sample Input 2**

    01-02-2001

&nbsp;&nbsp; **Sample Output 2**

    6
    
---

Inside that file create a class called **NumberSystemQuestion**.

Write a program that reads two lines from the user. The first line will be some sequence of characters. The second line will be a base number between 2 and 10. Your program outputs if the first line is a valid number in the given base. A number in base n where n is between 2 and 10 is a number that only uses digits 0 to n - 1, inclusive.

For example, a base 5 number will use digits 0 to 4. So 1234 could be a base 5 number but 2345 can't be a base 5 number.

&nbsp;&nbsp; **Sample Input 1**

    123455
    6

&nbsp;&nbsp; **Sample Output 1**

    yes
    
&nbsp;&nbsp; **Sample Input 2**

    52738
    8

&nbsp;&nbsp; **Sample Output 2**

    no
    
&nbsp;&nbsp; **Sample Input 2**

    52AA8
    10

&nbsp;&nbsp; **Sample Output 2**

    no
    
---

