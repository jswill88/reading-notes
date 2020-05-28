# HTML Images; CSS Color & Text

## Images
* Keep a folder called images with all the images a site uses, possibly with subfolders if your site has a lot of images
* Use `alt` attribute with images
* You can use a `title` attribute to provide additional info about the image. It will be shown when the user hovers over it
* If you put the image inside a `<p>` it will not start a new line
* the `align` attribute used to be used with images to make it flow with the text
* For images with many colors, use a `jpeg` file. For images with few colors, use a `gif` file
* Vector images are resolution-independent. You can increase the dimension without changing the quality
* Animated GIFs are really only useful with simple animations
* Two types of images can be transparent: Transparent GIFs and PNG
* If you open an image in a new tab, the size will appear
* `<figure>` contains an image and its caption, like this `<figure><img><figcaption>caption</figcaption><figure>`

## Color
* **Hue** - color
* **Saturation** - amount of gray in as color
* **Brightness** - how much black is in a color
* High contrast is the easiest to read, but not for long periods of time
* Medium contrast is better for long sections of reading
* You should increase the space between lines and the weight of the font for a light color on a dark background
* Opacity is the `a` in `rgba`, or you can have a separate `opacity`
  * It's good to have a fallback color for older browsers that don't recognize opacity
* `hsl` is hue, saturation, light, and can also be `hsla`

## Text
* **Monospace font** - every letter is the same width
* `weight` can be light, medium, bold, or black
* `Style` can be Normal, Italic, or Oblique (put the normal styles at an angle)
* `Stretch` can be condensed, regular, or extended
* __Cursive__ fonts have cursive and handwriting characteristics
__Fantasy__ fonts are decorative, and better for titles
* add `serif`, `sans-serif`, `monospace`, `cursive`, or `fantasy` after your preferred font, in case the browser doesn't have the one you want
* `font-family` specifies the typeface
*  Type size can be specified in pixels, percentages(default 16px), or ems
* You can specify an online font using `@font-face`
> @font-face {
>  font-family:
>  src:
>  }
* `font-weight` can be normal or bold
* In CSS you use `text-transform` to change capitalization to `uppercase`, `lowercase`, or `capitalize`
* `text-decoration` can be `underline`, `overline`, `line-through`, `none`, or `blink`
* `line-height` increases gap between lines
* `letter-spacing` and `word-spacing` are also options. This is good for all uppercase
* `text-align: justify` means everyline except the last should extend to the width of the box
* `vertical-align` can align text next to an image
* `text-indent` indents the first line of text
* `text-shadow` takes four values: left/right, top/bottom, optional blur, and color
* The first letter or first line can be styled: `p:first-letter` or `p:first-line`
* use `a:link` to stlye an unvisited link and `a:visited` to style a visited site
* `:hover` when the pointer is over the element, `:active` when a button is pressed or link clicked, `:focus` is when a browser knows you are about to interact with an element
* `p[class]` targets any `<p>` elemetns with a class
* `[class~="cat"]??
* `[attr^*"c"] - targets elements with an attribute value starting with 'c'
* `[attr*"ca"]` targets any element with an attribute value contaning 'ca'
* `[attr$"t"]` targets attribute values ending with 't'



