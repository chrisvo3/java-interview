# URLify

Write a method to replace all spaces ina string with `'%20'`. You may assume taht the string has sufficient space at the end to hold the additional chracters, and that you are given the "true" length of the string.

*Note: If implementing in Java, please use a chracter array so that you can perform this operation in place*

**EXAMPLE**

Input: `"Mr John Smith   `, 13

Output: `"Mr%20John%20Smith"`

## Hint

It's often easiest to modify strings by going from the end of the string to the beginning.

You  might find you need to know the number of spaces. Can you just count them?