### Issue

The problem is that `{x:1, y:2}` in the parameter list is being treated as a **destructuring pattern**, not as default values. In destructuring, `{x:1}` means "take the property `x` from the argument and put it in a variable named `1`", and `1` isn't a valid variable name, so JavaScript throws a `SyntaxError`.

There's also a second problem: `print` isn't a JavaScript function for logging (in browsers `print()` opens the print dialog). You want `console.log`.

**Fix: destructuring with defaults**

```javascript
function add({ x = 1, y = 2 } = {}) {
  console.log(x, y);
}

add();              // 1 2
add({ x: 10 });     // 10 2
add({ x: 5, y: 7 }); // 5 7
```

Two things changed:

- `x:1` became `x = 1`. In destructuring, `=` sets a default value, while `:` renames the property.
- `= {}` after the pattern is needed so that calling `add()` with no argument works. Without it, JavaScript tries to destructure `undefined` and throws a `TypeError`.

If you actually wanted to add the numbers (as the function name suggests), return the sum:

```javascript
function add({ x = 1, y = 2 } = {}) {
  return x + y;
}

console.log(add()); // 3
```