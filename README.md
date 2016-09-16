# Website Optimization Project

For [this](https://dimberr.github.io/frontend-nanodegree-mobile-portfolio) site some optimizations were applied after 'Website performance' and 'Browser rendering optimization' courses during [Udacity Front End Developer nanodegree](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001).

## Optimizations for [index.html](https://dimberr.github.io/frontend-nanodegree-mobile-portfolio):
Changes to original not optimized [page](http://udacity.github.io/pizza-perf/)
* Optimized images
* Inline CSS
* Split CSS for print and mobile version to different files and load them using @media
* Minified JS and added async to scripts Using Web Font Loader that defers the loading of Google Fonts until after other parts of the page have started to render

Now it has more than [90](https://goo.gl/A9GFls) in Pagespeed Insights by Google




## Optimizations for [pizza.html](https://dimberr.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html):
Changes to original not optimized [page](http://udacity.github.io/pizza-perf/views/pizza.html)
* Render pizza if it is only in viewport
* Split Style recalculations and Layout (Fix for FSL)
* Added requestAnimationFrame where it needed
* Optimized images, added async for scripts
* Inline CSS, minify JS and CSS

Now it can be rendered with a consistent frame-rate at 60fps when scrolling and also has more than [90](https://goo.gl/KZXo6V) in Pagespeed Insights by Google




### Check out my optimizations for [news-aggregator](https://dimberr.github.io/frontend-nanodegree-news-aggregator/)


#### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api").
