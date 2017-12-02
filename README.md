# math-from-string

Parses strings as mathematical expressions. This module supports both Node and browser use.

## Usage

### Node

`npm i math-from-string`

```
let mathfromString = require("math-from-string");
```

Minified version:

```
let mathfromString = require("math-from-string/dist/math-from-string.min");
```

### Browser

```
import "math-from-string";
```

Minified version:

```
import "math-from-string/dist/math-from-string.min";
```

Script tag:

```
<script src="node_modules/math-from-string/dist/math-from-string.min.js"></script>
```

## Documentation

See the [documentation](http://grafluxe.com/o/doc/math-from-string/global.html).

## Notes

- This project is lightweight and dependency free.
- The source code is written in ES6 and transpiled with Babel.

## Samples

#### mathfromString(*str*);

```
mathfromString("2+2");
// 4

mathfromString("(5-3)*2");
// 4

mathfromString("5-3*2");
// -1

mathfromString("-10+-2");
// -12
```

## License

Copyright (c) 2014, 2017 Leandro Silva (http://grafluxe.com)

Released under the MIT License.

See LICENSE.md for entire terms.
