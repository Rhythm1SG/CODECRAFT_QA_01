# CodeCraft Infotech - Quality Assurance Internship

## Task 1: Test Cases for a Simple Calculator Application

### Objective
To create detailed test cases for a calculator application that performs addition, subtraction, multiplication, and division.

### Test Cases

| Test Case ID | Test Description | Preconditions | Test Steps | Expected Results |
|---|---|---|---|---|
| TC-001 | Verify addition of two positive numbers | Calculator is open | Enter 10 and 5, select Addition (+), and click Calculate | Result should be 15 |
| TC-002 | Verify subtraction of two positive numbers | Calculator is open | Enter 10 and 5, select Subtraction (-), and click Calculate | Result should be 5 |
| TC-003 | Verify multiplication of two positive numbers | Calculator is open | Enter 10 and 5, select Multiplication (×), and click Calculate | Result should be 50 |
| TC-004 | Verify division of two positive numbers | Calculator is open | Enter 10 and 5, select Division (÷), and click Calculate | Result should be 2 |
| TC-005 | Verify addition with zero | Calculator is open | Enter 10 and 0, select Addition (+), and click Calculate | Result should be 10 |
| TC-006 | Verify subtraction resulting in a negative number | Calculator is open | Enter 5 and 10, select Subtraction (-), and click Calculate | Result should be -5 |
| TC-007 | Verify multiplication with zero | Calculator is open | Enter 10 and 0, select Multiplication (×), and click Calculate | Result should be 0 |
| TC-008 | Verify division by zero | Calculator is open | Enter 10 and 0, select Division (÷), and click Calculate | Calculator should display an appropriate error message and should not return a valid numeric result |
| TC-009 | Verify calculations using decimal numbers | Calculator is open | Enter 5.5 and 2.5, select Addition (+), and click Calculate | Result should be 8 |
| TC-010 | Verify calculations using negative numbers | Calculator is open | Enter -10 and -5, select Addition (+), and click Calculate | Result should be -15 |
| TC-011 | Verify blank input fields | Calculator is open | Leave one or both input fields empty and click Calculate | Calculator should display a validation message |
| TC-012 | Verify non-numeric input | Calculator is open | Enter alphabetic or invalid characters in an input field and click Calculate | Calculator should reject the input and display a validation message |
| TC-013 | Verify large numeric values | Calculator is open | Enter large valid numbers and perform an arithmetic operation | Calculator should calculate the result correctly or display an appropriate overflow/validation message |
| TC-014 | Verify repeated calculation | Calculator is open | Perform a calculation, then enter new values and perform another calculation | Calculator should calculate the new values correctly without using the previous result incorrectly |
| TC-015 | Verify calculator reset/clear functionality | Calculator is open | Enter values, perform a calculation, and click Clear/Reset if available | All input fields and displayed results should be cleared |

### Conclusion

These test cases cover valid and invalid inputs for the calculator's basic arithmetic operations. They also verify boundary conditions, validation, error handling, and reset functionality.
