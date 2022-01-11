Steps to Reproduce Yourself

1. Create directory (mkdir node-typescript-base and cd node-typescript-base)

2. Generate package.json (npm init -y)

3. yarn add typescript

4. edit package.json to add scripts for "build": "tsc index.ts"
   and "watch": "tsc --watch --outDir build \*.ts" and "start": "node build/index.js"

5. Add tsconfig.json with basic settings

6. Generate .vscode debugger file w/ Node selected as runtime

Partly inspired by https://code.visualstudio.com/docs/typescript/typescript-tutorial
