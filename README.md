# Website Optimization Project

This game was developed after 'Website performance' and 'Browser rendering optimization' courses during [Udacity Front End Developer nanodegree](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001).

## Optimizations for [index.html](dimberr.github.io/frontend-nanodegree-mobile-portfolio):
* Optimized images
* Inline CSS
* Split CSS for print and mobile version to different files and load them using @media
* Minified JS and added async to scripts Using Web Font Loader that defers the loading of Google Fonts until after other parts of the page have started to render

Now it has more than 90 in Pagespeed Insights by Google



## Optimizations for [pizza.html](dimberr.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html):
* Render pizza if it only in viewport
* Split Style recalculations and Layout (Fix for FSL)
* Added requestAnimationFrame where it needed
* Optimized images, added async for scripts
* Inline CSS, minify JS and CSS

Now it can be rendered with a consistent frame-rate at 60fps when scrolling


### Checkout my optimizations for [news-aggregator](dimberr.github.io/frontend-nanodegree-news-aggregator/)


### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api").
