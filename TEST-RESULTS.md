# Test Results – Black Box Testing

## Test Cases

Input: 4+5
Result: 9.0 → PASS

Input: 10+5*4
Result: 30.0 → PASS

Input: 10+5*4+3
Result: 33.0 → PASS

Input: 10/0
Result: Infinity → FAIL
Issue: Division by zero not handled

Input: 5++5
Result: ERROR → PASS

Input: abc
Result: ERROR → PASS

Input: 5/2
Result: 2.5 → PASS

Input: -5+3
Result: -2.0 → PASS

Input: 999999999*999999999
Result: 1.0E18 → PASS

---

## Conclusion

The calculator works correctly for valid inputs and respects operator precedence.

However, division by zero is not properly handled, as it returns "Infinity" instead of an error.
