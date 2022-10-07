# Regex Tutorial

Introductory paragraph: \
hello, this is my tutorial on Regex or Regular expressions and their components and how they work. this tutorial will teach and walk you through how to write and the components in a regex and also provide a easy to use table of contents along with a clear and consist way to find information on specific parts of a regex. 

## Summary

the things that i will cover in this tutorial are Anchors, Quantifiers, Grouping Constructs, Bracket Expressions, Character Classes, The OR Operator, Flags, and also Character Escapes
this will also be taking from the Regex `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/` we will break it down and understand how it work and what all of it does.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
How do you create a regular expression:  you can do it multiple ways you can make it a constant by calling it re and wrapping it in a / for example `const re = /ab+c/;` \
what do they do?: some things that a Regex can do is test for matching string or replace string the target just has to be string.

### Anchors
the Anchor will allow you to make a link and reference it to something such as a website but in this instance it will be a e-mail. the code that is wrapped in the `<a>` will be the content both the link and the string you wish to display the href that goes inside the `<a>` like `<a href="">` will allow you to put the link that it will take you to wherever you linked it to.
### Quantifiers
The quantifiers are specificity how many instances of a character group and can also be character class that must be present in the for a match to be found there are two different types of Quantifiers lazy and greedy. A greedy quantifier will try to match a element as much as it can while a lazy will do it as few times as possible. in our expression you could take a string input and put it in the 0-9 and make something such as any number with it.
### Grouping Constructs
Grouping Constructs can delineate a subexpression of a regular expression and capture the substring of a input string. what this does in out regex is it will take the data and it can include or exclude data determining on what we put in the pattern such as in ours when we have `{2,6}` this can be used in a date such as 2006.
### Bracket Expressions
Bracket expressions in my eyes are the easiest because they are what they look like they are things such as `[a-z]` and this will give you accesses to all the letters in the alphabet or `[0-9]` witch will give you all the numbers and is used multiple times in our example. what they do is match a single character or collating element. 
### Character Classes
a character class is a set of characters enclosed within square brackets more importantly it specifies the characters that will successfully match a single character from a given point using input string a good example of this would be `[abc]` just means a b or c. you can use this to make different sentences or make things plural or singular by adding or taking away an s
### The OR Operator
the or operator will allow you to choose between two things depending on the situation for a example it could be `result = expression9 or expression3` the only thing that is required is a boolean or an numeric expression and as long one or both of the expressions are the same it will return true the only reason it would return false would be if they are both returned false. 
### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
