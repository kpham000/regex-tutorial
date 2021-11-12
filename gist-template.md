# Title (replace with your title)

Regular expression also known as, "Regex", this is a sequence of characters that is used to search for a pattern in the code. 

<br>

## Summary

Hex code is a hexidecimal format for identifying a mixof a specific color. 
This is a regex used to match a hex values:

```
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/
```

<br>

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

<br>

## Regex Components

<br>

### Anchors

```
^
```

This character signifies the beginning of a string. Hex values must always begin with '#' so we would type, '^#'.

```
$
```
To end the string we must use this symbol '$'.

<br>

### Quantifiers

```
?
```
This is the first qualifier in the string, '?'. This tells the length for the hex code that is usually 3-6 characters.

<br>

### Grouping Constructs

```
([a-f0-9]{6}|[a-f0-9]{3})
```
The OR operator states if the length is either 3 or 6 characgters after '[a-f0-9]'.

<br>

### Bracket Expressions

```
[]
```
Within the brackets gives the criteria for the code. 

<br>

### Character Classes

```
[a-f0-9]
```
This is stating the criteria of hexcode which can only contain letters 'a-f' and the numbers '0-9'.

<br>

### The OR Operator

```
|
```
Hex code can have length of 3 or 6 but not bothe so this is used to separate by using OR operator.

<br>

### Flags

Matching hex values does not contain flags.

<br>

### Character Escapes

Matching hex values does not contain chacter escapes.

<br>

## Author

Hello, my name is Kelly. I am a student at UW full stack coding bootcamp.

https://github.com/kpham000 

<br>
