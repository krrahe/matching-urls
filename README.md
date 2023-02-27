# matching-urls
This is a break down of a certain kind of regex. Matching URLS specifically 



## Matching a URL: /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

## Introduction:
In today's digital age, URLs have become an integral part of our lives. Whether it is browsing the web, sharing content or accessing online services, URLs are ubiquitous. Regular expressions, or regex, provide a powerful tool for matching and manipulating text, including URLs. In this article, we will explore the regex pattern for matching URLs, which can be used in various programming languages and applications.

## Summary
The regex pattern /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/ matches URLs that start with "http://" or "https://", followed by a domain name (e.g., "example.com") and an optional path. The pattern also allows for subdomains, top-level domains, and paths that may contain alphanumeric characters, dashes, underscores, and slashes. In the following sections, we will break down each component of the pattern and explain how it works.

## Table of Contents
- [Anchors](#Anchors)
- [Quantifiers](#Quantifiers)
- [Grouping Constructs](#Grouping-Constructs)
- [Bracket Expressions](#Bracket-Expressions)
- [Character Classes](#Character-Classes)
- [The OR Operator](#The-OR-Operator)
- [Flags](#Flags)
- [Character Escapes](#Character-Escapes)
## Regex Components
## Anchors
The "^" character at the beginning of the pattern specifies that the URL must start at the beginning of a line. The "/" character at the end of the pattern specifies that the URL must end with a forward slash or be followed by nothing.

## Quantifiers
The "?" character after "(https?://" specifies that the "s" in "https" is optional. The "*" character after the path group specifies that the path can contain zero or more characters.

## Grouping Constructs
The parentheses are used to group parts of the pattern together. The first group, "(https?://)?", matches "http://" or "https://". The second group, "([\da-z.-]+)", matches one or more characters that are either digits, lowercase letters, dots, or hyphens. The third group, "([a-z.]{2,6})", matches a top-level domain that is between 2 and 6 characters long. The fourth group, "([/\w .-]*)", matches zero or more characters that can be either alphanumeric, a space, a dot, a hyphen, or a forward slash.

## Bracket Expressions
The square brackets are used to define a range of characters. The "\d" inside the square brackets matches any digit, and the "." matches any character.

## Character Classes
The backslash followed by a lowercase "w" matches any alphanumeric character, and the backslash followed by a space matches a literal space character.

## The OR Operator
The "|" character is used to specify alternative patterns. In this case, it is used to match either "http" or "https" in the URL.

## Flags
Flags are used to modify the behavior of the regex engine. In this pattern, no flags are used.

## Character Escapes
The backslash is used to escape characters that have a special meaning in regex. For example, the backslash followed by a dot matches a literal dot character, rather than any character.

Author
I am Riley Rahe, middle 20s from kansas. I always thought that coding would be neat. Might as well try to be productive on the computer right. 
