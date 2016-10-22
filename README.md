## Website Performance Optimization project

Visit http://shubhakar44.github.io.  to view live site

### Getting started

Some useful tips to help you get started:

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080


####Part 1: Optimize PageSpeed Insights score for index.html


1. Minimized and inlined the whole style.css stylesheet.
2. Make print.css to be available only  while printing
3. Make google font, analytics.js and perfmatters.js all async 
4. Reduced pizzeria.jpg size and compressed
5. Compressed profilepic.jpg
6. Made the similar adjustments to project-2048.html, project-webperf.html and project-mobile.html


####Part 2: Optimize Frames per Second in pizza.html

1.document.getElementById() and document.getElementsByClassName() Web API calls used for speed
2.DOM calls moved outside of for loops and saved to local variable
3.Saved array lengths in local variable
4.Declare variables outside of loops
5.window.screen.height and window.screen.width used to calculate number of pizzas needed to fill browser window  
 
