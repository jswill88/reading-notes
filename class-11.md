# Assorted Topics

## Images Chapter 16
* It is sometimes a good idea o standardize the size of images accross the site
* You can set image classes to `.small`, `.medium`, and `.large`
* You can add another class for images you want to float left or right, and add some margin so the text is not right on the picture
* Images are inline elements by default. To center an image, make its `display:block` and use `text-align:center` with the containing element, or give the image `margin: 0 auto`
* `background-image: url("images/file-name.gif");`
* `background-repeat:` has a few values:
  * `repeat` repeats the image vertically and horizontally
  * `repeat-x` repeats over the x-axis, or you can use `repeat-y`
  * `no-repeat` means the image is only shown once
* `background-attachment` can be `fixed` or `scroll`
* If the image is not repeated, you can specify a place in an invisible 9 square grid, using `top`, `bottom`, `left`, `right`, and `center` like (x,y)
``` body {
  background-image: yada yada;
  background-position: right center;
}
```
* You can also use percentages for a `background-image`
* You can put all of the info into `background:`
* If you have multilple images for the same background, you can put them in the same property separated by commas
* A **sprite** is a single image used in different parts of an interface. This reduces the number of images your browser has to load
* When making a background gradient, you must specify both colors and the angle of the gradient

## Practical Information Chapter 19
* There are seven key places on a page to add keywords to improve SEO
  1. Page title
  1. URL
  1. Headings
  1. Text - if possible, repeat the keywords at least 2 or 3 times in the text
  1. Use keywords in link
  1. Image alt text
  1. Page description in the `<head>` in a `<meta>` tag should descrive the contnt of the page
* To figure out SEO key words, think about what someone looking for your site would search for, and pick 3-5 keywords for each page of your website
* Find out the type of people visiting your site by signing up at "www.google.com/analytics"
* To put your site on the web, you need a domain name and web hosting
* Use a FTP(File Transfer Protocol) to transfel your code and images to the hosting company

## Audio and Video Elements
* Use the `<video>` and `<audio>` tags to embed in your HTML
* If you add the `controls` attribute, you get the default playback controls. `<video controls>`. You won't have control over what comes up, so it is better to make your own controls
* The `HTMLMediaElement` API has features like `HTMLMediaElement.play()` and `.pause()` for video and audio
* You can style the controls with CSS
* Use the `:before` selector to change the content before for example the button
* There are Icon fonts you can find that give you symbols such as "play"
* In JS, make `const`s to reference all the controls you are using
* These lines remove the default browser controls: 
```
media.removeAttribute('controls');
controls.style.visibility = 'visible';
```
* Use event listeners in JS to tell the media to play or pause, and to change the controls that are displayed
* You can add a "stop" function by making the video pause and setting the current time to 0
* `mediaBackward` and `mediaForward` and rewind and fast forward
* To have the time bar, set the width of the dive to the length of the media divided by seconds

## Flash (pg 201-206)
* Flash was a popular way to add animations, video, and audio to websites
* Flash was first used to develop animations
* Flash is less popular now because it is easier to make animations with JS, and Apple does not support flash on phones and tablets
