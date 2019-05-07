# Objects!

Sometimes you want to be able to group bits of functionality together. Using an [**Object**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object) is a good way to do this:

## What are they?

In JavaScript, *everything* is an object. That includes functions, numbers, strings, everything! Need proof? Try creating a string in the console, like this:

```javascript
'Hello World';
```

Now let's try accessing a *property* of that string:

```javascript
'Hello World'.length;
```

We can do the same thing with a function:

```javascript
function myFunction () {
    return 42;
}

myFunction.name;
```

So what does this mean?

Simply put, an object is something that has *properties*. Those properties can be other objects, or values, or functions!

There are a number of "Built-in" objects in JavaScript. One particularly useful built in object is the [`Math`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math) object.

We can use the `Math` object to do mathematical operators, such as...

Find the maximum number in a set:
```javascript
Math.max(1, 2, 3);
```

Calculate power operations:
```javascript
Math.pow(9, 9);
```

Get a random number:
```javascript
Math.random();
```

## Try it out:

Have a go at playing with some objects!

* Investigate some of the properties on basic objects, such as a `number` or a `boolean`. Chrome Dev Tools are really helpful for discovering the possibilities!
* Play with the Math object a bit. What kind of mathematical operations can you do?
* There are other built-in Objects available to you in JavaScript. Have a look and see what you find! [`Date`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) is a particularly useful one!

## Next

Once you're done, move on to [**Custom Objects**](./08%20-%20Custom%20objects.md).

## More info:

You can find out *way* more about objects on [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects).
