# Variables!

To start along our JavaScript journey, let's play with some *variables*!

## What are they?

Variables are an important part of most programming languages, and JavaScript is no exception!

A variable is used to store some data, and we declare one like this:

```javascript
let myVariable = 'value';
```

In that example we used a `string` but in JavaScript you can assign any type of data to a variable. You could also assign a `number`, or a `boolean`:

```javascript
let aVeryGoodNumber = 123;
let importantBoolean = true;
```

## Try it out!

Open the dev tools in Google Chrome, and go to the "console" panel. This is a [REPL](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop) (Read-Eval-Print Loop), which will let you run your code as you write it!

Let's have a go at making our own variable in the console. Create a new variable, and assign a string of your name to it! Naming variables is an important skill, so make sure you give your variable a clear name. In JavaScript we usually use `camelCase` for variable names.

You might write something like this:

```javascript
let myName = 'Craig Spence';
```

Check that the variable is working by accessing it from the console:

```javascript
myName;
```

Did your name get echoed back at you? Great!

** More things to try: **

* Create some other variables with other values! Try using `null` and `undefined`.
* Find out what happens if you try to declare two variables with the same name?
* Figure out if you can you assign a different value to the same variable?

Once you're done with that, you can move on to [**Functions**](./05 - Functions.md). 👏👏👏

## More info:

You can read more about [variables on the Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types#Declarations), an exceptionally useful resource where you can learn all about JavaScript and web technologies!

Have a look and see what you can find out about the other types of variables in JavaScript -  `const` and `var`.
