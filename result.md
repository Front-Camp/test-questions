1. What's the git command that downloads your repository from GitHub to your computer?

```
  A. git push
  B. git fork
  --> C. git clone
  D. git commit
```

2. How do you create a copy of a repository under your own GitHub account?

```
  --> A. Forking it via the GitHub interface.
  B. git fork
  C. git clone
  D. git pull-request
```

3. What's the opposite of git clone, instead of downloading your code from GitHub, 
uploads your changes and code back to GitHub?

```
  --> A. git push
  B. git add
  C. git upload
  D. git status
```

4. How do you check the state of your local git repository since your last commit?

```
  A. git check
  --> B. git status
  C. git commit
  D. git diff
```

5. Which of the following is the correct way to initialize a new Git repository?

```
  A. git add .
  --> B. git init
  C. git commit
```

6. Which of the following commands will stage your entire directory 
and every non-empty directory inside your current directory?

```
  A. git status all
  --> B. git add .
  C. git commit all
```

7. We've just created a new file called "index.html". 
Which of the following will stage this one file so we can commit it?
   
```
  --> A. git add index.html
  B. git add new
  C. git commit index.html
```

8. To get the latest changes from your remote repository, the git command is?

```
  A. git refresh
  B. git pull down
  --> C. git pull origin master
  D. git reset
```  

9. To make a new git branch, the git command is?

```
  --> A. git branch
  B. git -b
  C. git new branch
  D. git checkout branch
```
   
10. What is the correct HTML for adding a background color?

```
  --> A. <body style="background-color:red;">
  B. <body bg="red">
  C. <background>red</background>
```

11. What is the correct HTML for creating a hyperlink?

```
  A. <a url="http://www.test.com">test.com</a>
  B. <a>http://www.test.com</a>
  --> C. <a href="http://www.test.com">test</a>
  D. <a src="http://www.test.com">test.com</a>
```

12. What is the correct HTML for inserting an image?

```
  A. <img href="image.gif" alt="MyImage">
  --> B. <img src="image.gif" alt="MyImage">
  C. <image src="image.gif" alt="MyImage">
  D. <img alt="MyImage">image.gif</img>
```

13. What is the correct HTML for referring to an external style sheet?

```
 A. <style src="mystyle.css">
 --> B. <link rel="stylesheet" type="text/css" href="mystyle.css">
 C. <stylesheet>mystyle.css</stylesheet>
```

14. What is the correct CSS syntax for making all the `"p"` elements bold?

```
  A. p {text-size:bold;}
  B. <p style="text-size:bold;">
  C. <p style="font-size:bold;">
  --> D. p {font-weight:bold;}
```

15. When these elements are rendered, what will be the margin between them?

```html
  <style>
  h1 {
    margin-bottom: 30px;
    }
  h2 {
    margin-top: 20px;
    }
  </style>
  
  <h1>Title</h1>
  <h2>Subtitle</h2>
```

```
  A. 50px, because 20+30=50
  -->B. 30px, because of margin collapse
  C. 20px, because margin-top is more important
```

16. Which selector will target only the last list item?

```html
  <ul>
    <li>Not me.</li>
    <li>Not me.</li>
    <li>Target only me.</li>
  </ul>
```

```
  ---> A. ul li:last-child
  B. ul:last-child li
  C. ul:last-child(li)
```

17. Is there a difference between `"visibility: hidden"` and `"display: none"` properties?

```
  A. No
  --> B. Yes, visibility: hidden will hide element from screen, but it will still take the space, while display: none will not display it at all
  C. Yes, visibility: hidden will hide element from screen, while display: none will not display element, but it will still take the space
```

18. Will alert be shown?

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

19. How many parameters can be passed to the function?

```
  A. none
  B. one for each argument
  --> C. as much as you like
  D. one
```

20. Statement `A ? B : C` is equivalent to:

```
  --> A. if (A) {B} else {C}
  B. if (A==B) C
  C. if (A!=B) C
  D. if (A) {B; C}
```

21. To see if three variables are equal we would use:

```
  A. A=B=C
  --> B. (A==B) && (B==C)
  C. (A=B) && (B=C)
  D. (A==B) & (B==C)
```

22. What is this code going to show?

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

23. When executed, what value will be alerted to the screen?

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

