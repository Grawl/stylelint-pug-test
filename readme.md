# [Stylelint](https://stylelint.io) + [Pug](http://pugjs.org) test

Trying to lint CSS into Pug templates

Run NPM scripts from `package.json` to try.

| Check | Goal | Example
| --- | --- | ---
| ❌ | Lint `style.` tag content in `.pug` files with `stylelint` | `style.\n\t.foo { color: #000 }`
| ❌ | Lint `style` attribute content in `.pug` files with `stylelint` | `p(style='color: #000')`
