Small Starter for TypeScript
============================

This is not much a "real" start project. I just use to for examples for blog posts.

### To Initialize

    npm install

### To Build

* `npm tsc:win` - single compile. On Windows `npm run tsc:win`
* `npm run tsc:watch` - to compile and watch. On Windows `npm run tsc:watch:win`

### To run

You may have some build artifacts you want to run. If you are watching files, then just
open a new terminal to run. Otherwise, with a single build, just run on the same terminal.

    node src/test

this is just the single file that comes with the project.

If you want soure maps, just change the `sourceMap` in the `compilerOptions` to true inside
the `tsconfig.json` file.