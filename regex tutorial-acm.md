# Regex Tutorial on Matching an Email

A regular expression is a sequence of characters that specifies a search pattern in text. The patterns help you match, locate, and manage text.

## Summary

Email is method of exchanging messages between any platform. As a developer, it is important to verify that the user input is a valid email address In this tutorial, we will demonstrate regular expressions for email using: 
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/ Anchors assert that the engine's current position in the string matches a well-determined location: for instance, the beginning of the string, or the end of a line.. In the regex code above, ^ anchor symbolizes the beginning of the text and $ anchor symbolizes the end of the text

### Quantifiers

/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/ In regex, quantifiers specify how many instances of a character, group, or character must be presented in the input for a match to be found. In the regex code above, + is a greedy quantifer that there is another sequence to be matched and {2,6} tells us that the input should be a minimum of 2 characters and a maximum of 6 characters.

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
