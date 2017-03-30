# General coding conventions

## Contents

  * [Formatting](#formatting)
  * [Naming](#naming)
  * [Spacing](#spacing)

## Formatting

## Naming

### Variables etc.

lowerCamelCase

```javascript
var myVariable = 0;
```

### Classes etc.

UpperCamelCase

```javascript
function Apple (type) {
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

## Spacing

### Block indentation

2 spaces.

```javascript
function Apple (type) {
  this.type     = type;
  this.color    = "red";
  this.getInfo  = getAppleInfo;
}

var apple = new Apple('Macintosh');
```
