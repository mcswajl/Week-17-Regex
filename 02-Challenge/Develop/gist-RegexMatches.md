# Title Regex explinations for week 17

## Introduction
The markdown file describes how the different components of my Regex expression works. This weeks challenge is different from out past challenges, we are writing about code. After spending hours learning about Regex I know understand how powerful this can be when authenticating usernames, emails, URLs, etc.. A Regex can be coded directly into your code of choice (in my case JavaScript), you don't have to write a separate file just for Regex. This website was very useful https://regexr.com/.

## Summary

Below the table of contents you will find detailed sections explaining my email regex.. My Email code snippet can be found in section "Reg Components".  


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
`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`
### Anchors
The anchors in my Regex are the ^ matches  the beginning of regex string or line and the $ matches the end of the string or line.
*Note these are for JavaScript Browser

### Quantifiers
I have a few quantifiers in my Regex. First is the + matches 1 or more of the preceding tokens. In this Regex the + adds everything after the + to eveything before the +.
Next quantifiers is {2,6}, this means the text (previous token) (including the period (.)) must be between 2 and 6 total number chacters.
*Note these are for JavaScript Browser

<!-- ### OR Operator
I don't see any JavaScript operators. I do see some operators for SQL like (.), (*), (+), etc. This can be confusing depending on the enviornment that you are working in.
 -->
### Character Classes
I have a few character classes. First I have a range [a-z0-9_\.], in this range my letters have to be lower-case and between a and z, my numbers have to be between 0 and 9, I can use an underscore, \ (backslash) is an escape that allows this range to have a period (.).
Next range [\da-z\.-] \d means digit (0-9) any lower-case letter between a and z \ an escape that now allows a period(.) and or a hyphne (-).
Next range [a-z\.] any lower-case letter between a and z \ escape allowing for a period(.)
*Note these are for JavaScript Browser

<!-- ### Flags
I don't have any flags in my Regex. Flags examples could be a g for Global, s for dotail, u for ungreedy, etc. -->

### Grouping and Capturing
I do have some capture groups in my Regex. ([a-z0-9_\.-]+) and ([\da-z\.-]+) and ([a-z\.]{2,6}), similar to a range but with () instead of [].

<!-- ### Bracket Expressions
I don't see a bracket expression in my Regex. Is this a bracket ezpression? []\d^-] matches ], \, d, ^ or -.
 -->
<!-- ### Greedy and Lazy Match
I don't see and Lazy (ex. ?, *?, +?, etc.?) matches.

### Boundaries
I don't see any (\b or \B ) word boundaries in my Regex.

### Back-references
I don't see any back-references in my Regex. A back-reference in a group would look like this ([-/ ]).

### Look-ahead and Look-behind
I don't see any look-aheads ((?=ABC), (?!ABC)) and I also don't see any look-behinds ((?<=ABC), (?<!ABC)) in my Regex.
 -->
## Author

My name is Josh McSwain, I 43 years old, married with two teenage kids.<br>
 I live in Mount Holly, NC and I have been employed with Mecklenburg County since 2003.
I enjoyed writing this READme and learning just how powerful Regex components are in coding.

GitHub profile link https://github.com/mcswajl
