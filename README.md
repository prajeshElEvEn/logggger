# logggger

> `4 g's for 4 levels`

a npm package for logging beautiful messages in the terminal.

## installation

```bash
npm i logggger
```

## usage

```javascript
const { log, success, warn, error } = require("logggger");

log("a log message");
success("a success message");
warn("a warn message");
error("a error message");
```

### levels

- log

```javascript
const { log } = require("logggger");

log("a log message");
```

- success

```javascript
const { success } = require("logggger");

success("a success message");
```

- warn

```javascript
const { warn } = require("logggger");

warn("a warn message");
```

- error

```javascript
const { error } = require("logggger");

error("a error message");
```

## examples

- express app

```javascript
const express = require("express");
const { success } = require("logggger");

const app = express();
const port = 5000;

app.listen(port, () => {
  log(`Server running at http://127.0.0.1:${port}`);
});
```

## resources

- [chalk v4.1.2](https://www.npmjs.com/package/chalk/v/4.1.2)

## license

This project is licensed under the [MIT License](./LICENSE).

## contributions

Contributions are welcome! Feel free to open an issue.

## Author

[@prajesh](https://bit.ly/prajesheleven)
