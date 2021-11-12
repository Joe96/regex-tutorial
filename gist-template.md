
## What Is a Regex?

Regex, or regular expression**, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input. 

## Regex Components

To begin we will first take a look at the first and last character of the expression: / and /. All these symbols are doing is delineating where the expression starts and ends, so everything between / and / is the content of the expression. The following regular expression can be used to verify that user input is a valid email address:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the `@` symbol, followed by a domain.

* Matching a Hex Value: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

* Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

* Matching a URL: `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`

* Matching an HTML Tag: `/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/`



## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Bracket Expressions](#bracket-expressions)


## Anchors

This expression starts off with an anchor
^ start of string and $ end of string
Anchors have special meaning in regular expressions. They do not match any character. Instead, they match a position before or after characters:


## Bracket Expressions

Bracket expression: [a-zA-Z0-9.+_-]+@[a-zA-Z0-9.-]+.[a-zA-Z]

## Quantifiers

Quantifiers match a number of instances of a character, group, or character class in a string.