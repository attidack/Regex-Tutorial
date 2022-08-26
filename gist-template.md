# Regex Tutorial for Matching an Email



## Summary

This tutorial will walk through the regular expression to find or validate an E-mail address. 
</br><code> /^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/</code>

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
- the <code>^</code>  matches any string that starts with the qualifiers that are preceeding it.
- the <code> $ </code> matches a string that ends with the qualifiers before the symbol is called

### Quantifiers
- {2,6} are the Quantifiers in this expression it says that the string is going to be between 2 and 6 characters long.
- the + symbol is also a Quantifier in this expression to look for 1 or more expressions
### OR Operator
- everything between the [ ] brackets is look at as an  or expression 

### Character Classes
- \d matches a digit (equivalent to [0-9])

### Flags
- A regex usually comes within this form /abc/, where the search pattern is delimited by two slash characters /. At the end we can specify a flag with these values


### Grouping and Capturing
- parentheses create a capturing group, like everything before and after the @ then after the . (period)
### Bracket Expressions
-  this section would reflect the same thing as the or operator section.

### Greedy and Lazy Match
- this expression is a greedy match with the use of the + without the use of a ?

### Boundaries
- there are not any boundries in this expression. \b indicates a boundary

### Back-references
- this expression doesnt have any back-references ie. \1 \2 \3

### Look-ahead and Look-behind
- this expression doesnt have any look ahead or look behind components ie d(?=r) or (?<=r)d   

## Author


Jon Bird
https://github.com/attidack