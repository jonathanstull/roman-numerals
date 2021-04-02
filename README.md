## Test-Driven Development

**Specs**

* Write a method that converts numbers into Roman numerals
* Do not use a character more than three times (> 3)
* Use a character to subtract in such instances (e.g., 5 - 1 or IV)
* Symbol  Value
    I       1
    V       5
    X       10
    L       50
    C       100
    D       500
    M       1,000

**Tests**
Describe: romanize();
  1. Test: "It can return the number 1"
  Code:
  romanize(1);
  Expected Output: I