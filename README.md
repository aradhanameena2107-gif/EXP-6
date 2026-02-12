AIM: Study of conditional statemens in python

THEORY:

Conditional statements in Python are used to make decisions based on given conditions. They allow a program to execute different blocks of code depending on whether a condition is true or false.
Python mainly uses if, elif, and else statements for decision-making.



1. if Statement

The if statement checks a condition and executes the block of code only if the condition is true.
Example use cases in this experiment include checking whether a number is positive, even, or a leap year.

2. if–else Statement

The if–else structure provides two paths of execution—one when the condition is true and another when it is false.

3. if–elif–else Ladder

The elif (else if) statement is used when multiple conditions need to be checked sequentially.

4. Relational and Logical Operators

Relational operators (>, <, >=, <=, ==) and logical operators (and, or, not) are used to form conditions.

5. User Input and Output

The input() function is used to take data from the user, and print() is used to display the results. Type conversion functions like int() and float() ensure correct calculations.

ALGORITHM:

6.1 - Check Whether a Number is Positive, Negative, or Zero

1. Start

2. Input a number num

3. If num > 0, print "Positive"

4. Else if num < 0, print "Negative"

5. Else print "Zero"

6. Stop

6.2 - Check Whether a Number is Even or Odd

1. Start

2. Input a number num

3. If num % 2 == 0, print "Even"

4. Else print "Odd"

5. Stop

6.3 - Find the Largest of Three Numbers

1. Start

2. Input three numbers a, b, c

3. If a >= b and a >= c, print "a is largest"

4.Else if b >= a and b >= c, print "b is largest"

5. Else print "c is largest"

6. Stop

6.4 - Grade Based on Marks

1. Start

2. Input marks

3. If marks ≥ 90, assign Grade A

4. lse if marks ≥ 75, assign Grade B

5. Else if marks ≥ 50, assign Grade C

6. Else assign Grade F

7. Print grade

8. Stop

6.5 - verage Grade of Three Subjects

1. Start

2. Input marks of three subjects

3. Calculate average = (m1 + m2 + m3) / 3

4. If average ≥ 90, Grade A

5. Else if average ≥ 75, Grade B

6. Else if average ≥ 50, Grade C

7. Else Grade F

8. Print average and grade

6.6 - Leap Year Check

1. Start

2. Input year

3. If year is divisible by 400 → Leap Year

4. Else if year is divisible by 4 and not divisible by 100 → Leap Year

5. Else → Not a Leap Year

6. Stop

6.7 - Vowel or Consonant Check

1. Start

2. Input a character

3. If character is in (a, e, i, o, u, A, E, I, O, U)

4. Print "Vowel"

5. Else print "Consonant"

6. Stop

6.8 - Salary Calculation with Allowances

1.Start

2. Input basic salary

3. If basic ≤ 10,000

     HRA = 20% of basic

     DA = 80% of basic

4. Else if basic ≤ 20,000

     HRA = 25%

     DA = 90%

5. Else

    HRA = 30%

    DA = 95%

6. Gross Salary = Basic + HRA + DA

7. Print Gross Salary

8. Stop

6.9 - Income Tax Calculation

1. Start

2. Input annual income

3. If income ≤ 2,50,000 → Tax = 0

4. Else if income ≤ 5,00,000 → Tax = 5%

5. Else if income ≤ 10,00,000 → Tax = 20%

6. Else → Tax = 30%

7. Calculate tax amount

8. Print tax

9. Stop

6.10 - Date Validation and Next Date

1. Start

2. Input date in dd/mm/yyyy format

3. Separate day, month, year

4. Check if month is valid (1–12)

5. Check valid days for each month

6. If invalid → Print "Invalid Date"

7. Else

      - Increase day by 1

      - If day exceeds month limit, set day = 1 and increase month

      - If month exceeds 12, set month = 1 and increase year

8. Print next date

9. Stop

CONCLUSION:

This experiment helped in understanding and implementing conditional statements in Python for decision-making. By solving real-life problems using if, if-else, and if-elif-else, we learned how to control program flow based on different conditions. It improved logical thinking and programming skills.

11. Stop
