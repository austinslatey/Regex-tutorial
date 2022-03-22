# Regex-tutorial

# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Table of Contents

- [Regex-tutorial](#regex-tutorial)
- [Title (replace with your title)](#title-replace-with-your-title)
  - [Summary](#summary)
  - [Table of Contents](#table-of-contents)
  - [Regex Components](#regex-components)
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
  - [Author](#author)

## Regex Components

### Anchors

What is a regex anchor?

    A regex anchor ensures that a matched expression is anchored to a certain position in the string. The start-of-string anchor (^) ensures it’s at the start of the string while the end-of-string anchor ($) ensures it’s at the end. A word boundary (\b) ensures it’s at the start or end of a word while a non-word boundary (\B) ensures that it’s not.

        Start of String Anchor (^)
            /^abc/

        End of String Anchor ($)
            /abc$/

        Word Boundary Anchor (/b)
            /g\b/

        Non-Word Boundary Anchor (\B)
            /g\b/

### Quantifiers

What is a regex quantifier?

    A regex quantifier specifies the number of consecutive occurrences of the character or expression directly preceding it. Quantifiers can specify zero-or-more (*), one-or-more (+), zero-or-one (?), a specific quantity such as three {3}, more than three {3,}, or between one and three {1,3}. A lazy flag (?) added behind any quantifier will make it match as few characters as possible.

         Zero or More (*)
            The expression a* will match any number of consecutive occurrences of the letter a including no occurrence.


         One or More (+)
            The expression a+ will match any number of consecutive occurrences, but will not match if there is no occurrence.

         Zero or One (?)
            apples? will match both apple and apples
            abc?de will act only on whats before the c


         Specific Quantity x ({x})
            a{3} only matches specifically to the number of occurances.



        x or More ({x,})
            a{5,} will match all occurrences of variable a greater than or equal to 5. The test will fail for anything less than 5 occurrences.



        Between x and y ({x,y})
            a{2,6} will match between 2 and 6 occurrences of variable a

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
