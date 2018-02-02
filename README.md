## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository and inspect the code.

### Getting started
*some changes and compression on pictures.
*downloaded ngrok and started it.
*inspect and search for red lines to optimize them (most of them were in main.js file).
*tried to inline and change the css with HTML.
*function have most the errors (determineDx) had to cearfully change without making the page change
#### Sitting ngrok up


1. Download and install [ngrok](https://ngrok.com/) 

2. open terminal then
```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```
  3. Open a browser and visit localhost:8080
  4. open another terminal then
  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```
  5. Copy the public URL ngrok gives you and try running it through PageSpeed Insights! Optional: [More on integrating ngrok, Grunt and PageSpeed.](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/)


#### some extra's
i tried to minify the js filed but that lead's to error i hope to let me know how can i minify them correctly.