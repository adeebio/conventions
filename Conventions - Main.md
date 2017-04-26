# Conventions - Main

## Contents

  * [Naming](#naming)
  * [Spacing](#spacing)

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

#### Hyphen:

- Keeps the words on either side distinct.
- Should replace spaces where when they would have ordinarily been used.
- Can be mistaken for subtraction (hence not allowed as variable names in some languages.
- Used for:
  - Folder names.
  - File named not named after internal code content.

#### Underscore:

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
