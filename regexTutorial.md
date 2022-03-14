# Matching an Email Rexgex Tutorial

Regex stand for regular expression. Regex can look very complicated. With the right tools and help, you will be able 
to look at a regex and understand what each number and symbol means. Regex are basically just a serch pattern. 


## Summary

Regex: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.])

This Regex is to help verify an email. Email verfication is widely used to make sure users dont write a email wrong. This regex can look over whelming. So, it maybe easier to break it down into parts to see what is really going on here. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping](#grouping)

## Regex Components

Every regex starts with ' ^ '.
Parts of each regex has a caputuring group which are located inside of the '( )'. 
In each capturing group there are charater sets and different things. 

### Anchors

Anchors are used to choose a specific part of infromation. There are none in this Regex. 

### Quantifiers

Quantifiers are to make sure numbers if charaters match or a certian number of character classes are met. The ' + ' sign at the end of the '[ ]' indicates that it needs to match one or more of the ranges and characters. Also the @ symbol can be considered a qualifier as well. Also the \. outside of the ( ) as well. These two indicate that you need a '@' inbetween groups one and two, and a period between two and three. EX one@two.three 

### Character Classes

There are three character sets in this Regex. They are surrounded by the the '[ ]'. In the first one there is a ' a-z ' letter range and a 
' 0-9 ' number range for the first half of the email. It also has symbols like '_ . -' that can be included in the first part. '\.' this indicates just a period that can be included in the first part of the email. The ' . ' means something else in regex talk, so the charater . gets a ' \. ' to distunguish between the two. In the second [] there is a a-z, \d (which means any digit), a '\.' to symbolize ' . ' ,and a -. This means that the second part of the email can have any number, letter, period, dash. The third class has a range of a-z. 
 

### Grouping

Groups are everything in the '( )'. That is including all the character sets/ classes. 
The first group it the first half of the email. The second one is the actual domain name for the email. EX: Gmail, Outlook, and Yahoo. 
The last is the .com .org .edu ending. This really breaks down the email and the regex parts. 

## Author

I wouldn't call myself a regex master, but I would say I am familiar with regex and the layout of how it works. Here is my gitHub profile so you can see some of my work. 

Samantha Chavez 

Sam's GitHub: https://github.com/Sammychvz17



