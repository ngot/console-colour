# Console Colour

`console-colour` is a small package that can be used with [node.js](http://nodejs.org) to control console output. The package can change the output text color.

# Installation and use

Install with [npm](http://npmjs.org) to current directory:

```bash
  npm install console-colour --save
```

Then `require()` package from your script:

```js
  require('console-colour')(String);
```

# Examples

Some examples from the `examples` directory.

# Features

## Colors

Control colored output. See also `examples/colors.js`.

Simple color changing:

```js
  console.log("bold".bold);
```

This will output `bold` in bold.

For more usage ,please see `examples/colors.js`.