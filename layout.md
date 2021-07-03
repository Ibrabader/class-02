# LAYOUT 
- Controlling the position of elements 
- Creating site layouts 
- Designing for different sized screens


### POSITIONING : 
- the key concept is in bulding blocks 
- CSS treats each HTML element as if it is in its 
own box. This box will either be a block-level 
box or an inline box 
- containing elements : 
If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element.

### ControLLing the position of eLements
- **Normal flow** : Every block-level element 
appears on a new line, causing 
each item to appear lower down 
the page than the previous one. 
Even if you specify the width 
of the boxes and there is space 
for two elements to sit side-by-
side, they will not appear next 
to each other. This is the default 
behavior (unless you tell the 
browser to do something else).
- **Relative Positioning** : This moves an element from the 
position it would be in normal 
flow, shifting it to the top, right, 
bottom, or left of where it 
would have been placed. This 
does not affect the position of 
surrounding elements; they stay 
in the position they would be
in normal flow.
- **Asolute Positioning** : This positions the element 
in relation to its containing 
element. It is taken out of 
normal flow, meaning that it 
does not affect the position 
of any surrounding elements 
(as they simply ignore the 
space it would have taken up). 
Absolutely positioned elements 
move as users scroll up and 
down the page.


### Screen Sizes

- Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

- The size of a user’s screen affects how big they can open their windows and how much of the page they will see. There are also an increasing number of handheld devices.
Fixed Width Layouts

### Fixed width layout

-  designs do not change size as the user increases or decreases the size of their browser window.

**Summary**

-` <div>` elements are often used as containing elements to group together sections of a page.

- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)

- Pages can be fixed width or liquid (stretchy) layouts.

- Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).

- Grids help create professional and flexible designs.

- CSS Frameworks provide rules for common tasks.
You can include multiple CSS files in one page.
