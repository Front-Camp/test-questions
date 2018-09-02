1. What is the correct HTML for adding a background color?

```
  --> A. <body style="background-color:red;">
  B. <body bg="red">
  C. <background>red</background>
```

2. What is the correct HTML for creating a hyperlink?

```
  A. <a url="http://www.test.com">test.com</a>
  B. <a>http://www.test.com</a>
  --> C. <a href="http://www.test.com">test</a>
  D. <a src="http://www.test.com">test.com</a>
```

3. What is the correct HTML for inserting an image?

```
  A. <img href="image.gif" alt="MyImage">
  --> B. <img src="image.gif" alt="MyImage">
  C. <image src="image.gif" alt="MyImage">
  D. <img alt="MyImage">image.gif</img>
```

4. What is the correct HTML for referring to an external style sheet?

```
 A. <style src="mystyle.css">
 --> B. <link rel="stylesheet" type="text/css" href="mystyle.css">
 C. <stylesheet>mystyle.css</stylesheet>
```

5. What is the correct CSS syntax for making all the <p> elements bold?

```
  A. p {text-size:bold;}
  B. <p style="text-size:bold;">
  C. <p style="font-size:bold;">
  --> D. p {font-weight:bold;}
```

6. When these elements are rendered, what will be the margin between them?

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

7. Which selector will target only the last list item?

```html
  <ul>
    <li>Not me.</li>
    <li>Not me.</li>
    <li>Target only me.</li>
  </ul>
```

```
  ---> A ul li:last-child
  B ul:last-child li
  C ul:last-child(li)
```

8. Is there a difference between Visibility: hidden and Display: none properties?

```
  A. No
  --> B. Yes, visibility: hidden will hide element from screen, but it will still take the space, while display: none will not display it at all
  C. Yes, visibility: hidden will hide element from screen, while display: none will not display element, but it will still take the space
```
