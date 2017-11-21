# Illegal characters

### Summary

Do not use any of the following characters when naming files or folders:

`/`, `?`, `<`, `>`, `\`, `:`, `*`, `|`, `"` and `^`.


### Windows

- NTFS: `/`, `?`, `<`, `>`, `\`, `:`, `*`, `|`, `"` and any character you can type with the Ctrl key.
- FAT: " + `^`.

- NTFS: File and folder names: Up to 256 characters long.
- FAT: File and folder names: Up to 255 characters long.

- NTFS + FAT: Full path: Up to 260 characters long.

- NTFS + FAT: Not allowed:
  - Space at the end of a name.
  - Period at the end of a name.
  
- Reserved names: com1, com2, com3, com4, com5, com6, com7, com8, com9, lpt1, lpt2, lpt3, lpt4, lpt5, lpt6, lpt7, lpt8, lpt9, con, nul, and prn

### OS X

- `:` is the only illegal character for files and folder names.

- Also, files and folders:
  - Up to 255 characters in length.
  - Not permitted to begin with a `.`.

---

### References

- [acronis.com - Illegal Characters on Various Operating Systems](https://kb.acronis.com/content/39790)
