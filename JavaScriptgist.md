# Title (Computer Science for JavaScript: Regex Tutorial)

A REGEX is a regular expression that is used to search for matches in a value or patterns within a string. The example is REGEX looking for the string to match the general markup of an email address. 

## Summary

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ This REGEX tutorial will go over the REGEX of matching an email address. For this REGEX, each piece of the string has a responsibility  to make sure or verify the user enters an email address in the correct format which needs to begin with characters followed by @ symbol and then domain. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Character Escapes](#character-escapes)

## Regex Components
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
Anchors are the beginning and finish of a regular expression. In the following code,
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/, the anchor is the ^ and the $. Anchors are mostly used to validate an input. 

### Quantifiers
In order for a match to be found, a Quantifier must specify how many instances a character must be present in the input. The email REGEX has the + as the quantifier that repeats a match one or more times.

### Bracket Expressions
Backet expressions are used to specify characters to match. Square brackets are used to indicate a set of characters to match and curly braces are used to specify an exact amount of characters to match. 

### Character Classes
Character class distinguishes specific kinds of characters from certain sets. Any one can happen in a string input for a match to succeed. 

### The OR Operator
The "or" operator within a regular expression is defined as using the | element. The component indicates that it could be either of the components that we are seperating with the |. 

### Flags
A flag is an optional paramanater to a REGEX that modifies its behavior of searching. A flag changes the default search behavior of a regular expression. A flag is destiguished with using a single lowercase alphabetic character. 

### Grouping and Capturing
The example includes the following groups: ([a-z0-9_\.-]+), this expression includes + which matched at least one or more of any characters n the square brackets [a-z0-9_\.-]. a-z is lowercase letters from a to z, 0-9 is a number from 0 - 9. When matching, it has to make sure that the following guidelines of the group are there before it can move on the next group. 

### Greedy and Lazy Match
The Greedy match, matches the longest possible string. The standard qualifiers in regular expressions are greedy, meaning they match as much as they can, only returning as necessary to match what it can of the REGEX. A Lazy match is the opposite and matches the shortest string possible. By using a lazy qualitier, the expression tries the minimal match first. The example REGEX inlcudes "g" which stands for global search. 

## Author

vist my github link: https://github.com/jpace2022/JavaScript-Regex-Tutorial.git
