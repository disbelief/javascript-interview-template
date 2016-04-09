# Javascript Interview Template

A very simple template of front-end boilerplate enabling you to 
get to the meat of an interview solution without spending time
on the plumbing.

### Includes:
- babel for ES6+ transpilation
- browserify for bundling, dependencies, and node goodies in the browser
- vanilla CSS only (for now)
- basic HTML page

### Usage:

Main entry-point is `src/app.js`

Use `npm run build` to compile javascript. Will be passed through babel transpiler.

#### If ES5 Only:

Write your app with `src/app.es5.js` as the main entry-point instead.

Use `npm run build-es5` to compile the javascript. Code **will not** be passed through the babel transpiler. Only browserify will be used for requires and bundling.


copyright 2016 Michael Lawlor

