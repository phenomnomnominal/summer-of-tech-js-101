# Control flow!

Okay, so we know about variables, functions, objects, and arrays, but how do we put them all together?

## What is it?

**Control flow** is all about how the bits of a program go together.

The main way to control the flow of a JavaScript program is with `if`/`else` statements. They look something like this:

```javascript
if (something) {
    doThisThing();
} else if (somethingElse) {
    doThisOtherThing();
} else {
    doThisThirdThing();
}
```

Hopefully there's nothing too surprising here! We're simply saying what to do if one of several conditions happen.

The trick comes with defining those conditions! They are defined with [**boolean logic**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_Operators).

In JavaScript there are a number of operators we can use to *compare* values. First of all there are the comparison operators:

* `===` - the "strict equality" operator
* `!==` - the "strict inequality" operator
* `<` - the "less than" operator
* `>` - the "greater than" operator
* `<=` - the "less than or equal" operator
* `>=` - the "greater than or equal" operator

Each of these operations will result in a boolean expression, which can be used as a `condition` for an `if` or `else` statement!

You use them like this:

```javascript
3 < 10; // true
3 < 1; // false
3 >= 3; // true
3 === 3; // true
'hello' === 'bye' // false
'hello' === 'hello' // true
```

## Try it out!

Let's have a go at making a silly little program. Imagine that we want to do a coin flip, what would that look like?

We might start with something like this:

```javascript
if (something) {
    alert('HEADS');
} else {
    alert('TAILS');
}
```

Makes sense yeah? But what do we do with `something`?

Remember `Math.random()`? It returns us a *random* number, so that's perfect!

Let's change our code to use `Math.random()`, and combine it with the `<` operator:

```javascript
if (Math.random() < 0.5) {
    alert('HEADS');
} else {
    alert('TAILS');
}
```

Perfect!

## Next

Once you've got that working, you're ready for the last step, [**interacting with the DOM**](./11%20-%20Interacting%20with%20the%20DOM.md).

## More info:

You can find out more about [Control Flow on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling).
