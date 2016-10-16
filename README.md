WEBSITE OPTIMIZATION

Follow the given link: https://jigyasa6.github.io/frontend-project--6/

Project overview:
The task was to optimize a provided website with a number of optimization and performance-related issues so that it achieves a target PageSpeed score and runs at 60 frames per second.

Optimization

Index Page:
After making changes the initial score increased to 95/100 for mobile and 97/100 for desktop.

The following changes were made in index.html:

CSS
Inlined all of the CSS into the head of the document and added the HTML media="print" attribute to the external style sheet link for print styles.

JS
Added the HTML async attribute to all script tags and minify.

Images
Resized images that were too large and compressed all images with the Kraken image compression tool.

Files
Javascript,CSS files were minified using JS minifier and CSS minifier.

The following changes were made in pizza.html:

Optimizing loops:
Loops were optimized in updatePositions function and on DOMContentLoaded event handler.

Images were optimized.