# JavaScript notes

- .pop() - delete last record in the array. You can store it inside variable.
- .shift() - delete first record in the array. You can store it inside variable.
- .unshift() - add record at first place inside array.
- .push() - add data to the end of the array
- [.slice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice) - slice an array
- global variables - define outside function OR when you want GlobalVariable inside function do it without var. <br>
(Don't use var anymore. Use let and const)

``` javascript
var globalTest1 = 3;

  function() {
    globalTest2 = 5;
    var localTest1 = 2;
  }
  
```

- undefined - when JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". If you concatenate a string with an undefined variable, you will get a literal string of "undefined".
