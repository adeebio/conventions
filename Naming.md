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
  + Group - Regular Folder 1
  + Group - Regular Folder 2
  + Group - Regular Folder 3
  
+ A_folder_containing_regular_files
  - Introduction.txt
  - Contents.txt
  - Chapter_one.txt
  - ...
  + Group_-_Regular_Folder_1
  + Group_-_Regular_Folder_2
  + Group_-_Regular_Folder_3
```
### Groupings

A hyphen is used for groupings. (See the quick reference of this section.)

## Names of things

Names of things such as:

- Git repositories.
- Domain names.
- ...

... should be in lower case with the words separated with hyphens. For example:

- `my-git-repository`
- `my-lambda-function.aws.com`

__*UNLESS*__ ... it can be considered a title. In which case, all lowercase, no spaces or underscores. Hypens for grouping. For example:

- `mycoolapp.com`
- `myusername@domain.com`
- `@myhandle`
- `@company-product1`
- `@company-product2`

### Quick reference

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