24. What's alerted to the screen?

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

25. `Number("1") - 1 === 0;`

```
  --> A. true
  B. false
  C. ReferenceError
  D. undefined
```

26. What is the result of the following?

```javascript
  const y = ["0", "1", "2", "3", "4", "5"]
    .map(x => +x)
    .filter(x => x && x % 2 === 0)
    .reduce((accum, item) => accum * item);

  console.log(y);
```

```
  A. 1,2,3,4,5
  B. 0,2,4
  C. 0
  --> D. 8
  E. 16
  F. undefined
```
  
27. There’s an object:

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

28. How to get a number of array elements?

```
  A. arr.length()
  --> B. arr.length
  C. arr.size()
  D. sizeof(arr)
```
  
29. There’s an array: `const numbers = [ 1, 2, 3 ];` 
Choose the right way of accessing the first element.

```
  A. numbers.0
  --> B. numbers[0]
  C. numbers(0)
```

30.  Chose the expression that returns true

```
  A. typeof 1 === 'int'
  --> B. typeof 1 === 'number'
  C. typeof 1 === 'long'
```


31. Choose the right way of creating an array with a single element:

```
  --> A. const аrr = [ 5 ]
  B. const аrr = new Аггау(5)
  C. const аrr = new [ 5 ]
```

32. Tanya is older than Eric. 
Cliff is older than Tanya. 
Eric is older than Cliff. 

**If the first two statements are true, the third statement is**

```
  A. true
--> B. false
  C. uncertain
```

33. All the trees in the park are flowering trees. 
Some of the trees in the park are dogwoods. 
All dogwoods in the park are flowering trees.
  
**If the first two statements are true, the third statement is**

```
  --> A. true
  B. false
  C. uncertain
```

34. Fact 1: Robert has four vehicles.
Fact 2: Two of the vehicles are red.
Fact 3: One of the vehicles is a minivan.

**If the first three statements are facts, 
which of the following statements must also be a fact?**

* I: Robert has a red minivan.
* II: Robert has three cars.
* III: Robert's favorite color is red.

```
  A. I only
  B. II only
  C. II and III only
  --> D. None of the statements is a known fact.
```

35. Look at this series: `8, 43, 11, 41, __, 39, 17, ...` 
What number should fill in the blank?

```
  A. 8
  --> B. 14
  C. 43
  D. 44
```

36. Відомо, що гримзик обов'язково або смугастий, або рогатий, або те й інше разом.

```
  A. Гримзик не може бути безрогим.
  --> B. Гримзик не може бути однокольоровим та безрогим одночасно.
  C. Гримзик не може бути смугастим та безрогим одночасно.
```

37. Якщо запирку отруїти, то вона одразу почне пускати бульбашки

```
  A. Якщо запирка пускає бульбашки, то її отруїли.
  B. Якщо запирку не отруїти, то вона не буде пускати бульбашки.
  ---> C. Якщо запирка не пускає бульбашки, то її не отруїли.
```


38. Дубаратори бувають або хорошими, або поганими. 
Неправда, що цей дубаратор не поганий.

```
  A. Цей дубаратор хороший.
  B. Цей дубаратор такий собі.
  --> C. Цей дубаратор поганий.
```

39. Якщо почухати угубка за вухом, він почне задоволено шипіти. 
Якщо угубок задоволено зашипить, то поблизу скисне молоко.

```
  A. Якщо не чухати угубка за вухом, то молоко поблизу не скисне.
  --> B. Якщо почухати угубка за вухом, то поблизу скисне молоко.
  C. Молоко, що знаходиться далеко, ніколи не скисає від чухання угубків.
```

40. Усіх, хто гучно буриться, обов'язково з'їдають. 
Усі ухмирки постійно гучно буряться.

```
  A. Усі, хто гучно буриться - ухмирки.
  --> B. Усіх ухмирків обов'язково з'їдають.
  C. Деяких ухмирків не з'їдають.
```

41. Коли ви спите, ви завжди мухруєте.

```
  A. Якщо ви мухруєте, значить, ви спите.
  B. Якщо ви не спите, то ви не мухруєте.
  --> C. Якщо ви не мухруєте, значить, ви не спите.
```

42. Напишіть декілька слів про те чому ви хочете займатись програмуванням (150 слів максимум)
