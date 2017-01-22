# rollup-cheat-sheet
A quick reference to the options/plugins for the JS module bundler Rollup

Basic Rollup options:

| Option                   | Command-Line                   | Config/API                 | Default        | Possible Options        |
| ------------------------ | ------------------------------ | -------------------------- | -------------- | ----------------------- |
| show version number      | -v, --version                  | N/A                        | N/A            | N/A                     |
| Use config file          | -c [path], --config [path]     | N/A                        | N/A            | N/A                     |
| Watch files and rebundle | -w, --watch                    | N/A                        | Off            | N/A                     |
| Input (entry file)       | -i [path], --input [path]      | entry: 'path/to/entry.js'  | N/A (required) | N/A                     |
| Output                   | -o [path], --output [path]     | dest: 'path/to/bundle.js'  | Stdout         | N/A                     |
| Format                   | -f [format], --format [format] | format: 'cjs'              | es (ES module) | amd, cjs, es, iife, umd |
