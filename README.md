# RUN
run `$ npm start`  

This will run `npm install` && `npx nx g @nx/express:app my-express-api --directory=apps/my-express-api --verbose`

# YOU GET GETZ
```bash
> npx nx g @nx/express:app my-express-api --directory=apps/my-express-api --verbose


>  NX  Generating @nx/express:application

✔ What should be the project name and where should it be generated? · my-express-api @ apps/my-express-api

 >  NX   Cannot read properties of undefined (reading 'test')


TypeError: Cannot read properties of undefined (reading 'test')
    at createJestConfig (/Users/nalberg/Sites/nx-test/node_modules/@nx/jest/src/generators/configuration/lib/create-jest-config.js:47:42)
    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
    at async configurationGeneratorInternal (/Users/nalberg/Sites/nx-test/node_modules/@nx/jest/src/generators/configuration/configuration.js:60:5)
    at async applicationGeneratorInternal (/Users/nalberg/Sites/nx-test/node_modules/@nx/node/src/generators/application/application.js:325:26)
    at async applicationGenerator (/Users/nalberg/Sites/nx-test/node_modules/@nx/node/src/generators/application/application.js:265:12)
    at async applicationGeneratorInternal (/Users/nalberg/Sites/nx-test/node_modules/@nx/express/src/generators/application/application.js:57:29)
    at async /Users/nalberg/Sites/nx-test/node_modules/nx/src/command-line/generate/generate.js:241:26
    at async handleErrors (/Users/nalberg/Sites/nx-test/node_modules/nx/src/utils/params.js:9:16)
    at async Object.handler (/Users/nalberg/Sites/nx-test/node_modules/nx/src/command-line/generate/command-object.js:13:22)

```
