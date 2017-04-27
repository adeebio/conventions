# Naming

## Contents

  * [Naming styles](#naming-styles)
  * [Hyphen vs underscore](#Hyphen-vs-underscore)

## Naming styles

| `an_example_name` | `An_example_name` | `AN_EXAMPLE_NAME` | `anExampleName`   | `AnExampleName`   |
| ----------------- | ----------------- | ----------------- | ----------------- | ----------------- |
| variables (etc)   | classes<sup>[1]</sup>| constants         |                   |                   |
| functions (etc)   |                   | definitions       |                   |                   |
| objects           |                   |                   |                   |                   |

[1] - Instantiable classes.

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
