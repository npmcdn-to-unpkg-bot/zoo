# Zoo5 Front End Guidelines

Styling structure:

```
scss/
|
| //for vendor code, helpers, mixins, variables, and global (body, h1, p, a, etc.).
|+ base/
|  |- _functions.scss
|  |- _mixins.scss
|  |- _variables.scss
|  |- _base.scss
|  |- _etc etc
|
|
|+ layout/
|  |- _grid.scss
|  |- _header.scss
|  |- _footer.scss
|  |- _etc etc
|
|
| //for macro layout styles like buttons/navigation/forms etc…
|+ module/
|  |- _navigations.scss
|  |- _buttons.scss
|  |- _forms.scss
|  |- _etc etc
|
|
|  // for any type of page specific styles
|+ theme/
|  |- _home.scss
|  |- _product-row.scss
|  |- _single-product.scss
|  |- _etc etc
|
|
|  //for code you feel ashamed of and plan to improve.
|+ hacks/
|  |- _shame.scss
|
|
|- main.scss
```
