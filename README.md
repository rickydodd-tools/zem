# Zip 'em! (zem)
zem is a tool for quickly and recursively zipping files with specific file extensions.

## Examples
These examples can also be obtained from the command-line with `zem --tldr`.

- Create a zip file named "htmls.tar" that contains all files with the ".html" extension.
  ```bash
  zem -o "htmls.tar" -p "*.html"
  ```

- Create a zip file named "web.tar" that contains all files with the ".html" and ".css" extensions.
  ```bash
  zem -o "web.tar" -n 2 -p "*.html" "*.css"
  ```
## To-Do
- [ ] Add option to specific root directory.
- [ ] Add option(s) for compression.
