# CodeCraft Infotech - Quality Assurance Internship

## Task 1: Test Cases for a Simple Calculator Application

### Objective
To create detailed test cases for a calculator application that performs addition, subtraction, multiplication, and division, focusing on valid and invalid inputs.

### Application Under Test
Demo Site: https://rhythm1sg.github.io/CODECRAFT_QA_01/

Tested on: Google Chrome (Windows), 28 September 2026

### Test Cases

| Test Case ID | Test Description | Preconditions | Test Data | Test Steps | Expected Results | Priority | Actual Result | Status |
|---|---|---|---|---|---|---|---|---|
| TC-001 | Verify addition of two positive numbers | Calculator is open at the demo site | 10, 5 | 1. Enter 10 in the first field<br>2. Enter 5 in the second field<br>3. Select Addition (+)<br>4. Click Calculate | Result is displayed as 15 | High | Result: 15 | Pass |
| TC-002 | Verify subtraction of two positive numbers | Calculator is open at the demo site | 10, 5 | 1. Enter 10 and 5<br>2. Select Subtraction (-)<br>3. Click Calculate | Result is displayed as 5 | High | Result: 5 | Pass |
| TC-003 | Verify multiplication of two positive numbers | Calculator is open at the demo site | 10, 5 | 1. Enter 10 and 5<br>2. Select Multiplication (×)<br>3. Click Calculate | Result is displayed as 50 | High | Result: 50 | Pass |
| TC-004 | Verify division of two positive numbers | Calculator is open at the demo site | 10, 5 | 1. Enter 10 and 5<br>2. Select Division (÷)<br>3. Click Calculate | Result is displayed as 2 | High | Result: 2 | Pass |
| TC-005 | Verify addition with zero | Calculator is open at the demo site | 10, 0 | 1. Enter 10 and 0<br>2. Select Addition (+)<br>3. Click Calculate | Result is displayed as 10 | Medium | Result: 10 | Pass |
| TC-006 | Verify subtraction resulting in a negative number | Calculator is open at the demo site | 5, 10 | 1. Enter 5 and 10<br>2. Select Subtraction (-)<br>3. Click Calculate | Result is displayed as -5 | Medium | Result: -5 | Pass |
| TC-007 | Verify multiplication with zero | Calculator is open at the demo site | 10, 0 | 1. Enter 10 and 0<br>2. Select Multiplication (×)<br>3. Click Calculate | Result is displayed as 0 | Medium | Result: 0 | Pass |
| TC-008 | Verify division by zero | Calculator is open at the demo site | 10, 0 | 1. Enter 10 and 0<br>2. Select Division (÷)<br>3. Click Calculate | Error message "Cannot divide by zero." is displayed and no numeric result is shown | High | Message "Cannot divide by zero." displayed; no numeric result shown | Pass |
| TC-009 | Verify addition using decimal numbers | Calculator is open at the demo site | 5.5, 2.5 | 1. Enter 5.5 and 2.5<br>2. Select Addition (+)<br>3. Click Calculate | Result is displayed as 8 | Medium | Result: 8 | Pass |
| TC-010 | Verify addition using negative numbers | Calculator is open at the demo site | -10, -5 | 1. Enter -10 and -5<br>2. Select Addition (+)<br>3. Click Calculate | Result is displayed as -15 | Medium | Result: -15 | Pass |
| TC-011 | Verify blank input fields | Calculator is open at the demo site | Both fields empty | 1. Leave both fields empty<br>2. Select any operation<br>3. Click Calculate | Message "Please enter both numbers." is displayed and no result is calculated | High | Message "Please enter both numbers." displayed; no result calculated | Pass |
| TC-012 | Verify non-numeric input | Calculator is open at the demo site | abc, 5 | 1. Enter abc in the first field and 5 in the second<br>2. Select Addition (+)<br>3. Click Calculate | Input is rejected, message "Please enter valid numbers only." is displayed and no result is calculated | High | Input rejected; message "Please enter valid numbers only." displayed; no result calculated | Pass |
| TC-013 | Verify large numeric values | Calculator is open at the demo site | 999999999, 999999999 | 1. Enter 999999999 in both fields<br>2. Select Addition (+)<br>3. Click Calculate | Result is displayed as 1999999998 | Low | Result: 1999999998 | Pass |
| TC-014 | Verify repeated calculation | Calculator is open at the demo site | First: 10, 5 (+). Second: 20, 4 (-) | 1. Calculate 10 + 5<br>2. Enter 20 and 4<br>3. Select Subtraction (-)<br>4. Click Calculate | Second result is displayed as 16 and is not affected by the previous result (15) | Medium | Second result: 16; not affected by the previous result | Pass |
| TC-015 | Verify clear/reset functionality | Calculator is open at the demo site and has a Clear/Reset button | 10, 5 | 1. Enter 10 and 5<br>2. Click Calculate<br>3. Click Clear/Reset | Both input fields and the displayed result are cleared | Low | Both input fields and the result were cleared | Pass |
| TC-016 | Verify division with a decimal result | Calculator is open at the demo site | 10, 3 | 1. Enter 10 and 3<br>2. Select Division (÷)<br>3. Click Calculate | Result is displayed as 3.3333 (rounded to 4 decimal places) | Medium | Result: 3.3333 | Pass |
| TC-017 | Verify multiplication of two negative numbers | Calculator is open at the demo site | -4, -3 | 1. Enter -4 and -3<br>2. Select Multiplication (×)<br>3. Click Calculate | Result is displayed as 12 | Medium | Result: 12 | Pass |
| TC-018 | Verify decimal input without a leading zero | Calculator is open at the demo site | .6, .5 | 1. Enter .6 in the first field<br>2. Enter .5 in the second field<br>3. Select Subtraction (-)<br>4. Click Calculate | Result is displayed as 0.1 | Medium | Message "Please enter valid numbers only." displayed; no result calculated | Fail |
| TC-019 | Verify input with a leading plus sign | Calculator is open at the demo site | +6, 5 | 1. Enter +6 in the first field<br>2. Enter 5 in the second field<br>3. Select Subtraction (-)<br>4. Click Calculate | Result is displayed as 1 | Low | Message "Please enter valid numbers only." displayed; no result calculated | Fail |
| TC-020 | Verify input in scientific notation | Calculator is open at the demo site | 1e5, 5 | 1. Enter 1e5 in the first field<br>2. Enter 5 in the second field<br>3. Select Subtraction (-)<br>4. Click Calculate | Input is rejected, message "Please enter valid numbers only." is displayed and no result is calculated (the calculator accepts standard decimal numbers only) | Low | Message "Please enter valid numbers only." displayed; no result calculated | Pass |

### Execution Summary

| Total Test Cases | Passed | Failed | Not Executed |
|---|---|---|---|
| 20 | 18 | 2 | 0 |

### Conclusion

These 20 test cases cover valid and invalid inputs for the calculator's basic arithmetic operations. They also verify boundary conditions, validation, error handling, and reset functionality.
