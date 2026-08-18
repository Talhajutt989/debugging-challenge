# debugging-challenge
how to find errors
Debugging Solution
Q1. What errors did you find?
Answer: I found 3 errors:
"mark" was used instead of "marks".
A colon : was missing after the if condition.
A string was concatenated with a number.
Q2. Why did these errors occur?

Answer:"mark" is not a valid key in the dictionary.
Python requires : after an if statement.
average is a number, so it cannot be directly joined with a string using +.
Q3. How did you fix them?
Answer:
Changed student["mark"] to student["marks"].
Added : after if average >= 50.
Used str(average) to convert the number into a string.
Q4. What is the correct output?
Answer:Ali passed
Average: 80.0
Ahmed passed
Average: 55.0
