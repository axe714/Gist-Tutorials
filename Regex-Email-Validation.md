# Regex Tutorial 

## What is regex?
- In the world of computer science, we use regular expressions, also known as regex, to validate through a body of text or to locate patterns in the text using specific instructions or parameters that we define ourselves. Some of the most common uses of regex include locating, validating, searching, updating, sorting or filtering through text that match a certain form. 

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
- As mentioned above, one of the most common ways that people use regex for is validation purposes. The following is an expression for email validation:

```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

- In order to help us fully understand regex as a whole, lets break down this regular expression for email validation into smaller components:

### Anchors
- Anchors are a set of instructions that we can write in our regex which specify the location within a particular string to search. 

- In regex, we use the ```^``` (caret) key to match at the beginning of a new line, and we use the ```$``` (dollar sign) to match at the end of the line. 

- In the example above, we can see that there is a ```^``` in the section *before* the ```@``` and there is a ```$``` *after* the ```@``` sign.

```
- /^([a-z0-9_\.-]+) - Match at beginning of a line.
```

```
- ([\da-z\.-]+)\.([a-z\.]{2,6})$/ - Match at the end of a line.
```

### Quantifiers
- We use quantifiers to specify or define how many occurances of a character, group, or character class in a body of text happens for a match to be found.

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author
- [Github Profile - Axe714](www.github.com/axe714)
- For inquiries/questions, please reach out to me at allec@gmail.com