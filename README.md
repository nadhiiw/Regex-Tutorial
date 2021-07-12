# Regex-Tutorial
In this tutorial, we will be taking a brief look into what Regex (regular expressions) are and how they work. While regular expressions may seem to be overwhelming at first glance,
just like with any language, they can be broken down into its most simple parts and easily understood.

## Summary

Regex (short for regular expression) is a string of text that allows you to create search patterns that match, manage, and locate text. An example code snippet of regex shows as following:
```
/[\w._%+-]+@[\w.-]+\.[a-zA-z]{2,4}/
```
* A regular expression used to match an e-mail address

Regular expressions can also be used from the command line and within text-editors to find text within a file. 

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
Anchors are characters within the regular expression that allow the user to match strings that begin with or ends with (or both) certain characters. 

Examples of Anchors are as follows:

* `^` - matches any string that start with the anterior word
* `$` - matches a string that end with preceeding word before the character
* Examples:
```
^Hello          matches any string starting with `Hello`
World$          matches any string ending with `World`
^Hello World$   matches exact string
goodbye         matches any string that has the exact text `goodbye` in it
```