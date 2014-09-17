#Simple Crypt

simple. fast. light

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
var simpleCrypt = require('simple-crypt');
var sc = new simpleCrypt('ENTER_A_PASSWORD_TO_GENERATE_CRYPTION');
```

Than simply use

Examples are provided [here](https://github.com/sagivo/accept-bitcoin/tree/master/examples)
```javascript
var plain = "I see dead people!";
var blob = sc.encrypt(plain); //your encrypted string
sc.decrypt(blob); //back to original string
```

##Contribute
Please do. Fork it, star it, share it and add your code to the project. Help others.  

##License
MIT