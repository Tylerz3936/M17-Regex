# Tutorial: Understanding the Regex Pattern '^\d{3}-\d{2}-\d{4}$'

# Introduction
Welcome to this tutorial on understanding the regex pattern ^\d{3}-\d{2}-\d{4}$. Regex, or regular expressions, are powerful tools used in programming for pattern matching within strings. This tutorial aims to break down the given regex pattern, explain its components, and help you understand how it works to match specific string formats.

## Summary

The regex pattern ^\d{3}-\d{2}-\d{4}$ is used to match a string that follows the format of a U.S. Social Security Number (SSN). This format consists of three digits, followed by a hyphen, two more digits, another hyphen, and four final digits (e.g., 123-45-6789).

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)
- [Complete Pattern](#complete-pattern)

## Regex Components

### Anchors
#### '^' and '$' 
The '^' and `$` symbols are known as anchors. The '^' symbol asserts the position at the start of the string, and the '$' symbol asserts the position at the end of the string. Together, they ensure that the entire string matches the pattern exactly, with no extra characters before or after.

### Quantifiers
'{3}', '{2}', '{4}'
Quantifiers specify how many instances of the previous character or group are required:

- '{3}' means exactly three digits.
- '{2}' means exactly two digits.
- '{4}' means exactly four digits.

### Grouping Constructs
This pattern does not include any grouping constructs such as parentheses ().

### Bracket Expressions
This pattern does not include any bracket expressions such as [].

### Character Classes
'\d'
The '\d' character in regex matches any digit from 0 to 9. It's shorthand for [0-9].
### The OR Operator
This pattern does not include any OR operators |.

### Flags
This pattern does not include any flags such as i, g, or m.

### Character Escapes
'-'
The hyphen '-' is a literal character in this pattern. It is used to separate the groups of digits in the format.

### Complete Pattern
Combining all components, the regex pattern ^\d{3}-\d{2}-\d{4}$ matches strings that:

1. Start with exactly three digits.
2. Followed by a hyphen.
3. Followed by exactly two digits.
4. Followed by another hyphen.
5. End with exactly four digits.

For example, 123-45-6789 matches the pattern, while 12-345-6789 or 1234-56-789 do not.

## Author

This tutorial was written by Tyler Zhao, a web development student passionate about regex and pattern matching. You can find more of my work and follow me on GitHub: Tylerz3936.
