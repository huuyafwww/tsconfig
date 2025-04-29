# @huuyafwww/tsconfig


[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

This repository is a detailed package of tsconfig for me.


## packages

|Name|Include rule|Package|
|---|---|---|
|[`@huuyafwww/tsconfig-common`](packages/tsconfig-common)|Node.js|[![npm version](https://badge.fury.io/js/@huuyafwww%2Ftsconfig-common.svg)](https://www.npmjs.com/package/@huuyafwww/tsconfig-common)|
|[`@huuyafwww/tsconfig-react`](packages/tsconfig-react)|React|[![npm version](https://badge.fury.io/js/@huuyafwww%2Ftsconfig-react.svg)](https://www.npmjs.com/package/@huuyafwww/tsconfig-react)|
|[`@huuyafwww/tsconfig-next`](packages/tsconfig-next)|Next.js|[![npm version](https://badge.fury.io/js/@huuyafwww%2Ftsconfig-next.svg)](https://www.npmjs.com/package/@huuyafwww/tsconfig-next)|

## Usage

<details>

<summary>Node.js</summary>

### Installation

```sh
pnpm add -D @huuyafwww/tsconfig-common @types/node
```

### tsconfig.json

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": [
    "@huuyafwww/tsconfig-common",
  ],
  "compilerOptions": {
    "types": [
      "@types/node"
    ]
  }
}
```

</details>

<details>

<summary>Next.js</summary>

### Installation

```sh
pnpm add -D @huuyafwww/tsconfig-next
```

### tsconfig.json

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": [
    "@huuyafwww/tsconfig-next",
  ]
}
```

</details>

## License

[MIT](https://github.com/huuyafwww/tsconfig/blob/main/LICENSE)
