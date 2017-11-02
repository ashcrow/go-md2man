go-md2man
=========

** Work in Progress **
This still needs a lot of help to be complete, or even usable!

Uses blackfriday to process markdown into man pages.

### Building

```
make vendor # To install govend and update vendor libraries
make build  # Creates the go-md2man binary
```

### Usage
```
./md2man -in /path/to/markdownfile.md -out /manfile/output/path
```
### How to contribute

We use [govend](https://github.com/govend/govend) for vendoring Go packages.

How to update dependencies: `govend -v -u --prune` or `make vendor`
