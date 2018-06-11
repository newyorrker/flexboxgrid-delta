Flexbox Grid Sass - Delta
===========
This is a fork of adaptation from the original [Flexbox Grid](http://flexboxgrid.com/) created by @kristoferjoseph.

Grid based on the `flex` display property. [Check the documentation](http://hugeinc.github.io/flexboxgrid-sass)

About
------
By trying the [Flexbox Grid](http://flexboxgrid.com/) we saw the internal need to a SASS version of it. Thanks to the good work of Kristopher Joseph, we forked his project and sassified it.

Install
---------
### npm
`npm i flexboxgrid-delta --save`

Use
---------
To modify the Flexbox grid, declare the following variables on your layout .scss

#### Set the number of columns you want to use on your layout.
`$flexboxgrid-grid-columns: 12;`

#### Set the gutter between columns.

`$flexboxgrid-gutter-width: 1rem;`

#### Set a margin for the container sides.

`$flexboxgrid-outer-margin: 1rem;`

####  Create or remove breakpoints for your project
You can modify, remove or create breakpoints before generate the final CSS.

```
$flexboxgrid-breakpoints:
  sm 768px,
  md 992px,
  lg 1200,
  xlg 1680px,
  newbreakpoint 120rem;
```
