# TypeScript Test Cases
TypeScript boilerplate for test cases.

## How it works

1. Clone the repository.
2. Run ```npm install```.
3. Run script (npm start).
4. Create a test case file (TypeScript file) based on the template (testcase-template.ts).
5. Add TypeScript code inside the test() function.
6. Import created test case file into the imports.ts.

## File structure
- src - place your TypeScript files here,
- dist - auto-generated JavaScript files,
- src/types - demo test cases

## Prerequisites
- Node.js
- npm

## Installation
npm install

## Scripts

### Run the project 

Just run the following command and the project works. The command runs TypeScript compiler and JavaScript watcher

```npm start```

### Run TypeScript compiler
The TypeScript compiler (tsc) converts the instructions written in TypeScript (src directory) to its JavaScript equivalent (dist directory). It is a part of the ```npm start``` script.

```npm run tsc```

### Watch and run JavaScript files
Watch function is automatically running/restarting index.js file (Node.js application) when file changes in the dist directory are detected. It is a part of the ```npm start``` script.

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