[![npm](https://img.shields.io/npm/v/kent-css.svg)](https://www.npmjs.com/package/kent-css)
[![npm](https://img.shields.io/npm/dm/kent-css.svg)](https://www.npmjs.com/package/kent-css)
![KENTcss](https://raw.githubusercontent.com/Jaredk3nt/Kent/master/media/kent.png)
# Kent css
The only css framework on the internet created by me (Jared). Kent is a simple, minimal, and custom css framework built using scss and relying on flexbox!

> Kentcss uses a k- prefix on all components

## Docs
### Variables
The base modifiable SCSS variables for the styles. All variables can be overwritten by defining them before importing Kent.
``` scss
// color variables
$white
$black
$grey
$grey-light
$grey-dark
$grey-very-light
$blue
$green
$purple
$red
$yellow
$primary
$info
$success
$warning
$error
$background-color
$heading-color
$text-color
$link-color
$link-hover
```
``` scss
// size variables
$text-size-very-large
$text-size-large
$text-size-medium
$text-size-normal
$text-size-small
$text-size-very-small
$weight-bold
$weight-semibold
$weight-normal
$weight-light
$tablet
$laptop
$desktop
$large-desktop
$heading-line-height
$family-sans-serif
$border-radius
```
#### Basics
.k-container
- provides a width constrained container for center-content
- centered in page
``` html
<div class="k-container"></div>
```

.k-hero
- Full width hero section
- $primary, $light, and $dark schemes built in
- styled .k-title and .k-subtitle
``` html
<!-- large, dark, light modifiers -->
<div class="k-hero"> <
<div class="k-hero-content">
    <div class="k-container">
        <div class="k-title"></div>
        <div class="k-subtitle"></div>
    </div>
</div>
</div>
```
#### Type
.k-type
- Container for type based styles
- h1 - h6, p, blockquote, ul, ol

#### Buttons
.k-button
- flexible, minimal button styling
- rounded and bordered styles that can be mixed
- $primary
