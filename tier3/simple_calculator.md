**Problem**
Simple Calculator

**Steps**
1. Prompt user for the first number(input1).
2. check if input1 is a valid number.
3. if input1 is not a number display a message "invalid input Please enter a valid number" and go back to step 1.
4. if input1 is a valid number, Prompt user for input2.
5. check if input2 is a valid number.
6. if input2 is not a valid number, display a message "invalid input, please enter a valid number" and go back to step 4.
7. if input2 is valid number.
8. prompt user for operator they want to use (/, *, +, -).
9. if operator is "+" calculate: result = input1 + input2, display result
10. else if operator "-" calculate: result = input1 - input2, display result.
11. else if operator is "*" calculate: result = input1 * input2, display result.
12. if operator is "/", check:
    - if input2 == 0 display a message "cannot be divided by zero.
    - else calculate: result = input1 / input2, display result.
13. else (if user enter an unrecognised operator) display a message "Invalid operator".
14. end the program.