# rollup-cheat-sheet
A quick reference to the options/plugins for the JS module bundler Rollup

Basic Rollup options:

| Option                   | Command-Line                   | Config/API                 | Default        |
| ------------------------ | ------------------------------ | -------------------------- | -------------- |
| show version number      | -v, --version                  | N/A                        | N/A            |
| Use config file          | -c [path], --config [path]     | N/A                        | N/A            |
| Watch files and rebundle | -w, --watch                    | N/A                        | Off            |
| Input (entry file)       | -i [path], --input [path]      | entry: 'path/to/entry.js'  | N/A (required) |
| Output                   | -o [path], --output [path]     | dest: 'path/to/bundle.js'  | Stdout         |
| Format                   | -f [format], --format [format] | format: 'cjs'              | es (ES module) |
