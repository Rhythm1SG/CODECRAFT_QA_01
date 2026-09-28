# CodeCraft Infotech - Quality Assurance Internship

## Task 1: Test Cases for a Simple Calculator Application

### Objective
To create detailed test cases for a calculator application that performs addition, subtraction, multiplication, and division, focusing on valid and invalid inputs.

### Application Under Test
Demo Site: [PASTE DEMO SITE URL HERE]

### Test Cases

| Test Case ID | Test Description | Preconditions | Test Data | Test Steps | Expected Results | Priority | Actual Result | Status |
|---|---|---|---|---|---|---|---|---|
| TC-001 | Verify addition of two positive numbers | Calculator is open at the demo site | 10, 5 | 1. Enter 10 in the first field<br>2. Enter 5 in the second field<br>3. Select Addition (+)<br>4. Click Calculate | Result is displayed as 15 | High | | Not Executed |
| TC-002 | Verify subtraction of two positive numbers | Calculator is open at the demo site | 10, 5 | 1. Enter 10 and 5<br>2. Select Subtraction (-)<br>3. Click Calculate | Result is displayed as 5 | High | | Not Executed |
| TC-003 | Verify multiplication of two positive numbers | Calculator is open at the demo site | 10, 5 | 1. Enter 10 and 5<br>2. Select Multiplication (×)<br>3. Click Calculate | Result is displayed as 50 | High | | Not Executed |
| TC-004 | Verify division of two positive numbers | Calculator is open at the demo site | 10, 5 | 1. Enter 10 and 5<br>2. Select Division (÷)<br>3. Click Calculate | Result is displayed as 2 | High | | Not Executed |
| TC-005 | Verify addition with zero | Calculator is open at the demo site | 10, 0 | 1. Enter 10 and 0<br>2. Select Addition (+)<br>3. Click Calculate | Result is displayed as 10 | Medium | | Not Executed |
| TC-006 | Verify subtraction resulting in a negative number | Calculator is open at the demo site | 5, 10 | 1. Enter 5 and 10<br>2. Select Subtraction (-)<br>3. Click Calculate | Result is displayed as -5 | Medium | | Not Executed |
| TC-007 | Verify multiplication with zero | Calculator is open at the demo site | 10, 0 | 1. Enter 10 and 0<br>2. Select Multiplication (×)<br>3. Click Calculate | Result is displayed as 0 | Medium | | Not Executed |
| TC-008 | Verify division by zero | Calculator is open at the demo site | 10, 0 | 1. Enter 10 and 0<br>2. Select Division (÷)<br>3. Click Calculate | Error message "[EXACT MESSAGE FROM SITE, e.g. Cannot divide by zero]" is displayed and no numeric result is shown | High | | Not Executed |
| TC-009 | Verify addition using decimal numbers | Calculator is open at the demo site | 5.5, 2.5 | 1. Enter 5.5 and 2.5<br>2. Select Addition (+)<br>3. Click Calculate | Result is displayed as 8 | Medium | | Not Executed |
| TC-010 | Verify addition using negative numbers | Calculator is open at the demo site | -10, -5 | 1. Enter -10 and -5<br>2. Select Addition (+)<br>3. Click Calculate | Result is displayed as -15 | Medium | | Not Executed |
| TC-011 | Verify blank input fields | Calculator is open at the demo site | Both fields empty | 1. Leave both fields empty<br>2. Select any operation<br>3. Click Calculate | Message "[EXACT MESSAGE FROM SITE]" is displayed and no result is calculated | High | | Not Executed |
| TC-012 | Verify non-numeric input | Calculator is open at the demo site | abc, 5 | 1. Enter abc in the first field and 5 in the second<br>2. Select Addition (+)<br>3. Click Calculate | Input is rejected, message "[EXACT MESSAGE FROM SITE]" is displayed and no result is calculated | High | | Not Executed |
| TC-013 | Verify large numeric values | Calculator is open at the demo site | 999999999, 999999999 | 1. Enter 999999999 in both fields<br>2. Select Addition (+)<br>3. Click Calculate | Result is displayed as 1999999998 | Low | | Not Executed |
| TC-014 | Verify repeated calculation | Calculator is open at the demo site | First: 10, 5 (+). Second: 20, 4 (-) | 1. Calculate 10 + 5<br>2. Enter 20 and 4<br>3. Select Subtraction (-)<br>4. Click Calculate | Second result is displayed as 16 and is not affected by the previous result (15) | Medium | | Not Executed |
| TC-015 | Verify clear/reset functionality | Calculator is open at the demo site and has a Clear/Reset button | 10, 5 | 1. Enter 10 and 5<br>2. Click Calculate<br>3. Click Clear/Reset | Both input fields and the displayed result are cleared | Low | | Not Executed |
| TC-016 | Verify division with a decimal result | Calculator is open at the demo site | 10, 3 | 1. Enter 10 and 3<br>2. Select Division (÷)<br>3. Click Calculate | Result is displayed as 3.33 (or 3.3333...) | Medium | | Not Executed |
| TC-017 | Verify multiplication of two negative numbers | Calculator is open at the demo site | -4, -3 | 1. Enter -4 and -3<br>2. Select Multiplication (×)<br>3. Click Calculate | Result is displayed as 12 | Medium | | Not Executed |

### Conclusion

These 17 test cases cover valid and invalid inputs for the calculator's basic arithmetic operations. They also verify boundary conditions, validation, error handling, and reset functionality.
