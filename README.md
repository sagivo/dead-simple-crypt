#Dead Simple Crypt

dead simple. fast. light

  - No need for heavy libraries. Using aes-256-cbc protocol. 
  - Simple to use.
  - Customize it easily. 
  - Only 2 methodes `encrypt(string, optionalPass)` and `decrypt(string, optionalPass)`


##Get Started

Simply install via [npm](https://npmjs.org/):

```javascript
npm install simple-crypt
```
Load it and you're ready to go!
```javascript
var deadSimpleCrypt = require('dead-simple-crypt');
```

##Examples

```javascript
var plain = "I see dead people!";
var blob = deadSimpleCrypt.encrypt(plain); //your encrypted string
deadSimpleCrypt.decrypt(blob); //back to original string
```

or, with optional password:
```javascript
var pass = 'some password';
var plain = "I see dead people!"; 
var blob = deadSimpleCrypt.encrypt(plain, pass); //your encrypted string
deadSimpleCrypt.decrypt(blob, pass); //back to original string
```


##Disclosure
This is best for simple use needs. In case you need more complicate solution do your research before.  

##Contribute
Please do. Fork it, star it, share it and add your code to the project. Help others.  

##License
MIT
