# Add line to file in Terminal

We can add a new line to the end of a file in the terminal with:

```
echo "Your text" >> your-file.md
```

`echo <string>` simply logs a string passed. Then we're passing that output to the `>> <file-name>` (double arrow) function which adds a new line to the passed file name.

Note: `>` (single arrow) overwrites the entire file with the give input.