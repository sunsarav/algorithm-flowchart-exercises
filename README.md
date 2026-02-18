Practice - Writing Pseudocode

Write a step by step pseudocode using plain text and logical structure.

Exercise 1: Find the Largest of Two Numbers

Write the pseudocode for a program that:

Takes two numbers A and B as input.

Compares the two numbers.

Displays which number is larger

If they are equal, display "Both numbers are equal".

1. Start
2. Input A and B
3. If A > B Then
	Display A
   If Else A == B
	Display "Equal"
   Else
	Display B
4. End

Exercise 2: Sum of 5 Numbers

Write pseudocode for a program that:

Reads 5 numbers one by one.

Calculates their total sum

Displays the result.

1. Start
2. Set i = 1,Sum = 0
3. While i <= 5 do
	Input num
	Sum = Sum + num
	i = i + 1
	End While
4. Display sum
5. End

Algorithm and Flowchart

Exercise 1

A program asks the user to enter their age.

If age is 18 or older, display: "You are eligible to vote."
If age is less than 18, display: "You are not eligible to vote."
End the program.

Pseudocode

START
    INPUT age
    IF age >= 18 THEN
        PRINT "You are eligible to vote."
    ELSE
        PRINT "You are not eligible to vote."
    ENDIF
END

Exercise 2

A program takes student marks (0–100).

90 and above → Grade A
75–89 → Grade B
50–74 → Grade C
Below 50 → Fail

Pseudocode

START
    INPUT marks
    IF marks >= 90 THEN
        PRINT "Grade A"
    ELSE IF marks >= 75 THEN
        PRINT "Grade B"
    ELSE IF marks >= 50 THEN
        PRINT "Grade C"
    ELSE
        PRINT "Fail"
    ENDIF
END

Exercise 3

A program that:

Prompts user to enter 5 numbers
Keeps a running total
Displays the sum
Ends program

Pseudocode

START
    total = 0
    REPEAT 5 TIMES
        INPUT number
        total = total + number
    ENDREPEAT
    PRINT "Total sum = ", total
END

Exercise 4

A program that:

Takes A, B, C as inputs
Finds the largest
Displays result
Ends program

Pseudocode

START
    INPUT A
    INPUT B
    INPUT C
    IF A >= B AND A >= C THEN
        PRINT "A is largest"
    ELSE IF B >= A AND B >= C THEN
        PRINT "B is largest"
    ELSE
        PRINT "C is largest"
    ENDIF
END