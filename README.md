# ts-node

Typescript node project

## Prequisites

- You should have Node and npm installed
- You should be familiar with Node and the npm ecosystem
- You have a code editor installed

## Step to set up

1. install `typescript` and `@types/node` in `devDependencies`
2. run `npx tsc -init` to set up `tsconfig.json` file
3. create `index.ts` file, run `mkdir src && touch src/index.ts`  
4. test Compiling Typescript `npx tsc` 
5. install `npm install --save-dev ts-node nodemon`
6. update `package.json` script, `"dev": "nodemon src/index.ts",`
