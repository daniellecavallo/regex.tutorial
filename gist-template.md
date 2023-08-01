# Title Password Validation RegEx

This document covers the indiviudal parts and components of this regex:
"​^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{8,}$/g"

## Summary
​
This regex makes sure a password equals 8 characters, upper case, lower case, numbers, letters, and special characters.
​
## Table of Contents
​
- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)
​
## Regex Components
​

### Anchors
​Our first anchor is the ^. This tells our regex to begin at the start of a string. 
Our second one is the dollar sign. This tells our regex to stop at the end of a string.

### Quantifiers
​{8,} In our regex this symbol specifies that the password should 8 or more characters. 

### Grouping Constructs
​(?=.*[A-Z]) Our regex contains several of these grouping constructs. Each of them dictates which characters our passwords should have. 

### Bracket Expressions
​[A-Za-z\d@$!%*?&] Bracket expressions like this one specify exactly what character our regex is looking for. This particular one specifies that our regex should have uppercase, lower case, numbers, and symbols. 

### Character Classes
​[A-Z] Character classes tells regex to watch for a range of characters. This particular character class tells regex to watch for characters, upper case letters A-Z.

### The OR Operator
​This regex does not have an OR operator. 

### Flags
​Flags tell regex how far to search. The global or g flag tells regex to search the entire string.

### Character Escapes
​

## Author
​
A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
Collapse










