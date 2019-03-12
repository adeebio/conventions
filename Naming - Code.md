# Naming - Code

### Identifiers

| Example name      | Identifiers |
| ----------------- | ----------- |
| **`anExampleName`**   | <ul><li>variables (etc)</li><li>functions (etc)</li><li>classes [2]</li><li>objects</li><li>structures</li></ul> | 
| **`AnExampleName`**   | <ul><li>classes [1]</li><li>types</li></ul> | 
| **`AN_EXAMPLE_NAME`** | <ul><li>constants</li><li>definitions</li></ul> | 

[1] - Classes that can be instantiated.  
[2] - Classes that cannot / are not meant to be instantiated. For example, a class consisting solely of static functions.

### Groupings

An (additional) underscore is used for groupings.

```javascript
var fruit_apple;
var fruit_banana;
var fruit_pear;

const PHYSICS__STANDARD_GRAVITY 9.81;
const PHYSICS__SPEED_OF_LIGHT   299792458;
```

### Acronyms

Acronyms should be lowercase with the first letter capitalised when neccessary.

```javascript
var googleUrl = 'https://google.com';
```
