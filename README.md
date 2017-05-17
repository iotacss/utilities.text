**iotaCSS is now a monorepo and all individual repositories are part of it. Please open issues or PRs here: [https://github.com/iotacss/iotacss](https://github.com/iotacss/iotacss).**

# Text Utility #

The text utility contains helper classes for the CSS text-align property.


### Installation ###

```
npm install --save iotacss-utils-text
```


### Options ###

```sass
$iota-utils-text-namespace    : 'text-' !default;
$iota-utils-text-left-name    : 'left' !default;
$iota-utils-text-right-name   : 'right' !default;
$iota-utils-text-center-name  : 'center' !default;

$iota-utils-text-res          : false !default;
$iota-utils-text-breakpoints  : $iota-global-breakpoints !default;
```


### Classes ###

```
.u-text-left
.u-text-right
.u-text-center


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: .u-text-left@sm
```
