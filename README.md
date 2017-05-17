# Mobile Portfolio
This is project for the course frontend Nanodegree progam.

## To execute this:
Type or copy the following link in the browser:
https://lizgarces.github.io/frontend-nanodegree-mobile-portfolio/

You will be able to see the project of the nanodegree.

## Modifications
I worked optimizing the files: index.html, views/js/main.js, views/pizza.html.

### index.html:
Since this is not a big project, I try adding all the style.css in this html. And of course, I deleted the call to this file.
Also, I added async to the call of analytics.js and  perfmatters.js

### views/js/main.js
This one was complicated. First I changed the querySelector for getElementById or getElementbyName.
The I worked in the cycles, to move out of them assigments. Then add the requestAnimationFrame.
Specially in updatePositions(), changePizzaSizes and addEventListener.

### pizza.html
I changed the file views/images/pizzeria.jpg for an optimized pizzeria.jpg

### Minify files
I minified the files:
- /views/css/boostrap-grid.css
- /views/css/style.css 
- /views/js/main.js
- css/print.css
- css/style.css
- index.html

And all the original files are next to the minified file with the name xOriginal.x

Reduction of the files: /views/images/pizzeria.png, img/me.png

