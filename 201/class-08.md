# Class 8 notes

## Flexbox

1. Flexbox is designed for one-dimensional content. Explain what this means.

- It excels at taking a bunch of items which have different sizes, and returning the best layout for those items.helps lay the sidebar and content out inline, but where there's not enough space remaining, the sidebar will break onto a new line. Instead of setting rigid dimensions for the browser to follow, with flexbox, you can instead provide flexible boundaries to hint how the content could display.

2. Explain the difference between the main axis and cross axis.

- The main axis is the one set by your flex direction property.

- The cross axis runs in the other direction to the main axis, so if flex-direction is row the cross axis runs along the column.

- You can do two things on the cross axis. You can move the items individually or as a group, so they align against each other and the flex container. Also, if you have wrapped flex lines, you can treat those lines as a group to control how space is assigned to those lines.

3. How can using certain properties of flexbox negatively impact accessibility?

- be cautious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility. The row-reverse and column-reverse values are a good example of this. The reordering only happens for the visual order, not the logical order.logical order is the order that a screen reader will read out the content

## CSS Layout flexbox

1. What are some advantages of using flexbox over float? 

- Vertically centering a block of content inside its parent.Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available. Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

2. How does this topic connect with your long term goals?

- need to create columns and rows so i can display items in a row equally spaced inline for m project. this solves trying to adjust items equally and takes the headache out.


## Sources 
[FlexBox](https://web.dev/learn/css/flexbox/)
[FlexboxLayout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
[CSS Lyout](https://web.dev/learn/css/layout/)
 
 ## I would like to know more about

- Flex box manipulation.