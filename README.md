# rollup-cheat-sheet
A quick reference to the options/plugins for the JS module bundler Rollup

Basic Rollup options:

| Option                   | Command-Line                   | Config/API                 | Default | Possible Options        |
| ------------------------ | ------------------------------ | -------------------------- | ------- | ----------------------- |
| Show version number      | -v, --version                  | N/A                        | N/A     | N/A                     |
| Use config file          | -c [path]                      | N/A                        | N/A     | N/A                     |
| Watch files and rebundle | -w                             | N/A                        | Off     | N/A                     |
| Input (entry file)       | -i [path]                      | entry: 'path/to/entry.js'  | N/A *   | N/A                     |
| Output                   | -o [path]                      | dest: 'path/to/bundle.js'  | Stdout  | N/A                     |
| Format                   | -f [format]                    | format: 'cjs'              | es      | amd, cjs, es, iife, umd |
