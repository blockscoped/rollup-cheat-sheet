# rollup-cheat-sheet
A quick reference to the options/plugins for the JS module bundler Rollup

Basic Rollup options:

| Option              | Command-Line          | Config/API                      |
| ------------------- | --------------------- | ------------------------------- |
| Show version number | -v                    | N/A                             |
| Use config file     | -c [path]             | N/A                             |
| Watch (rebundle)    | -w                    | N/A                             |
| Input (entry file)  | -i src/main.js        | entry: 'src/main.js'            |
| Output              | -o dist/bundle.js     | dest: 'dist/bundle.js'          |
| Format              | -f cjs                | format: 'cjs'                   |
| External (exclude)  | -e moment,jquery      | external: ['momment', 'jquery'] |
| Globals (window.X)  | -g backbone:Backbone, | globals: {backbone: 'Backbone'} |
| Name (for UMD/IIFE) | -n myBundle,          | moduleName: 'myBundle'          |
| ID (for AMD)        | -u my-bundle,         | moduleId: 'my-bundle'           |
| Source Maps         | -m [inline],          | sourceMap: true                 |
