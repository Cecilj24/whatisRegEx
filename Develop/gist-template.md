# Title - What is Reg-Ex

The purpose of this tutorial is to expand the users knowledge of reg-ex(short for regular expression). A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. This tutorial will show what is regular expression, the different types of ways that it is used and examples of different types of regular expressions. 

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
Anchors are the matching key when it comes to regular expressions.(^) is used to identify the first character and ($) is used to match the last character. An example would be applying ^a to abc matches a. ^b does not match abc at all, because the b cannot be matched right after the start of the string, matched by ^. So just like ^,  $ matches right after the last character in the string. c$ matches c in abc, while a$ does not. ^ is used to match the beginning character while $ is used to match the last character
### Quantifiers
There are all different types of quantifiers but to sum it up, quantifiers allow you to specify how many of a character or character class should be matched. An example would be if you put a "?" behind "abc" it will match anything with three letters that are consecutive. 
### OR Operator

### Character Classes
There are a number of character classes but to sum it up, character classes allow you to match a specific set of characters that can be used in a search pattern. An example of this would be \d and it would match any digit from (0-9) and \w would match any alphanumeric character from (a-zA-Z0-9).
### Flags
Flags in regular expression can change its behavior when matching a group of items. It can make it case-insensitive and/or match on multiple lines.
### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match
Greedy and Lazy match are a little similar with a slight difference in it. To sum it up, greedy will match the longest possible string and lazy will match the shortest possible string. Lazy will stop as soon as the condition is satisfied but greedy will keep going until theres nothing left. An example would be the word "helolo" (this is not a real word). Greedy h.+l would match "helol" but lazy h.+l would only match "hel".
### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
