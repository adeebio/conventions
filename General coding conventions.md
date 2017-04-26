# General coding conventions

## Contents

  * [Formatting](#formatting)
  * [Naming](#naming)
  * [Spacing](#spacing)

## Formatting

### Brackets

By examples...

#### Function arguments

```javascript
function myFunction(a, b) {
  sum = a + b;
  return sum;
}
```

#### Loops

```javascript
for (i = 0; i < 5; i++) {
    text += "The number is " + i + "<br>";
}
```

### Line length

The length of a line should be 80 characters long, starting from, and including,
the first significant character. Characters at the beginning of the line related
to formatting the layout do not count. Tip: writing "1234567890" eight times can
easily and quickly give you the 80 character bounds.

Some examples:

```javascript

// |==============================  80  characters  ==============================|
// 12345678901234567890123456789012345678901234567890123456789012345678901234567890

// A comment related to myVariable... The quick brown fox jumped over the lazy dog.
// The quick brown fox jumped over the lazy dog. The quick brown fox jumped over
// the lazy dog.
var myVariable = 0;
```

```javascript

function myFunction(a, b) {
  // |==============================  80  characters  ==============================|
  // 12345678901234567890123456789012345678901234567890123456789012345678901234567890

  // A comment related to myFunction... The quick brown fox jumped over the lazy dog.
  // The quick brown fox jumped over the lazy dog. The quick brown fox jumped over
  // the lazy dog.

  sum = a + b;  // The length of this line includes the code and this comment.
  return sum;   // This line can be up to ................................ this long.
}
```

## Naming

### Variables etc.

lowerCamelCase

```javascript
var myVariable = 0;
```

### Classes etc.

UpperCamelCase

```javascript
function Apple(type) {
  this.type     = type;
  this.color    = "red";
  this.getInfo  = getAppleInfo;
}

var apple = new Apple('Macintosh');
```

### Constants etc.

SCREAMING_SNAKE_CASE

```javascript
const GRAVITATIONAL_ACCELERATION = 9.81;
```

### Groupings etc.

example_anExample

When you want to group a number of variables / functions / classes / files /
folders / etc. into a group / type / category / namespace / etc., use an
underscore.

```javascript
const fruit_apple;
const fruit_banana;
const fruit_pear;
```

### Hyphen vs underscore

Hyphen:

- Keeps the words on either side distinct.
- Should replace spaces where when they would have ordinarily been used.
- Can be mistaken for subtraction (hence not allowed as variable names in some languages.
- Used for:
  - Folder names.
  - File named not named after internal code content.

Underscore:

- Merges the two words on either side.
- Should be used when creating something that should be considered one entity, e.g. a variable name.
- Used for:
  - Variable / function / Class names.
  - File names named after internal code content.
  - Groupings, in code and otherwise.

## Spacing

### Block indentation

2 spaces.

```javascript
function Apple(type) {
  this.type     = type;
  this.color    = "red";
  this.getInfo  = getAppleInfo;
}

var apple = new Apple('Macintosh');
```
