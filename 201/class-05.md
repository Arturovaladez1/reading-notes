# Class 5 notes

## html media

figure element is useful because if someone is using a screen reader and you have multiple images it will read whatever is in in the figure element and what you have written in the figcaption elements.

To set a different font for your text, you use the font-family property — this allows you to specify a font (or list of fonts) for the browser to apply to the selected elements. The browser will only apply a font if it is available on the machine the website is being accessed on; if not, it will just use a browser default font.

1. What is a real world use case for the alt attribute being used in a website?

- Its value is supposed to be a textual description of the image, for use in situations where the image cannot be seen/displayed or takes a long time to render because of a slow internet connection. It also helps with visually impared people that cannot see the image and are using a reader.

- Users have turned off images to reduce data transfer volume and distractions. This is especially common on mobile phones, and in countries where bandwidth is limited or expensive.

- Provide text for search engines to utilize; search engines can match alt text with search queries.

2. How can you improve accessibility of images in an HTML document?

- Adding the alt attributemto describe what the image is.

3. Provide an example of when the figure element would be useful in an HTML document.

- When you want to move the image contained in the figiure element without affecting the main flow.

4. Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.

- SVG: is a scalable vector graphics selector that uses images that arent composed of pixels and can be scaled to any size without being distorted.

- Gif: very universal format that supports many different applications like images and animations.

5. What image type would you use to display a screenshot on your website and why?

- Png should be used because it is lossles which means that it doesnt lose any data in the compression process.

## Learn CSS

1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

- Background color property defines the BG color on any elememnt in CSS. It extenfs underneath the content and padding box of the element. Foreground colors are the color before the background colors. you see foreground colors before you see background colors.
foregrounf color of an html elements content and bg color property defines the elements background color.

2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?

- change the bg color to a receding nuetral color and set his borders for his p tags with a color. 

3. What should you consider when choosing fonts for an HTML document?

- There are only a certain number of fonts that are available universally. so instead use web safe fonts.

4. What do font-size, font-weight, and font-style do to HTML text elements?

- font size cand tyake values in px, em, or rem.
- Avoid using font size of container elemets.

- font weight sets how bold the text is. normal and bold are most common varients.

- font style used to turn italic text on or off. normal, italic, oblique are the varients.

5. Describe two ways you could add spacing around the characters displayed in an h1 element.

- textalign and text orientation, margin padding? not sure about this one.

# Sources
[Multimedia and embedding](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)

[Images in html](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

[Img file type and format](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)

[Html styling using css](https://developer.mozilla.org/en-US/docs/Learn/CSS)

[Color html using css](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)

[Text and font stylizing fundamentals](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

## Class 5 In class notes

# Title

Bottom of class demo is the replit from class
Friday assignments can be turned on sunday night
the real value passed in is the value
declare a variable to be used in a function
if, and else if comes after the while
while ()
{}
if ()
{}
else if()
{}
declaring your function at top if you find yourself repeating the same code.
global variable at the top 
you can invoke functions at the bottom of the page.

## Arrays

.pop() removes things at the end of the array
.push() adds it to the end of the array.
.shift() removes the first item in the array and moves the rest of the items move in the index.
.unshift() adds to the first item in the array and shifts the rest of the items.
you can also add multiple strings to the array also.
.splice() takes the index of the item you want removes in a argument

## CSS

div > span only direct children will get changes.
div takes the whole line
li:nth-child(pickalistnumber) for list styling
margin:auto sets it as a box 
div block
span are inline
float takes things out of the flow 
article  
.clearfix::after{
  content:"";
  clear:both
  display:table;

}

take in an array into a function
function add first 3
function return diff array 2 elemetns

function adder(arr)

## Things I want to know more about

- CSS Grid

- Two ways you could add spacing around the characters displayed in an h1 element.