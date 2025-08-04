# Bro Code - JavaScript Full Course (2024)

From [Bro Code's YouTube channel](https://youtu.be/lfmg-EJ8gm4?si=yPvTYS3wx6eC94AE).

## Notes

VScode Multi-line Comment: `Shift + Alt + A`

- **variable**: A container that stores a value. It behaves as if it is the value it contains.
  - Declaration: `let x;`
  - Assignment: `x = 100;`
  - Combined: `let x = 100;` - Probably most often used, but it's two statements combined.
- **arithmetic operators**: Tools that allow you to perform arithmetic functions.
  - **operators**: (`+ - * /`)
    - **addition**: `+`
    - **subtraction**: `-`
    - **multiplication**: `*`
    - **division**: `/`
    - **exponent**: `**`
    - **modulus**: `%`
  - **augmented assignment operators**:
    - **increment by value**: `+=`
    - **decrement by value**: `-=`
    - **multiply by value**: `*=*`
    - **divide by value**: `/=`
    - **exponent by value**: `**=`
    - **modulus by value**: `%=`
    - **increment by one**: `++`
    - **decrement by one**: `--`
  - **operands**: Anything that the operators work on. In the example `11 = x + 5`, the operands are `11`, `x`, and `5`.
  
  ### Operator Precendence

  1. parenthesis ()
  2. exponents
  3. multiplication & division & modulo
  4. addition & subtraction

  ### Accepting User Input | Type Conversion | Constants

  - Accept user input via a window dialog or an HTML input, with the latter preferred.
  - Use document.getElementById() to target the element's value you want to grab.
  - `Number()`: Function will cast your variable to a number.
  - `String()`: Function will cast your variable to a string.
  - `Boolean()`: Function will cast your variable to a boolean.
  - `const`: Declares a variable as constant so it cannot be changed.  There is a convention to use ALL-CAPS for primitive values (e.g., PI) or InitialCaps for strings, etc.  Will throw an uncaught type error if you try to reassign it.
