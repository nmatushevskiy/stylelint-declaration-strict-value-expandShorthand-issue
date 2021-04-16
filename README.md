<h3>Description:</h3>

I want that in properties containing color the value to be as variable (like background-color, color, background, border etc).

To reach this, I use `stylelint-declaration-strict-value` plugin with expandShorthand property (see stylelintrc.json for details).

I get an error, when in shorthand property has a value unrelated to color.
For example:

```
.example {
    border: 0;
}
```

see `example.less` for details.

Is this expected behavior?

<h3>How to reproduce:</h3>
1) `npm i`
2) `npm run lint`