# 201 Course Notes

## 4/14/2021 201

# *CSS Layout*

From the last time I read part of this chapter a very useful cheat sheet link is [here.](https://learn-the-web.algonquindesign.ca/topics/css-layout-cheat-sheet/)

**Element Basics**
- Block level elements take up as much space as possible to fill the element that they are in
- Inline elements can flow around other elements and vice versa.
- Box offsets can be used to place an element relative on the page
- position:static: The standard behavior for blocks. This does not need to be called and is assumed for everything until told otherwise
- position:relative tells the element to be at a certain offset of where it would normall be.
- position:absolute: gives a location for the box to go and it will then ignore all other typical rules about ositioning to go right to the specified area.
- position:fixed: Places the element in an absolute location relative to the browser window.

**Advanced Element Properties**
- Z-Index: If there are overlapping elements you can control what is on top of others by setting this. Higher numbers go above lower numbers.
-Float: place an element as far to the left or right as possible within the normal area that element is allowed in.
-Clear: use this to have an element check and make sure it is clear of touching similar elements within it's parent box. You also need to define a direction.
- Layout Grids: A useful way to think about how you are going to layout a webpage. It helps to add cohesion between different elements and just makes everything look nice and neat.
- CSS Frameworks: These are pre-made CSS rule sets that you can move between projects. Kind of the definition of not re-inventing the wheel each time. A good front end developer will probably have a catalogue of these.


[Go Back](README.md)

[Hard Link to this Full Live Page](https://charles-bofferding.github.io/reading-notes/class-08.html)