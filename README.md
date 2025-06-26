# Typescript Introduction

## Get started

- `npm init es6`
- `pnpm install -D typescript tsx @types/node`
- `pnpm install -D @tsconfig/node-lts`

`tsconfig.json`

```json
{
  "extends": "@tsconfig/node-lts/tsconfig.json",
  "compilerOptions": {
    "outDir": "./dist"
  },
  "include": ["./src/**/*"]
}
```
