# UDACITY (Front-End Web Developer Nanodegree)

## P4: Website Optimization

Open index.html in your browser to run file locally.
Optimized a provided website with a number of optimization- and performance-related issues so that it achieves a target PageSpeed score and runs at 60 frames per second.




### Index.HTML
- Removed the style.css link, minify the style.css then add this to header
-  compressed the images(profilepic.jpg & pizzeria.jpg) and use the compressed images in index.html
-  add async attribute to the script links
-  add media attribute to the print.css link
-  minified the print.css
-  minified the perfmatters.js
-  minified the index.html

###  Pizza.html
-  Minify the bootstrap-grid.css & style.css
- Minify the main.js
- Minify the pizza.html
- Modify main.js  (moved variables out of the for loop since they are constants.changed document.querySelectorAll
  to document.getElementsByClassName to increase efficiency in functions named changePizzaSizes() and updatePositions() )



