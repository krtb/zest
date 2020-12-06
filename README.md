# Zest
Food Menu App

- Frontend built with React.js framework

___
> Notes Below

## React

### Render
* importing in React
    * `import React, { Component }  from 'react';`
* render method
    * first arg => JSX
        * Provide a function as JSX, self-closing tag
    * second arg => Mounting Point
        * a DOM element - so that it can be mounted to the page.
### JSX
* Allows users to mix JavaScript with HTML
* jsx tags must have a class of `className`
* Alternative
    * React.createElement()
    * Nested elements path
* ASI (js feature)
    * Automatic Semicolon Insertion
    * Ex: `return;` - if code on a different line
* Return pair of parenthesis (), and put JSX inside
* BEDMAS - (brackets exponents multiplication addition subtraction)
    * Runs what is inside the parens, first
* `return (` - with space, since return is a keyword, not a function
*  can only return 1 element, with as many elements inside as needed
    * React 16.2 - `React.Fragment`, tag as a wrapper
        * or `import {Fragment}`, and only render out `<Fragment>` tag
        * this renders to nothing
    * will also be able to redner out blank tags - `<></>`
* Commenting in JSX, different from regular React
    * {} - JavaScript
    * {/*comment*/} - block comment must be used
    * CAN NOT return both a comment and an element
        * comment must be inside of element

### Load CSS
* ( `Option 1` ) 
    * Import CSS directly into index.html file, where React us mounted
* ( `Option 2` ) 
    * Inline CSS / Componentized CSS - Advanced Route
        * import CSS that only relates to one component
        * tightly could CSS with the component that gets rendered out
* ( `Option 3` )
    * Import CSS into index.js file
        * will be applied to the entire application 
