[![npm](https://img.shields.io/npm/v/kent-css.svg)](https://www.npmjs.com/package/kent-css)
[![npm](https://img.shields.io/npm/dm/kent-css.svg)](https://www.npmjs.com/package/kent-css)
![KENTcss](https://raw.githubusercontent.com/Jaredk3nt/Kent/master/media/kent.png)
# Kent css
The only css framework on the internet created by me (Jared). Kent is a simple, minimal, and custom css framework built using scss and relying on flexbox!

Kent has a 'beta' global night-mode for all components.

> Kentcss uses a k- prefix on all components

Install with `npm install kent-css`!

## Docs

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
``` html
<!-- rounded and bordered modifiers -->
<div class="k-button rounded bordered"></div>
<!-- primary, info, warning, success, error color modifiers -->
<div class="k-button error"></div>
```

#### Grid
.k-grid
- dynamic sizing grid system
- full-width, one-quarter, one-half, three-quarters modifiers
- is-(1 - 12) modifiers
``` html
<div class="k-grid">
    <div class="one-quarter"></div>
    <div class="one-half"></div>
    <div class="one-quarter"></div>
</div>
```

#### Form
.k-form
- input, select, label, (more coming) stylings
``` html
<div class="k-field">
    <label class="k-label">Input field</label>
    <input type="text" class="k-input">
</div>
<div class="k-field">
    <label class="k-label">Dropdown</label>
    <div class="k-select">
        <select name="">
            <option value="">Option 1</option>
            <option value="">Option 2</option>
        </select>
    </div>
</div>
```

### Nightmode (Beta feature)
.k-nightmode
- Global night-mode styling on all current components
``` html
<body class="k-nightmode">
    <!-- Application -->
</body>
```

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
