# Custom objects!

Built-in objects are great, but things get really useful when we can create our own custom objects.

## What are they?

A custom object is just the same as any other object, but it is *not* provided by the runtime.

JavaScript has a special syntax for creating an object, so you could create a *person* object like this:

```javascript
let person = {
    name: 'Craig',
    age: 28
};
```

Here our `person` object has two properties, `name` and `age`.

This kind of structure may be familiar to you if you've ever used [JSON](https://www.json.org/).

You can even use a `function` to create an object:

```javascript
function createPerson (name, age) {
    return {
        name: name,
        age: age
    };
}

let craig = createPerson('Craig', 28);
console.log(craig.age);
```

Notice that here we're using another "built-in" object, `console`. `console` is a powerful object that helps us to debug our code!

An object can also have properties that are functions. Remember our `multiply` and `add` functions from before? We could group them together:

``` javascript
let myMaths = {
    add: function add (a, b) {
        return a + b;
    },
    multiply: function multiply (a, b) {
        return a * b;
    }
};
```

We'd then use them like this:

```javascript
myMaths.add(1, 2);
```

## Try it out:

Have a go at creating your own objects!

* Try creating an object with a mix of *values* and *functions*.
* Try creating an object that contains another object.
* Can you figure out how to change a property on an object after it's been created?

Once you're done, you're ready to go on to the next step, [**Arrays**](./09 - Arrays.md). 👏👏👏
