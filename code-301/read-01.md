# SMACSS and Responsive Web Design

## Responsive Web Design
* Responsive Web Design (RWD) is the response to the growing use of mobile phones
* This means building a website so that it works on every screen 
* Responsive design websites continuously change as you change the size of the window
* Adaptive design websites change at certain points to a group of preset factors
* Mobile design makes a different domain for mobile and desktop sites, and it is not ideal
* Flexible layouts are made with flexible grids, and use flexible measurements: `vw` and `vh` are viewport width and height, and `vmin` and `vmax` are viewport minimum and maximum
* You can also use percentages to get the right sizes
* To design for much larger or much smaller screens, use media queries
* To make a media query, add `media="all and (max-width: 1024px)"` to the HTML call to the CSS, and add to the CSS add `@media all and (max-width: 1024px) {}` and to import, add `@import url(styles.css) and all (max-width: 1024px) {}`
* Media types include `all`, `print`, `screen`, `tv`, and `braille`
* You can use the oprators `and`, `not`, and `only` to make complex media queries
* To select screens between certain sizes, use `@media all and (min-width: 800px) and (max-width: 1024px) {}
* You can change to make the orientaion `lanscape`
* You can make changes based on aspect ratio, pixel ratio, and resolution
* Designing **Mobile first** is a good idea, because then smaller devices won't have to load all the dexktop content before removing it
* Overall, there are a lot of steps you need to take to make sure your site looks good on all devices

