# How to use 

```js
import { regexValidate, MapOfRegExpValidate } from "@skapxd/regex-validate";

/** @type {boolean} */
const isValid = regexValidate({
    stringToValidate: "test@test.test",
    regExp: MapOfRegExpValidate.email, // any regular expression -> /any/ 
});

console.log({ isValid });
```