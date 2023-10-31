## What you'll study

- [x] Using Margin: auto on flex children
- [x] Position: absolute & relative
- [x] align self
- [x] position: fixed

## Problem

-- Facing problem with the header, as it was not taking the whole width then i just provide padding and
margin top then it took the desire space

## Positin absolute and relative

-- Position absolute is used to position the element relative to the parent element
-- Position relative is used

- when we will set position absolute to a block element two things will happen, \* element will be removed from the normal flow of the document, element will be positioned relative to the first parent element that has a position other than static

  - It shrinks down to the width it needs to accomodate its content

-- It's good to know that when we take a block level element like this div, we set it to position absoulte , it takes on some the behavior of an inline element, streches only to the width of its content;

## White Space between the images

-- The white space between the images is because of the inline-block property & they align to the baseline of the text which can create a small amount of space underneath them, to remove the white space we can use block property

-- What is actually happening is that the images are inline-block elements and inline element are given white space at the bottom and this was done originally to make sure that the parts of letters like Y and P that go below the baseline of the text don't get cut off or overlap other elements. The fact that it happens on images is just an unfortuate consequence of that.

            Align-Self

-- Align self is used to align the individual item in the flex container, it is important to note that align self only works on flex items and not on flex container, when it comes to aligning flex items, align self works exactly the same as align items, the only difference is that align self only applies to a single flex item, while align items applies to all flex items at once
