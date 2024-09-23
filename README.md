# Installation

```sh
npm install -D @ayka/tsconfig
```

```sh
yarn add --dev @ayka/tsconfig
```

```sh
pnpm add -D @ayka/tsconfig
```

# Configuration

Add to your `tsconfig.json`:

## ESM

```json
"extends": "@ayka/tsconfig/esm.json"
```

## CommonJS

```json
"extends": "@ayka/tsconfig/cjs.json"
```

## Unspecified

```json
"extends": "@ayka/tsconfig/base.json"
```
