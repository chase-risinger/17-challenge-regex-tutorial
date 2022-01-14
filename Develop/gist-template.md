# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Above is the regular expression representing an email.  This puzzling and cryptic series of symbols, numbers and letters will help us search through a document and extract only emails.  This highly efficient code will only accept strings formatted to look like example@domain.com

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
The carot symbol (^) and the money symbol ($) are the anchors.  The carot symbol represents the start of the regular expression.  

So in our case ^([a-z0-9_\.-]+)... we are saying that the string we are searching for must begin with either a lowercase letter, a number or any of the symbols ( _ ) ( . ) or ( - ).

And ...([a-z\.]{2,6})$ we are saying that the string we are searching for must end with either a lowercase letter or a period
 
### Quantifiers
In Regex, the quantifiers are * + ? { n } {n ,} and {n, m}

* match zero or more times
+ match one or more times
? match zero or one time
{ n } match exactly n number of times
{N ,} match at least n number of times

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
