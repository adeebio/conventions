# Formatting

## Contents

  * [Brackets](#brackets)
  * [Line length](#line-length)

## Brackets

By examples...

### Function arguments

```javascript
function myFunction(a, b) {
    sum = a + b;
    return sum;
}
```

### Loops

```javascript
for (i = 0; i < 5; i++) {
    text += "The number is " + i + "<br>";
}
```

## Spacing

### Block indentation

4 spaces.

```javascript
function Apple(type) {
    this.type     = type;
    this.color    = "red";
    this.getInfo  = getAppleInfo;
}

var apple = new Apple('Macintosh');
```

## Line length

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

```javascript
/*
|==============================  80  characters  ==============================|
12345678901234567890123456789012345678901234567890123456789012345678901234567890
*/

var myVar = 0; // A single line comment example looks like this.

var myVar2;       // Comments for lines of code in a block look like this.
var myVariable3;  // They contribute towards the total line length.
var myVarFour;    // They are aligned to two spaces after the longest code line.
```
