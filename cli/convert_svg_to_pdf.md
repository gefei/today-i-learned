# Convert SVG to PDF on Mac or Linux

First install `librsvg` if necessary. On a Mac, this can be done with brew.

Then you can simply convert by (taken from https://apple.stackexchange.com/a/438164)

```
rsvg-convert -f pdf -o file.pdf file.svg
```
