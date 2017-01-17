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
change

## Accessibility
 - You can have sr options for screen readers. Also you can place a link to the accessibility at the start of the site which is then styled to be placed at the bottom of the screen for visual users.

## Components
 - Navigation bar - fix to top and move the page down.
 - fluid container div inside navbar
 - data- tags in buttons: data-target, data-toggle etc. data- means you can add whatever you like - not a fixed attribute of the HTML tag. Angular uses data- before the ng- attributes.
 - zoom in changes text size which in turn changes navbar height, and so fixed pixel padding to offset body so its visible under navbar will not be enough - so percentage is preferable

# Day 2

## Screen size decisions
- If you need to move something as the screen size reduces, you can either use bootstrap to hide and show elements at certain screen sizes, or you can you use JS to move the element to a new position.
- todo mvc site shows you the difference between most popular mvc's on the web
- library is a set of routines that you call
- framework is its own thing that you run

## Components
- badges: such as a count of items in a shopping basket - black circle background. Like a notification on iPhone
- Alerts - for pop up with JS
- Wells instead of panels? They are less complex. Don't have to rely on grid - can specify with width and height to place them in the right place.

## Using JS with bootstrap
- Jquery can be used to show HTML elements. It will compute one element in a chain before it will execute the next element.
- Can select a tag, id or class. Using comma to add together classes, tags etc.
- ~ : etc can be used to specify what element in the HTML we want to talk to.
- $().click, .bind, .on are event listeners.
- Navs and Pills are navigation options.
- tooltip and popover are unique in that they do not work unless JS is configured. Must write a selector and specify that its going to be a tooltip / popover.
- `` are used to allow writing JS over multiple lines``

## Afternoon Exercise
- toolbar at the top
- Accordian with drop down inside - categories choice
- Accordian with two pill nav seciton
- in left nav - Carosel of images in left
- in right - panel with table / shopping cart
