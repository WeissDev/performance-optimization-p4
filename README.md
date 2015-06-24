# Website Performance Optimization Project

These are my project files for Udacity's Web Performance project. To have a look at it you can clone or download the zip file and then click on index.html. The main page includes a timer at the bottom of the page where you can see how long it took the browser to go through the critical rendering path.

Alternatively simply follow this link: http://weissdev.github.io/performance-optimization-p4

To view the render-optimized pizza page to see pizza's flying around at a smooth 60FPS+ follow this link: http://weissdev.github.io/views/pizza.html

## Goal 1: Optimize Cameron Pittmans Sample Portfolio Page

The goal of this exercise was to improve the critical rendering path of index.html to make the page render as fast as possible.

I achieved a PageSpeed Insights score of 95 on mobile and 97 on desktop after having applied all optimizations.

### Optimizations applied:

#### Images

All images have been compressed since they have been unnecessarily large.

#### JavaScript

Non critical JavaScript resources were given the async attribute & moved to the bottom of index.html

#### CSS

Critical CSS has been inlined to ensure it is not render-blocking, in addition to that it has also been minified to save some bytes

Non critical CSS resources were given the appropriate mediatype attribute

##Goal 2: The 60FPS Pizza Page Challenge

The goal of this challenge was to optimize main.js so that pizza.html would be able to render its animation's at a smooth 60FPS.

### Optimizations applied

I optimized the code which responded to the mouse scroll event by applying requestAnimationFrame & further optimizing related functions.

I've also improved the pizza slider to resize the pizzas as instructed during the course.

##Resources Used

-Ilya Grigorik's Web Fundamentals on how to optimize the Critical Rendering Path (https://developers.google.com/web/fundamentals/performance/critical-rendering-path/)

-Google's PageSpeed Insight which gave me helpful hints (https://developers.google.com/speed/pagespeed/insights/)

-Paul Lewis's article: Animations with requestAnimationFrame (http://www.html5rocks.com/en/tutorials/speed/animations/)

-Getting started with Gulp (https://markgoodyear.com/2014/01/getting-started-with-gulp/)










