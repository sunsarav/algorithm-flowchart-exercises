Practice - Writing Pseudocode

Write a step by step pseudocode using plain text and logical structure.

Exercise 1: Find the Largest of Two Numbers

1. START
2. INPUT A and B
3. IF A > B THEN
	DISPLAY A
   If Else A == B
	DISPLAY "Equal"
   ELSE
	DISPLAY B
4. END

Exercise 2: 

1. START
2. SET i = 1,Sum = 0
3. WHILE i <= 5 do
	INPUT num
	Sum = Sum + num
	i = i + 1
	END WHILE
4. DISPLAY sum
5. END

Practice - Algorithm and Flowchart

Exercise 1

A program asks the user to enter their age.

If age is 18 or older, display: "You are eligible to vote."
If age is less than 18, display: "You are not eligible to vote."
End the program.

Pseudocode

1. START
2. INPUT age
3. IF age >= 18 THEN
    PRINT "You are eligible to vote."
    ELSE
    PRINT "You are not eligible to vote."
    ENDIF
4. END

<img width="551" height="581" alt="vote drawio" src="https://github.com/user-attachments/assets/d851b907-e552-4ed4-a35d-169906c344fc" />


Exercise 2

A program takes student marks (0–100).

90 and above → Grade A
75–89 → Grade B
50–74 → Grade C
Below 50 → Fail

Pseudocode

1. START
2. INPUT marks
3. IF marks >= 90 THEN
    PRINT "Grade A"
    ELSE IF marks >= 75 THEN
        PRINT "Grade B"
    ELSE IF marks >= 50 THEN
        PRINT "Grade C"
    ELSE
        PRINT "Fail"
    ENDIF
4. END

Exercise 3

A program that:

Prompts user to enter 5 numbers
Keeps a running total
Displays the sum
Ends program

Pseudocode

1. START
2. sum = 0
3. REPEAT 5 TIMES
4. INPUT num
    sum = sum + num
    ENDREPEAT
5. PRINT "Total sum = ", sum
6. END

Exercise 4

A program that:

Takes A, B, C as inputs
Finds the largest
Displays result
Ends program

Pseudocode

1. START
2. INPUT A
3. INPUT B
4. INPUT C
5. IF A >= B AND A >= C THEN
    PRINT "A is largest"
    ELSE IF B >= A AND B >= C THEN
    PRINT "B is largest"
    ELSE
    PRINT "C is largest"
    ENDIF
6. END
