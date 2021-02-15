# HTML LAYOUT
![layout](https://1.bp.blogspot.com/-byyR6UhzRlw/XqPR9QUH12I/AAAAAAAACf8/_h6ITaQ45h0dazPFuifNqe7OSMFNbZopgCLcBGAsYHQ/s1600/HTML%2Blayout.png)
**Key Concepts in Positioning Elements**

Building Blocks
CSS treats each HTML element as if it is in its
own box. This box will either be a block-level box or an 
- inline box.
Block-level elements start on a new line Examples include:
- < h1>
- < p> 
- < ul> 
- < li>

- Inline elements
flow in between surrounding text Examples include:
- < img> 
- < b>
- < i>

- Containing Elements
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

- Controlling the Position of Elements
CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning.
- Normal Flow
The paragraphs appear one
after the other, vertically down
the page.
- Relative Positioning (position: relative)
The second paragraph has been
pushed down and right from
where it would otherwise have
been in normal flow
- Absolute Positioning (position: absolute)
The heading is positioned to the
top right, and the paragraphs
start at the top of the screen (as
if the heading were not there).
- Fixed Positioning (position:fixed)
The heading has been placed in
the center of the page and 25%
from the top of the screen. (The
rest appears in normal flow.)
- Floating Elements
The heading has been floated to
the left, allowing the paragraphs
of text to flow around it.

**CLEARING FLOATS**
- clear
The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. It can take the following values:
- left
The left-hand side of the box should not touch any other elements appearing in the same containing element.
- right
The right-hand side of thebox will not touch elements
appearing in the same containing element.
- both
Neither the left nor right-hand sides of the box will touch
elements appearing in the same containing element.
- none
Elements can touch either side.

**CREATING MULTI-COLUMNLAYOUTS WITH FLOATS**
- width 
- float
- margin

**Screen Sizes**
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

**Screen Resolution**
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.


Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.

***MOST IMPORTANT TO KNOW***
- < div> elements are often used as containing elements
to group together sections of a page.
-  Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.
- The float property moves content to the left or right
of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
 You can include multiple CSS files in one page.






