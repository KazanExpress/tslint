# @kazanexpress/tslint

> A typescript linter rules for projects of KazanExpress frontend division

## Installation

```bash
npm i -D @kazanexpress/tslint
```

To add the linter rules to your current project, you need create `tslint.json` file in your project's root directory:

```json
{
  "extends": [
    "@kazanexpress/tslint"
  ]
}

```

## Usage

```bash
npx tslint -c tslint.json index.ts
```

or use [vscode plugin](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin)

![wallhaven-342160](/assets/vscode-plugin.png)
