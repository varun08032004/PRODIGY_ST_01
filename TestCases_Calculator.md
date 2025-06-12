# Calculator Test Cases – Addition, Subtraction, Multiplication, Division

Test Case ID: TC_CALC_001
Test Description: Add two positive integers
Preconditions: Calculator app is open
Test Steps:

Input 5

Press +

Input 3

Press =
Expected Result: Display shows 8

Test Case ID: TC_CALC_002
Test Description: Subtract a positive number from a negative number
Preconditions: Calculator app is open
Test Steps:

Input -10

Press -

Input 4

Press =
Expected Result: Display shows -14

Test Case ID: TC_CALC_003
Test Description: Multiply two decimal numbers
Preconditions: Calculator app is open
Test Steps:

Input 2.5

Press ×

Input 4.2

Press =
Expected Result: Display shows 10.5

Test Case ID: TC_CALC_004
Test Description: Divide a decimal number by a whole number
Preconditions: Calculator app is open
Test Steps:

Input 7.5

Press ÷

Input 2

Press =
Expected Result: Display shows 3.75

Test Case ID: TC_CALC_005
Test Description: Handle BODMAS expression (e.g., 2 + 3 × 4)
Preconditions: Calculator supports operator precedence
Test Steps:

Input 2

Press +

Input 3

Press ×

Input 4

Press =
Expected Result: Display shows 14 (multiplication before addition)

Test Case ID: TC_CALC_006
Test Description: Add negative and decimal numbers
Preconditions: Calculator app is open
Test Steps:

Input -3.5

Press +

Input 2.25

Press =
Expected Result: Display shows -1.25

❌ Invalid Input Test Cases
Test Case ID: TC_CALC_007
Test Description: Division by zero
Preconditions: Calculator app is open
Test Steps:

Input 5

Press ÷

Input 0

Press =
Expected Result: Display shows Error or Infinity or Cannot divide by zero

Test Case ID: TC_CALC_008
Test Description: Input non-numeric characters
Preconditions: Calculator app allows character input (e.g., via keyboard)
Test Steps:

Input A

Observe behavior
Expected Result: Calculator ignores the input or shows an Invalid Input error

Test Case ID: TC_CALC_009
Test Description: Multiple decimal points in a number
Preconditions: Calculator app is open
Test Steps:

Input 5..2

Press +

Input 1

Press =
Expected Result: Display shows Error or ignores second decimal

Test Case ID: TC_CALC_010
Test Description: Empty input followed by operation
Preconditions: Calculator app is open
Test Steps:

Press +

Input 4

Press =
Expected Result: Display shows Error or treats missing operand as 0

Test Case ID: TC_CALC_011
Test Description: Press equals without any input
Preconditions: Calculator app is open
Test Steps:

Press =
Expected Result: Display shows 0 or no change

