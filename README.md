# TypeScript Test Cases
TypeScript boilerplate for test cases.

1. Run scripts.
2. Create a test case file (TypeScript file) based on the template (testcase-template.ts).
3. Add TypeScript code into the wrapper.
4. Import created test case file into the imports.ts.

## File structure
- src - place your TypeScript files here,
- dist - auto-generated JavaScript files,
- types - examples of test cases

## Prerequisites
- Node.js
- npm

## Installation
npm install

## Scripts
### Run TypeScript compiler
The TypeScript compiler (tsc) converts the instructions written in TypeScript (src directory) to its JavaScript equivalent (dist directory).

```npm start```

### Watch and run JavaScript files
Watch function is automatically running/restarting index.js file (Node.js application) when file changes in the dist directory are detected.

```npm run watch```

## Files

##### imports.ts

Import your test case file here. 
Comment (disable) unused imports (test case files).

##### *.ts file (test case file)

Place your TypeScript code inside the wrapper.
```
export function run() {

// place your TypeScript code here

};
```