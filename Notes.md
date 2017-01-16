# Boostrap Course

## Tools you can use with Boostrap - not a necessity.

### CSS
 - Boostrap uses Less and Saas, which are CSS compilers. You write short code and the Less engine converts it into the long CSS code.

### Grunt / Gulp
 - Similar thing but for JS, write short code and it converts it into long code using the engine.

### Compatibility
 - Caniuse.com allows you to input JS, CSS components to see which browsers support it.
 - Builtwith.com allows you to input a web addr and see what technologies make up the site.

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
