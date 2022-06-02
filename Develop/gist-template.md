# Regex Tutorial 


  
## Summary

A regex is short for regular expression. It's a sequence of characters that defines a specific search pattern. When included in code or search algorithms. Regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

For example, the following regular expression can be used to verify that user input is a valid email address:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### Anchors

Anchors actually identify positions of characters.

/^([a-z0-5_\.-]+)@([\da-z\.-]+)\.([a-z\.]{,6})$/

The character "^" defines the start of string also the dollar sing "$" defines the end the string.

### Quantifiers

Quantifiers are used to specify character is expected to appear.

([a-z0-9_\.-]+)

### Character Classes

\d stand for matching email code and all single letter character @ sing in the email address. e check in tha the letter is matched after the @ not number or character.

\d - @

### Flags

flags are placed at the end of a regex also a regex must be wrapped in slash characters.

g—Global search: the regex should be tested against all possible matches in a string.

i—Case-insensitive search: case should be ignored while attempting a match in a string

m—Multi-line search: a multi-line input string should be treated as multiple lines

/regex/

### Grouping and Capturing

Grouping and capturing used () in regex

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

([a-z0-9_\.-]+) is the first group that appears in our regex. This must be true before moving on to "match" the next part of the code. ([\da-z\.-]+) is the second group that appears in our regex. ([a-z\.]{2,6}) is the third group that appears in our regex.

### Bracket Expressions

The guidelines for matching the group. For this code snippet, it can contain letters a-z, numbers 0-9, an underscore, hyphen, or period.

[a-z0-9_\.-]

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


Author Francisco Alegria
