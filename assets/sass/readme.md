# MAIN FILE

The main file (usually labelled main.scss) should be the only Sass file from the whole code base not to begin with an underscore. This file should not contain anything but @import and comments.

Files should be imported according to the folder they live in, one after the other in the following order:

1. abstracts/
2. vendors/
3. base/
4. layout/
5. components/
6. pages/
7. themes/

In order to preserve readability, the main file should respect these guidelines:

- one file per @import;
- one @import per line;
- no new line between two imports from the same folder;
- a new line after the last import from a folder;
- file extensions and leading underscores omitted.