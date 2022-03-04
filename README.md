# pratice-typescript
a project to learn and practice typescript

## Pre-requisite
- install long term support version of nodejs
- install vs code 
  
## Package Installed
```sh
npm i typescript
```

## How the Project is Organized
- The `tutorials` folder will contain the step by step sequentially
- Actual Code to be tried out will be present in `src` folder 
- in the project root create a `tsconfig.json` by typing `tsc --init`
- make sure the below properties as set as:
```json
{
    "compilerOptions":{
        "outDir": "./dist",
        "rootDir": "./src",
    }
}
```
- update the `package.json>script` section as below
```json
{
  "scripts": {
    "start:watching": "npx tsc -w",
    "start": "node ./dist/index.js"
  }
}
```

## How to run the project
- write your ts codes in a file in `src` folder
- the compiled ones will be present in `dist` folder
- to start tranpiling all the ts files in the src folder run `npm run start:watching`
- to run the index.js in the dist folder run `npm start`
- try out code in `src\index.ts` and later move to relevant folders as per your need

## Reference
- [Project Setup reference](https://www.youtube.com/watch?v=gp5H0Vw39yw&list=PLU5QVLLpcQufmx8R2tfcL-Te2HEzfASZp&index=20) 
