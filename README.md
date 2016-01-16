# marked

[![Build Status](https://travis-ci.org/cakecatz/marked.svg?branch=master)](https://travis-ci.org/cakecatz/marked)

## Usage

```js
const Marked = require('marked');
const marked = new Marked({ /* options */ });

const md_content = `
# Hello, World!
`;

marked.parse( md_content );
```
