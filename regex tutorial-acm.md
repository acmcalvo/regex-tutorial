# Regex Tutorial on Matching Email

A regular expression is a sequence of characters that specifies a search pattern in text. The patterns help you match, locate, and manage text. For example, this tutorial will follow an example code snippet that can be used to match an email. This tutorial will follow the different components of regular expressions.

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
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Anchors assert that the engine's current position in the string matches a well-determined location: for instance, the beginning of the string, or the end of a line.. In the regex code above, ^ anchor symbolizes the beginning of the text and $ anchor symbolizes the end of the text

### Quantifiers

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

A quantifier specifies how many characters, groups, or instances of a character must appear in the input to find a match. In the regex code above, + is a greedy quantifier that there is another sequence to be matched and {2,6} tells us that the input should be a minimum of 2 characters and a maximum of 6 characters.

### OR Operator

OR Operator is not in include in this email code.


### Character Classes

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

A character class is a set of characters enclosed within square bracket. In the regex code above, \d is a shorthand character for [0-9] that matches any character that is a digit.

### Flags

i: Ignores casing. Makes expression case-sensitive
g: Global. Makes expression search for all occurrences
s: Dot All. Makes the wild characters. Match newlines as well
m: Multiline. Make the boundary characters ^ and $ match the beginning and end of each line.
y: Sticky. Indicates that it matches only from the index indicated by the lastIndex property of this regular expression in the target string (and does not attempt to match from any later indexes)
u: Unicode. Expression assumes individual characters are code points, not code units and will then match 32 bit characters.

### Grouping and Capturing
There are three groups in that captured in this example. Group #1 is the username of the e-mail account [a-z0-9_\.-]. The second group captures the domain name or e-mail service being used [\da-z\.-]. Finally, the third group captures domain extensions (i.e. .com or .net) [a-z\.]{2,6}

### Bracket Expressions

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

A Bracket expression is a list of characters enclose by []. Much like the grouping and capturing section, there are three bracket expressions.
[a-z0-9_\.-] - includes case sensitive characters from a-z, numbers from 0-9 an underscore, periods and hyphens.
[\da-z\.-] - includes all digits, case sensitive characters from a-z, periods and hyphens
[a-z\.] - includes case sensitive characters from a-z and periods.

### Greedy and Lazy Match

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

'Greedy Match' means that it will match the longest possible string while a 'Lazy Match' will do the opposite such that it will match the shortest possible string. In the code above, + would be used for a greedy search. If > is added to +, the mode would switch from greedy to lazy.

### Boundaries

Boundaries are similar to an anchor and uses the expression \b for word boundaries and \B for non-word boundaries. They are a zero-length match that marks the beginning and end of an alphanumerical sequence and will make it easier to find whole words. The beginning of this expression \b([-a-zA-Z0-9()@:%_\+.~#?&//=]*) is searching for a whole word or digit.
Boundaries are not used in given email code.

### Back-references

Back-references are not in use inn the given email code.

### Look-ahead and Look-behind

It is not being used in the given matching an email code.

## Author

  If you have any questions about this projects, please contact me directly at acmcalvo@yahoo.com. 
  You can view more of my projects at https://github.com/acmcalvo. 