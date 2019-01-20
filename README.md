# faster-cookie-parser
A cookie parser which is finally simple and short. This library is currently only 10 lines long.

## Install

```bash
npm install --save faster-cookie-parser
```

## Usage

```js
const cookieParser = require('faster-cookie-parser');
let cookie = cookieParser("token=123token; user=AlexisTM");
/*
{
    token: "123token",
    user: "AlexisTM"
}
 */
```

# Credits

- [@AlexisTM](http://github.com/AlexisTM)
