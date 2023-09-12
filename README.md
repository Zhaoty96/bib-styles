# myBibStyle.bst: RevTeX4 Bibliography Styles

This repository hosts both original and modified RevTeX4 `.bst` files. 

## Motivation
While the official RevTeX 4.1 and 4.2 templates display full author lists, earlier versions of RevTeX 4 would truncate the list if there were more than 10 authors. To accommodate preferences for concise author listings, I've reintroduced this truncation feature.

> **Note**: _APS editors prefer full author lists for references with 15 or fewer authors. For references with more than 15 authors, it's recommended to use the phrase "and others" after listing the first set of authors._

## `myREVTeX4-2.bst`
### Updates (09/11/2023)
- Replace the `FUNCTION{format.names}` from the RevTeX4's `apsrev.bst`. This truncates the author list to a maximum of 10 names.
- Automated the process: No more manual removal of authors in `.bib` files! This is especially beneficial for LVK papers.

## Other `.bst` files:
- `apsrev.bst` - From RevTeX4.
- `apsrev4-1.bst` - From RevTeX4-2.
- `apsrev4-2.bst` - From RevTeX4-2.
