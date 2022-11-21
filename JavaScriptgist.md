# Title (Computer Science for JavaScript: Regex Tutorial)

A REGEX is a regular expression that is used to search for matches in a value or patterns within a string. The example is REGEX looking for the string to match the general markup of an email address. 

## Summary

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ This REGEX tutorial will go over the REGEX of matching an email address. For this REGEX, each piece of the string has a responsibility  to make sure or verify the user enters an email address in the correct format which needs to begin with characters followed by @ symbol and then domain. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
Anchors are the beginning and end of a regular expression. IN this email code below,
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/, the anchor is the ^ and the $. This code is telling the com puter that we are lookign for a string that starts with /^([a-z0-9_.-]+) and then end with .([a-z\.]{2,6})$/ so that is must start and finish with the given criteria with in the code. 

### Quantifiers
The example of the REGEX includes these qualifiers: + which us used to match one or more of the proceeding token { 2, 6 } which matches the specific quality of the previos token, in this case between 2 and 6 characters. Conversily, it would be { 2, 6 } which would look for 2 digits exactly or { 2, 4 } which looks for 2 or more characters. 

### Grouping Constructs
The example inlcudes the following group: ([a-z0-9_\.-]+), this expression includes + which means we match at least one or more of the any characters in the square brackets [a-z0-9_\.-]. A-Z is lowercase letters and 0-9 is the number range. 

### Bracket Expressions
Backet expressions are used to specify characters to match, they are enclosed in square brakcets. Our REGEX has 3 brakcet expression: ([a-z0-9_\.-]+), ([\da-z\.-]+), and ([a-z\.]{2,6}). 

### Character Classes
Character class distinguishes specific kinds of characters from certain sets. Our REGEX has charaters classes: . and \d The . means any character except a line break. By placing a \ in front of the . its "escaping" the character and is taken literally. The \d matches any single digit equivalent to [0-9]. 

### The OR Operator
The "or" operator within a regular expression is defined as using the | element. The component indicates that it could be either of the components that we are seperating with the |. For our hex value regualr expressiosn we have ([a-f0-9]{6}|[a-f0-9]{3}). Note the or operatopr seperates these 2 components. 
### Flags
A flag is an optional paramanater to a REGEX that modifies its behavior of searching. 

The example REGEX inlcudes "g" which stands for global search. 
### Character Escapes
There are several characters that need to be escaped to be taken literally (at least outside char classes):

- Brackets: []
- Parentheses: ()
- Curly braces: {}
- Operators: *, +, ?, |
- Anchors: ^, $
- Others: ., \

In order to use a literal ^ at the start or a literal $ at the end of a regex, the character must be escaped.
Some flavors only use ^ and $ as metacharacters when they are at the start or end of the regex respectively. In those flavors, no additional escaping is necessary. It's usually just best to escape them anyway.

## Author

vist my github link: https://github.com/jpace2022/JavaScript-Regex-Tutorial.git
