# Scripts!

Running everything in the console can be a bit annoying! It is much better to save our code as a script!

## What are they?

A script is some code that is included in a web page. That can happen one of two ways:

1) With a script tag that reference a JavaScript file with a `src` attribute:

```html
<script src="./my-script.js"></script>
```

2) With a script tag that contains the script *inline*:

```html
<script>
    alert('Hello world!');
</script>
```

## Try it out!

For the sake of simplicity, let's try the second option.

We should modify our *index.html* file to include an *inline* script tag as shown above. It should be added just after the `<body></body>` tags.

Now, whenever you refresh the page and reload *index.html*, that script should run, and you should see the `alert`!

**More things to try:**

* Try adding some of the functions from before to your `<script>`.
* Try moving the script to a separate file and using the `src` attribute to include it. Use the "**Network**" tab of dev tools to look at the difference.

## Next

Now we're ready to learn a bit about [**Objects**](./07%20-%20Objects.md). 👏👏👏

## More info:

You can find our more about the `<script>` tag on [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script)

If you're feeling extra keen, try to get a script to load with the `src` attribute. To do that, save your script alongside the *index.html* file in another file called *my-script.js*.
