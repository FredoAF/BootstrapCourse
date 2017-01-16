# Boostrap Course

## Tools you can use with Boostrap - not a necessity.

### CSS
 - Boostrap uses Less and Saas, which are CSS compilers. You write short code and the Less engine converts it into the long CSS code.

### Grunt / Gulp
 - Similar thing but for JS, write short code and it converts it into long code using the engine.

### Compatibility
 - Caniuse.com allows you to input JS, CSS components to see which browsers support it. - Builtwith.com allows you to input a web addr and see what technologies make up the site.

## Writing a template
 - Viewport meta tag: set the device width to be the actual width of the device - as most mobile devices set the width by default to be 1024 so that you see a portion of the page full size, in 1:1 ratio. We do this as Bootstrap takes mobile devices into account - so we want to be in control.
 - .map tells you where to look in the non-minified file where the error was in the minified file.
 - Media queries -the browser asks the device what its max width is etc - and based on the response it will return a difference CSS file that is appropriate for it.
 - On Chrome developer tools you can select the device you want to imitate, so you can tell the server what device you are and see what it sends back, to test media queries.
 - Fluid designs - when you change your screen resolution the width changes.
 - layout shifter - hardest option but depending on the device you can completely change the layout of the site.
 - Boostrap includes CSS for older browser compatibility.
 - main div container can use class="container"

 - the number 12 is used in formatting the layout of Bootstrap as its the most divisible number.
 - col-xs md, sm, lg specify the column parameters when the div is at different sizes.
 - .img-responsive will fill a container and change the height of the image as the container changes.


## Forms
  - Form control class must be on items for the overriding form class to be applied
  - form-inline or form-horizontal can be applied to the form to define how the layout is viewed.
  - text items in the form need to be in a div wrapper if columns are used.
  - Column classes can be applied to the labels direct. See the forms.html file.
  - If you want to layout your columns as rows, then all you need to do is set the width of the column to be the entire width (12), then the next column will have to go underneath.


## Tables
 - Grids can be used instead of Tables. You can use borders and stripes to make them look good with the Boostrap classes.
 - Don't need tbody, thead tfoot are no longer needed.
 - You need to put a table-responsive div around a table in order to create the scroll when the page size decreases.
