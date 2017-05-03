# Naming

## Contents

  * [Naming styles](#naming-styles)
  * [Files and folders](#Files-and-folders)
  * [Hyphen vs underscore](#Hyphen-vs-underscore)

## Code

| `an_example_name` | `An_example_name` | `AN_EXAMPLE_NAME` | `anExampleName`   | `AnExampleName`   |
| ----------------- | ----------------- | ----------------- | ----------------- | ----------------- |
| variables (etc)   |                   | constants         |                   | classes [1]       |
| functions (etc)   |                   | definitions       |                   | types             |
| classes [2]       |                   |                   |                   |                   |
| objects           |                   |                   |                   |                   |
| structures        |                   |                   |                   |                   |

[1] - Instantiable classes.
[2] - Functional classes.

## Files and folders

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
