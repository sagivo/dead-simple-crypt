#Dead Simple Crypt

dead simple. fast. light

  - No need for heavy libraries.
  - Simple to use.
  - Customize it easily. 


##Get Started

Simply install via [npm](https://npmjs.org/):

```javascript
npm install simple-crypt
```
Load AC and you're ready to go!
```javascript
var deadSimpleCrypt = require('dead-simple-crypt');
```

Than simply use

Examples are provided [here](https://github.com/sagivo/accept-bitcoin/tree/master/examples)
```javascript
var plain = "I see dead people!";
var blob = deadSimpleCrypt.encrypt(plain); //your encrypted string
deadSimpleCrypt.decrypt(blob); //back to original string
```

or, with optional password:
```javascript
pass = 'some password';
var plain = "I see dead people!"; 
var blob = deadSimpleCrypt.encrypt(plain, pass); //your encrypted string
deadSimpleCrypt.decrypt(blob, pass); //back to original string
```


##Contribute
Please do. Fork it, star it, share it and add your code to the project. Help others.  

##License
MIT