1. Will alert be shown?

```javascript
if ("0") {
  alert( 'Hello' );
}
```

```
  --> A. Yes
  B. No
  C. Will be an error
```

2. How many parameters can be passed to the function?

```
  A. none
  B. one for each argument
  --> C. as much as you like
  D. one
```

3. Statement `A ? B : C` is equivalent to:

```
  --> A. if (A) {B} else {C}
  B. if (A==B) C
  C. if (A!=B) C
  D. if (A) {B; C}
```

4. To see if three variables are equal we would use:

```
  A. A=B=C
  --> B. (A==B) && (B==C)
  C. (A=B) && (B=C)
  D. (A==B) & (B==C)
```

5. What is this code going to show?

```javascript
  let fruits = ["Apples", "Pear", "Orange"];
  let shoppingCart = fruits;
  
  shoppingCart.push("Orange");
  
  alert( fruits.length );
```

```
  A. 1
  B. 2
  C. 3
  --> D. 4
```

6. When executed, what value will be alerted to the screen?

```javascript
  function foo () {
    let a = 10;
    
    if (a > 5) {
      a = 7;
    }
    alert(a);
  }
```

```
  --> A. 7
  B. 10
  C. null
  D. undefined
```

7. What's alerted to the screen?

```javascript
  function getFunc() {
    const a = 7;
    
    return b => {
      alert(a + b);
    }
  }
  
  const f = getFunc();

  f(5);
```

```
  A. 5
  B. 7
  --> C. 12
  D. null
  E. undefined
```

8. `Number("1") - 1 === 0;`

```
  --> A. true
  B. false
  C. ReferenceError
  D. undefined
```

9. What is the result of the following?

```javascript
  const y = ["0", "1", "2", "3", "4", "5"]
    .map(x => +x)
    .filter(x => x && x % 2 === 0)
    .reduce((accum, item) => accum * item);

  console.log(y);
```

```
  A.  1,2,3,4,5
  B.  0,2,4
  C.  0
  --> D.  8
  E.  16
  F.  undefined
```
  
10. There’s an object:

```javascript
  const obj = {
    1: '1',
    2: '2',
    3: '3'
  };
```

What the value of `obj.length`?
```
  --> A. undefined
  B. 3
  C. Will throw "ReferenceError: length is not defined"
  D. null
```

11. How to get a number of array elements?

```
  A. arr.length()
  --> B. arr.length
  C. arr.size()
  D. sizeof(arr)
```
  
12. There’s an array: `const numbers = [ 1, 2, 3 ];` 
Choose the right way of accessing the first element.

```
  A. numbers.0
  --> B. numbers[0]
  C. numbers(0)
```


13.  Chose the expression that returns true

```
  A. typeof 1 === 'int'
  --> B. typeof 1 === 'number'
  C. typeof 1 === 'long'
```


14. Choose the right way of creating an array with a single element:

```
  --> A. const аrr = [ 5 ]
  B. const аrr = new Аггау(5)
  C. const аrr = new [ 5 ]
```

