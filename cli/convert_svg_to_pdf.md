# Convert SVG to PDF on a Mac

First install `librsvg` if necessary. This can be done by brew.

```
brew install librsvg
```

Then you can simply convert by (taken from https://apple.stackexchange.com/a/438164)

```
rsvg-convert -f pdf -o file.pdf file.svg
```
