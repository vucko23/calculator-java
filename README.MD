# Assignment – Metrics, Review and Static Analysis

## Project Description

A simple calculator implemented in Java that supports basic arithmetic operations such as addition, subtraction, multiplication, and division.

---

## LOC (Lines of Code)

Total number of lines of code (Java): 212
(Note: value obtained using the `wc -l` command)

---

## Static Analysis (Informal Review)

Calculator.java – 1 – file is not placed inside a named package (poor project structure)

Calculator.java – 4 – class has an implicit public constructor, a private constructor is recommended

Calculator.java – 18 – method "ToString" does not follow Java naming conventions (should be `toString`)

Calculator.java – 18 – method name does not follow standard naming conventions

Calculator.java – 24 – method name does not comply with naming convention rules (regex)

Calculator.java – 63 – variable name "exc" is not descriptive (poor readability)

Calculator.java – 70 – unnecessary temporary variable (can return expression directly)

Calculator.java – 74 – method name does not follow naming conventions

Calculator.java – 183 – redundant statement (unnecessary jump)

Start.java – 1 – file is not placed inside a named package (poor project structure)

Start.java – 5 – unused method parameter "args"

Start.java – 6 – variable name does not follow naming conventions

Start.java – 8 – usage of System.out instead of a logger (bad practice)

Start.java – 19 – usage of System.out instead of a logger (bad practice)

---

## Tools Used

- wc – for counting lines of code
- SonarLint – for static code analysis

---

## Conclusion

The code is simple and functional, but there are several issues related to structure and code quality.
The main problems include missing package structure, violation of naming conventions, use of System.out instead of proper logging, and presence of redundant code.

Refactoring is recommended to improve readability, maintainability, and overall code quality.
