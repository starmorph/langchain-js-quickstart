## setup node project
npm init es6 -y && npm install langchain openai dotenv @types/node typescript ts-node
npx tsc --init --rootDir src --outDir ./dist --esModuleInterop --lib ES2020 --target ES2020 --module nodenext --noImplicitAny true

### add to package.json
```
  "scripts": { 
      "build": "tsc", 
      "start": "node ./dist/app.js", 
      "dev": "ts-node --esm ./src/app.ts"
  },
  ```
### Create an app.ts source file in the src folder. Add code to it to display a test string.
mkdir src 
echo "console.log('Welcome to the LangChain.js tutorial by LangChainers.')" > src/app.ts

### boot up 
npm run build
npm run start

## blog post tutorial https://langchainers.hashnode.dev/getting-started-with-langchainjs

