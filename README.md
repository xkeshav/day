# Day - @xkeshav/day - A JSR package

This is a minimal sample package for new package ecosystem  JavaScript Registry (JSR)  by Deno, it works both i9n javascript and typescript.

access to JSr is limited and based on invite.

## What this package does

this package have one property `oneDay` which return total number of millisseocnds in a daty i.e. 86400000

## How to install

> npx jsr i @xkeshav/day


above command will add entry in your **package.json** file as below

```json
 "dependencies": {
    "@xkeshav/day": "npm:@jsr/xkeshav__day@^1.1.0"
  }
```
## How to use

```js
import { oneDay } from "@xkeshav/day";

// named export 
console.log({oneDay});

```


## References

- [@xkeshav/day](https://jsr.io/@xkeshav/day)
- [jsr.io](https://jsr.io/)
