# LINT: LIterature reference managemeNT
simple console based literature reference manager. Capable of opening corresponding pdf files.

- Single source of truth is the biblatex file: **literature.bib**
- An overview over available biblatex entriey is given in **literature.md**
- Additional entries are:
  - file (path of the pdf file)
  - keywords (included in the search string)

## Setup
Set environment variable **LITERATURE**, pointing to the **literature.bib** file.
The pdf viewer can be chosen by modifying the **PDFviewer** entry in the "environment variables" section of "LINT.py"

## Latex templete
Is given in "latex", which also uses the environment variable **LITERATURE**. Build with **make**
