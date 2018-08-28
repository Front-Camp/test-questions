```
# test-questions

## Logic questions
1. Tanya is older than Eric.
Cliff is older than Tanya.
Eric is older than Cliff. 

If the first two statements are true, the third statement is

A. true
B. false
C. uncertain

2. Blueberries cost more than strawberries.
Blueberries cost less than raspberries.
Raspberries cost more than both strawberries and blueberries.

If the first two statements are true, the third statement is

A. true
B. false
C. uncertain

3. All the trees in the park are flowering trees.
Some of the trees in the park are dogwoods.
All dogwoods in the park are flowering trees.

If the first two statements are true, the third statement is

A. true
B. false
C. uncertain

4. B2CD, _____, BCD4, B5CD, BC6D

A. B2C2D
B. BC3D
C. B2C3D
D. BCD7

5. Play is to actor as concert is to

A. symphony
B. musician
C. piano
D. percussion


6. Fact 1: Robert has four vehicles.
Fact 2: Two of the vehicles are red.
Fact 3: One of the vehicles is a minivan.

If the first three statements are facts, which of the following statements must also be a fact?

I: Robert has a red minivan.
II: Robert has three cars.
III: Robert's favorite color is red.

A. I only
B. II only
C. II and III only
D. None of the statements is a known fact.

7. Fact 1: All chickens are birds.
Fact 2: Some chickens are hens.
Fact 3: Female birds lay eggs.

If the first three statements are facts, which of the following statements must also be a fact?

I: All birds lay eggs.
II: Some Hens are birds.
III: Some chickens are not hens.

A. I only
B. II only
C. II and III only
D. None of the statements is a known fact.

8. 4 : 256 :: 5 : ?

A. 526
B. 625
C. 125
D. 726
E. 620

9. Which word does NOT belong with the others?

A. two
B. three
C. six
D. eight

10. Look at this series: 8, 43, 11, 41, __, 39, 17, ... What number should fill in the blank?

A. 8
B. 14
C. 43
D. 44


## Javascript
1. What is the correct JavaScript syntax to change the content of the HTML element below?

<p id="demo">This is a test.</p>

A document.getElementByName("p").innerHTML = "Hello World!";
B #demo.innerHTML = "Hello World!";
C document.getElement("p").innerHTML = "Hello World!";
D document.getElementById("demo").innerHTML = "Hello World!";

2. Which of the following is NOT a JavaScript object?

A let obj = {};
B let obj = { name: "Steve"};
C let obj = { name = "Steve"};
D let obj = new Object();

3. Which of the following is an example of anonymous function in JavaScript?

A let myFunc = function(){ };
B function(){ };
C let myFunc = (){ };
D All of the above.

4. Will alert be shown?

if ("0") {
  alert( 'Hello' );
}

A Yes
B No

5. How many parameters can be passed to the function?

A none
B one for each argument
C as much as you like
D one

6. A ? B : C is equivalent to:

A if (A) {B} else {C}
B if (A==B) C
C if (A!=B) C
D if (A) {B; C}

7. The code to obtain a random number between 5 and 9 inclusive is:

A Math.floor(Math.random() * 5) + 4)
B Math.floor(Math.random() * 4) + 4)
C Math.floor(Math.random() * 4) + 5)
D Math.floor(Math.random() * 5) + 5)

8. To see if three variables are equal we would use:

A A=B=C
B (A==B)&&(B==C)
C (A=B)&&(B=C)
D (A==B)&(B==C)

9. What is this code going to show?

let fruits = ["Apples", "Pear", "Orange"];

let shoppingCart = fruits;
shoppingCart.push("Orange");

alert( fruits.length );

A 1
B 2
C 3
D 4

10. When executed, this will pop up three alerts. In order, what are they?

let a = 6;
function test() {
    let a = 7;
    function again() {
        let a = 8;
        alert(a);  // First
    }
    again();
    alert(a);  // Second
}
test();
​alert(a);​  // Third

A 6; 7; 8
B 7; 6; 8
C 8; 7; 6
D 8; 6; 7

11. What is this code going to show?

(function(foo) {
  alert(foo);
})(this);

A SyntaxError
B [object Window]
C function(foo) {
    alert(foo);
  }
D 'this'

## HTML/CSS

 1. Choose the correct HTML element for the largest heading:
 <heading>
 <h6>
 <head>
 <h1>

 2. What is the correct HTML for adding a background color?
 <body style="background-color:red;">
 <body bg="red">
 <background>red</background>

 3. What is the correct HTML for creating a hyperlink?
 <a url="http://www.test.com">test.com</a>
 <a>http://www.test.com</a>
 <a href="http://www.test.com">test</a>
 <a src="http://www.test.com">test.com</a>

 4. What is the correct HTML for inserting an image?
 <img href="image.gif" alt="MyImage">
 <img src="image.gif" alt="MyImage">
 <image src="image.gif" alt="MyImage">
 <img alt="MyImage">image.gif</img>

 5. Which HTML element is used to specify a header for a document or section?
 <head>
 <header>
 <section>
 <top>

6. What is the correct HTML for referring to an external style sheet?
 <style src="mystyle.css">
 <link rel="stylesheet" type="text/css" href="mystyle.css">
 <stylesheet>mystyle.css</stylesheet>

7. Which HTML attribute is used to define inline styles?
 style
 font
 class
 styles

8. Which CSS property is used to change the text color of an element?
 text-color
 color
 fgcolor
 font-color

9. How do you selects all <p> elements where the parent is a <div>?
 div p
 div.p
 div + p
 div > p

10. What is the correct CSS syntax for making all the <p> elements bold?
 p {text-size:bold;}
 <p style="text-size:bold;">
 <p style="font-size:bold;">
 p {font-weight:bold;}

## Git (Github)

1. What's the git command that downloads your repository from GitHub to your computer?

git push
git fork
git clone
git commit

2. How do you create a copy of a repository under your own GitHub account?

Forking it via the GitHub interface.
git fork
git clone
git pull-request

3. What's the opposite of git clone, instead of downloading your code from GitHub, uploads your changes and code back to GitHub?

git push
git add
git upload
git status

4. How do you check the state of your local git repository since your last commit?

git check
git status
git commit
git diff

5. How do you stage files for a commit?

git stage
git commit
git add
git reset

6. How do you save the current state of your code into the git version control?

By committing the staged changes with git commit
By adding all changes and staging them with git stage
By adding all changes and staging them with git add
By creating a new commit with git init

7. What's a shortcut to staging all the changes you have?

git commit add .
git commit .
git add .
git push -am "Message"

8. How do you supply a commit message to a commit?

git message "I'm coding"
git add "I'm coding"
git commit "I'm coding"
git commit -m "I'm coding"

9. What is the correct commit syntax for all changes with a message?

git message -am "I'm coding"
git add -a "I'm coding"
git commit -a "I'm coding"
git commit -am "I'm coding"

10. What comes first, staging with git add . or committing with git commit?

Staging your commits with git add
Committing with git commit

```