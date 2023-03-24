# JavaScript Functions & Operations

## Functions

- Pieces of code that perform a specific functions/actions.
- Can be called/executed/invoked multiple times throughout code
- To call a function by using its name followed by parentheses "()". If the function takes any arguments, you can pass them inside the parentheses separated by commas.

>Example:
>
>function addNumbers(num1, num2) {
  return num1 + num2;
}
>
>Note: Arguments are typed inside the brackets

- To use functions they must be called
>
>Example: 
>
>let sum = addNumbers(5, 10);
console.log(sum); // 
>
>**Output: 15**
>
>

## Operations

Operations are performed on values.

### Examples

- Arithmetic Operations:

>let x = 5 + 3; // addition
>
>let y = 10 - 4; // subtraction
>
>let z = 2 * 6; // multiplication
>
>let w = 12 / 4; // division
>
>let r = 17 % 3; // modulus (remainder)

- **Comparison Operations:** compare values and retures a boolean (true/false) result

>let a = 10;
let b = 5;
>
>console.log(a == b); **Output: false**
>console.log(a > b); **Output: true**
>console.log(a <= 10);  **Output: true**

-**Logical Operations:** Used to combine boolean values and return a boolean result

>let hasMoney = true;
>
>let isHungry = false;
>
>console.log(hasMoney && isHungry); **Output: false**
>
>console.log(hasMoney || isHungry); **Output: true**
> console.log(!hasMoney); **Output: false**

-**Assignment operations:** used to assign values to variables.

>let c = 10;
>
>c += 5; // equivalent to c = c + 5
>
>console.log(c); // 15

