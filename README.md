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

  2. Test: "It can convert the number 1 to Roman numerals from an array"
  Code:
  let numbersInput = [1];
  let numeralKey = ["I"];
  romanize(numbersInput);
  Expected Output: I

  3. Test: "It can convert the number 2 to Roman numerals from an array"
  Code:
  let numbersInput = [2];
  let numeralKey = ["I"];
  let numeral = [];
  romanize(numbersInput);
  