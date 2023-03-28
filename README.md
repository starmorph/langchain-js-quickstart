## Get Started with Langchain JS 
a basic node.js template to run langchain.js
`app.ts` uses langchain with OpenAI to generate a code snippet, format the response, and save the output (a complete react component) to a file.

1. install dependencies
```npm init es6 -y && npm install langchain openai dotenv @types/node
```
2. setup node project
```
typescript ts-node 
```

```
npx tsc --init --rootDir src --outDir ./dist --esModuleInterop --lib ES2020 --target ES2020 --module nodenext --noImplicitAny true
```

3. Update Package.json

```
  "scripts": { 
      "build": "tsc", 
      "start": "node ./dist/app.js", 
      "dev": "ts-node --esm ./src/app.ts"
  },
  ```

4. Create app.ts in the src folder.
```
mkdir src 
echo "console.log('Welcome to the LangChain.js tutorial by LangChainers.')" > src/app.ts
```

5. boot up 
```
npm run build
npm run start
```

## blog post tutorial https://langchainers.hashnode.dev/getting-started-with-langchainjs

