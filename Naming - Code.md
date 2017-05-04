# Naming

## Contents

  * [Code](#code)
  * [Files and folders](#files-and-folders)
  * [Names of things](#names-of-things)
  * [Hyphen vs underscore](#hyphen-vs-underscore)

## Code

### Quick reference

| `anExampleName`   | `AnExampleName`   | `AN_EXAMPLE_NAME` |
| ----------------- | ----------------- | ----------------- |
| variables (etc)   | classes [1]       | constants         |
| functions (etc)   | types             | definitions       |
| classes [2]       |                   |                   |
| objects           |                   |                   |
| structures        |                   |                   |

[1] - Classes that can be instantiated.  
[2] - Classes that are treated as functions or used as namespaces.

### Groupings

An (additional) underscore is used for groupings.

```javascript
var  fruit_apple;
var  fruit_banana;
var  fruit_pear;

const  PHYSICS__STANDARD_GRAVITY  9.81;
const  PHYSICS__SPEED_OF_LIGHT    299792458;
```
