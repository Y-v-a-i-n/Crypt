# Crypt

**How to use the module :**

```js
const crypt=require("./index.js");
var encryptedMessage=crypt.encrypt("theKey","theMessage")
console.log(encryptedMessage)
//output : 㒐⼠ⷄ⋤ⷄ㐜㐜⯴⺬ⷄ
var decryptedMessage=crypt.decrypt("theKey",encryptedMessage)
console.log(decryptedMessage)
//output : theMessage
```