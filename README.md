swapview is a simple program to view processes' swap usage on Linux.

This is the version for daily use. For implementations in different programming languages, see [swapview-rosetta](https://github.com/lilydjwg/swapview-rosetta).

Tips: you can continuously monitor swap usage in a terminal with

```sh
watch -n 1 "swapview | tail -\$((\$LINES - 2)) | cut -b -\$COLUMNS"
```
