# recursions
# Palindrome Checker (Recursive)

This is a simple JavaScript function that determines whether a given word is a palindrome using a recursive approach.

## How It Works

The function uses a recursive algorithm to check if the given word is a palindrome. It compares the characters located at the ends of the word. If they are equal, it recursively tests the rest of the word. If they are different, the algorithm stops. The stop conditions are an empty word or a word containing a single character, both of which are considered palindromes.

## Usage

1. Clone this repository or copy the `palindromeRecursive.js` file to your project.
2. In your JavaScript code, import or include the `isPalindromeRecursive` function.

Example:

```javascript
const { isPalindromeRecursive } = require('./palindromeRecursive');

console.log(isPalindromeRecursive("gag"));     // true
console.log(isPalindromeRecursive("kayak"));   // true
console.log(isPalindromeRecursive("hello"));   // false
// Add more test cases as needed
