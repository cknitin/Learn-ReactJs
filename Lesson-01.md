# React Basic, JSX

What is React?
React is a JavaScript library for building user interfaces (UIs), specifically for single-page applications (SPAs) where you need a fast, interactive, and dynamic web experience.


## Steps

1. Create a folder
2. Open it in VS Code
3. Create a .html file
    name -> react-basics.html
4. Get sample code from

    https://supersimple.dev/react-basics

```
<!DOCTYPE html>
<html>
  <head>
    <title>React Basics</title>
  </head>
  <body>
    <div class="js-container"></div>

    <script src="https://unpkg.com/supersimpledev/react.js"></script>
    <script src="https://unpkg.com/supersimpledev/react-dom.js"></script>

    <script src="https://unpkg.com/supersimpledev/babel.js"></script>
    <script type="text/babel">
      const container = document.querySelector('.js-container');
      ReactDOM.createRoot(container).render('Welcome to SuperSimpleDev React Course');
    </script>
  </body>
</html> 

```

### How to use javascript in this

add below code 

```
 <script>
        console.log('Hello React')
 </script>
```

in be this html


```
<!DOCTYPE html>
<html>
  <head>
    <title>React Basics</title>
  </head>
  <body>
    <div class="js-container"></div>

    <script>
        console.log('Hello React')
    </script>

    <script src="https://unpkg.com/supersimpledev/react.js"></script>
    <script src="https://unpkg.com/supersimpledev/react-dom.js"></script>

    <script src="https://unpkg.com/supersimpledev/babel.js"></script>
    <script type="text/babel">
      const container = document.querySelector('.js-container');
      ReactDOM.createRoot(container).render('Welcome to SuperSimpleDev React Course');
    </script>
  </body>
</html> 

```

