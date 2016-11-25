## Website Performance Optimization portfolio project


####Part 1: Optimize PageSpeed Insights score for index.html

1.Speed of website is enhanced upto 90 pagespeed in mobile as well as desktop.
2.Code of html is minified using online tool htmlminifier.com .
3.'analytics.js' and 'permatters.js' is attributed as async and defer for better performance in index.html
4.Inline css tag is used to remove render blocking approach of html parsing.
5.defer attribute is used for defering the javascripts in index.html.
6.lazyload attribute is used for lazy load of images to avoid overhead in downloading of images which is caused by preloader.
7.For checking the speed of page ngrok server is used which provide local server remotely accessible to internet.


####Part 2: Optimize Frames per Second in pizza.html

1.The main.js optimizes pizza.html upto 60fps smoothly.
2.Global variables for Adjective to uncause the invocation of new object every time.
3.Global variable for nouns to uncause the invocation of new object every time.
4.Changepizzasize method is improved by removing all other calculations and functions which are lowering the performance. 
5.Use getElementByClassName instead of querySelectors improves performance
6.For scrolling optimization height of window is used which calculates the no. of pizza which is required to be on screen instead of looping
around 200 pizza's.
7.Variables like top,no_pizza,newwidth are used to optimize the results because they are being constant and making loops complexity high.
8.Time to resize pizzas is less than 5 ms using the pizza size slider.

#### How to RUN index.html 

1.Go to folder fend 
2.Double click on index.html

#### How to Run pizza.html

1.Go to folder fend then
2.Go to folder views
3.Double click on pizza.html

#### How to Run ngrok

1.Run your localserver at localhost 80 port and copy all files of web to local server directory.
2.online the ngrok app.
3.call command in commandline ngrok http 80
4.run localhost:4040 in your browser
5.use the link provided.
 
 
