# escape-string

Escape string special characters.

## Install

```
npm install escape-string --save
```

## Usage

```js
import escapeString from 'escape-string';
// or `var escapeString = require('escape-string').default;`

escapeString(` \\ ' " \r \n `);
// => ` \\\\ \\' \\" \\r \\n `

Function(`return '${ escapeString(` \\ ' " \r \n `) }';`)();
// => ` \\ ' " \r \n `
```
