# [Caesars Cipher](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/javascript-algorithms-and-data-structures-projects/caesars-cipher)

One of the simplest and most widely known ciphers is a Caesar cipher, also known as a shift cipher. In a shift cipher the meanings of the letters are shifted by some set amount.

A common modern use is the [ROT13](https://www.freecodecamp.org/news/how-to-code-the-caesar-cipher-an-introduction-to-basic-encryption-3bf77b4e19f7/) cipher, where the values of the letters are shifted by 13 places. Thus `A ↔ N`, `B ↔ O` and so on.

Write a function which takes a [ROT13](https://www.freecodecamp.org/news/how-to-code-the-caesar-cipher-an-introduction-to-basic-encryption-3bf77b4e19f7/) encoded string as input and returns a decoded string.

All letters will be uppercase. Do not transform any non-alphabetic character (i.e. spaces, punctuation), but do pass them on.

## Tests

1\. `rot13("SERR PBQR PNZC")` should decode to the string `FREE CODE CAMP`

2\. `rot13("SERR CVMMN!")` should decode to the string `FREE PIZZA!`

3\. `rot13("SERR YBIR?")` should decode to the string `FREE LOVE?`

4\. `rot13("GUR DHVPX OEBJA SBK WHZCF BIRE GUR YNML QBT.")` should decode to the string `THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG.`

### [Official Solution](https://github.com/FreeCodeCamp-Solutions/JavaScript-Algorithms-and-Data-Structures-Projects)
