# TypeScript build demo

This is the basic environment required to build TypeScript files.  For more information, see the [gulp page](http://www.typescriptlang.org/docs/handbook/gulp.html) in the handbook.

## Installing dependencies

First of all, you need [Node.js](https://nodejs.org/en/download/).  Then, once you have node installed, `cd` into the root directory and run
```bash
npm install -g gulp-cli
npm install
```
## Running

After installing dependencies, `cd` into the root directory and run
```bash
gulp && npm start
```
`gulp` transpiles `src/main.ts` into `dist/main.js` and then `npm start` runs `dist/main.js`.
