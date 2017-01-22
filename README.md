# rollup-cheat-sheet
A quick reference to the options/plugins for the JS module bundler Rollup

Basic Rollup options:

| Option              | Command-Line      | Config/API                      | Default | Possible Options        |
| ------------------- | ----------------- | ------------------------------- | ------- | ----------------------- |
| Show version number | -v                | N/A                             | N/A     | N/A                     |
| Use config file     | -c [path]         | N/A                             | N/A     | N/A                     |
| Watch (rebundle)    | -w                | N/A                             | Off     | N/A                     |
| Input (entry file)  | -i src/main.js    | entry: 'path/to/entry.js'       | N/A *   | N/A                     |
| Output              | -o dist/bundle.js | dest: 'path/to/bundle.js'       | Stdout  | N/A                     |
| Format              | -f cjs            | format: 'cjs'                   | es      | amd, cjs, es, iife, umd |
| External (exclude)  | -e moment,jquery  | external: ['momment', 'jquery'] | N/A     | N/A                     |
