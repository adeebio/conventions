# Naming

## Contents

  * [Code](#code)
  * [Files and folders](#files-and-folders)
  * [Hyphen vs underscore](#hyphen-vs-underscore)

## Code

### Quick reference

| `anExampleName`   | `AnExampleName`   | `AN_EXAMPLE_NAME` | `an_example_name` | `An_example_name` |
| ----------------- | ----------------- | ----------------- | ----------------- | ----------------- |
| variables (etc)   | classes [1]       | constants         |                   |                   |
| functions (etc)   | types             | definitions       |                   |                   |
| classes [2]       |                   |                   |                   |                   |
| objects           |                   |                   |                   |                   |
| structures        |                   |                   |                   |                   |

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

### Details

## Files and folders

### Quick reference

```
+ aFolderContainingCode
  - main.js
  + scripts
    - main.js
    - anotherScript.js
    - andAnother.js
    + evenMore
      - additional1.js
      - additional2.js
      - ...
      
+ group_codingFolder1
+ group_codingFolder2
+ group_codingFolder3

+ A folder containing regular files
  - Introduction.txt
  - Contents.txt
  - Chapter One.txt
  - ...
  
+ A_folder_containing_regular_files
  - Introduction.txt
  - Contents.txt
  - Chapter_one.txt
  - ...
  
+ Group__Regular Folder 1
+ Group__Regular Folder 2
+ Group__Regular Folder 3
```

## Hyphen vs underscore

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
