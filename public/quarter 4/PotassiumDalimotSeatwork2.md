# Step 1 (Static vs Relative)
## What changed compared to the default static positioning? Try to give different values to top and left or you can change it to bottom, right.
### The element's position was changed relative to its original top and left values

# Step 2 (Fixed)
## What happens when you scroll the page? Why does the footer behave differently from position relative?
### When you scroll the page, the footer doesn't move and stays stuck at the bottom. The footer behaves differently from position relative because the fixed position is relative to the screen while the relative position is relative to the element's original position.

# Step 3 (Absolute)
## What is the effect of position: absolute on an element? How is it different from fixed?
### The position absolute moves the element relative to its nearest positioned ancestor.  On the other hand, position fixed is relative to the screen or viewport.

# Step 4 (Absolute)
## Why does the notice appear on top of the content? What happens if you swap the z‑index values?
### The notice appears on top of the content because it has a higher z-index than content.  The higher the z-index, the higher you can stack over other elements.  If you swap the z-index values, content will have a higher z-index and it will appear on top of notice.

## a. Could you summarize the differences between the CSS position values (static, relative, absolute, fixed)?
### Static is the default position of the element, relative position is relative to the element's original position, absolute position is relative to the element's nearest positioned ancestor and fixed position is relative to the element's viewport.

## b. How does absolute positioning depend on its parent element?
### The absolute positioning depends on its parent element by finding the nearest ancestor element with relative, fixed or absolute position.  If it can't find one, the element takes up the whole page.

## c. How do you differentiate sticky from fixed (you can research on sticky)?
### When you use sticky position, the element is positioned relative to its nearest scrollable ancestor while fixed position makes the element relative to the viewport.

## d. If you were designing a webpage for a school event, how might you use positioning to highlight important information? Please give concrete examples.
### If I was designing a webpage for a school event, I would use fixed positioning for a navigation bar and sticky positioning for a header.  I would also use the overlay notice or z-index for pop-ups like advertisements or reminders.