# Title (Computer Science for JavaScript: Regex Tutorial)

This is a tutorial that will covers the main concepts of regular expressions or “REGEX”. The example I will be reviewing is the string used to match values for email addresses. /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Summary

REGEX or also referred to as a regular expression are sequences of characters that specifies a search parameter. Regular expressions are used to confirm the input or to find or replace characters within text. This expression is deemed a REGEX and are considered universal in most programming languages:

 /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [The OR Operator](#the-or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back References](#back-references)
- [Looking Ahead and Looking Behind](#looking-ahead-and-looking-behind)

## Regex Components

* Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

### Anchors
Usually, Anchors are used to authenticate an input. Frequently in order to match a position prior to, after or in the middle of. An example of an Anchor is ```^``` that can match the beginning of a string and ```$``` will inidicate the end. 

### Quantifiers
When you have an input, in order to find a match, a Quantifiers indicate how many occurrences of a character must be present. Please see some examples below;

```
Greedy Quantifier       Lazy Quantifier       Description  
?                           ??              Matches 0 or 1 time. 

```

### The OR Operator
The vertical bar symbol ```|``` is the OR operator in this case and it can be utilized to match any characters or expression which allows for an either/or conditional match.

### Character Classes
Character class distinguishes a specific kind of characters from other certain sets. Which can occur in an input string for a match to be successful. Please see examples below. 
```
 \w: Word
 \s: Whitespace
 \d: Digit

```

### Flags
A flag is an optional paramanater to a REGEX that modifies its behavior of searching. A flag changes the default search behavior of a regular expression. A flag is destiguished with using a single lowercase alphabetic character. 

### Grouping and Capturing
With REGEX ```()``` you are able to “capture” a group that will match and it will also indicate that you are intending to use part of the string that is within the parentheses. Grouping constructs delineate the subexpressions of a regular expression and capture the substrings of an input string. 

### Bracket Expressions
In order to specify a character to match, you must use square brackets ```[]``` to indicate a set of characters that need to be matched and if you want to specify an exact amount of characters, curly braces ```{}``` should be used.  

### Greedy and Lazy Match
When you have a GREEDY match, it will match you with the longest string available. The typical quantifiers in REGEX are GREEDY, which means they match as much as they can, only returning as necessary to match what it can of the REGEX. 

A LAZY match matches the shortest string possible. By using a LAZY quantifier, an expression will try the shortest match first. 

### Boundaries

### Back References

### Looking Ahead and Looking Behind

## Author

vist my github link: https://github.com/jpace2022/JavaScript-Regex-Tutorial.git
