# Functions!

Next up, we have functions!

## What are they?

A function *encapsulates* a bit of functionality. They provide a way to *reuse* bits of code!

JavaScript gives us some functions out the box! One particularly useful one is [`alert()`](https://developer.mozilla.org/en-US/docs/Web/API/Window/alert). You can *pass* a value to `alert()`, and it will show up on the screen!

We can also write our own functions! We might have something like this:

```javascript
function multiple (a, b) {
    return a * b;
}
```

Here we have a `multiply` function, which takes two *parameters*, `a`, and `b`, and *returns* the result.

We could similarly write an `add` function, like this:

```javascript
function add (a, b) {
    return a + b;
}
```

The only difference is the *name* of the function, and the operator used! Function names are important, as they have to be unique within a [*scope*](https://developer.mozilla.org/en-US/docs/Glossary/Scope) of a program.

## Try it out:

Let's first have a go at using `alert`!

In the console, try passing a string directly to the `alert` function, like so:

```javascript
alert('Hello World!');
```

You should get a (kind of annoying) pop-up on your screen!

Next, let's swap out that string for the variable we used for our name before. In my case that would be `myName`.

```javascript
alert(myName);
```

Now I get my name in the pop-up! (If it didn't work, you may need to recreate the variable).

Next, let's try using the `multiply` functions we saw before. Let's run the following in the console:

```javascript
function multiple (a, b) {
    return a * b;
}
```

Nothing happened? That's because we only *declared* the function, we didn't use it.

We can take the result of our function call, and assign it to a variable:

```javascript
let result = multiply(3, 4);
```

So now we've stored our result, but what if instead we want to see what it is?

Instead of using the variable, let's combine `multiply` with alert:

```javascript
alert(multiply(3, 4));
```

You should get a pop-up with the number 12 in it! This is an example of *composing* functions, where the return value from one function is passed directly to another function.

Let's go deeper! Let's declare our `add` function:

```javascript
function add (a, b) {
    return a + b;
}
```

Let's try using the `add` with our `multiply` and `alert`! Before you run the code, have a guess at what you think the result will be:

```javascript
alert(multiply(2, add(3, 4)));
```

Was it what you expected?

**More things to try:**

* Have a go at adding and using a `subtract` and `divide` function!
* Check out the built in [`prompt()`](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt) function - it's kind of like `alert()`, but allows the user to give you a value!

## Next

Next up it's time to learn about using [**Scripts**](./06%20-%20Scripts.md). 👏👏👏

## More info:

You can read more about [functions on MDN!](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
