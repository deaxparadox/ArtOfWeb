# Hello, world!

### Table of content

- [The "script" tag]()

### The "script" tag

JavaScript programs can be inserted almost  anywhere into an HTML document using the `<script>` tag.

```html
<!DOCTYPE HTML>
<html>

<body>

  <p>Before the script...</p>

  <script>
    alert( 'Hello, JavaScript!' );
  </script>

  <p>...After the script.</p>

</body>

</html>
```

The `<script>` tag contains JavaScript code which is automatically executed when the browser processes the tag. 

As soon document is loaded in the browser, the browser will first render the `p` tag (`<p>Before the script...</p>`), and then you will see a pop alert in the browser:

![alert](/assets/101-hello-javascript.png)

and finally browser will render the last `p` tag (`<p>...After the script.</p>`).
