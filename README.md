# prettier-config

⚙️ Reusable prettier config

## Installation

```bash
npm i @rwxmad/prettier-config --save-dev
```

## Usage

Add a key in your `package.json` file

```json
"prettier": "@rwxmad/prettier-config"
```

**OR**

If you don’t want to use package.json, you can use any of the supported extensions to export a string, e.g. .prettierrc.json:

```json
"@rwxmad/prettier-config"
```

**OR**

Create a **prettier.config.js** or **.prettierrc.js** file and export an object

```js
import config from "@rwxmad/prettier-config";

export default {
  ...config,
  semi: false,
};
```
