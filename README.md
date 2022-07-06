# dart-sass-issue-3322-extend-in-mixin-undefined
@extend inside @mixin does not work in this example

1. `npm i`
2. `sass _total.scss total.css`

⬇️

```
Error: The target selector was not found.
Use "@extend .foo !optional" to avoid this error.
  ╷
4 │   @extend .foo;
  │   ^^^^^^^^^^^^
  ╵
  _baz.scss 4:3  root stylesheet
```
