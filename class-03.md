# 201 Course Notes

## 4/07/2021 201 Day 3

# *HTML Lists, JS Control Flow, and CSS Model Box*

**HTML Lists**

- Ordered Lists: A list where all of the items are numbered and the order in which they are presented is important.
- Unordered Lists: Lists that are marked with a bullet point or similar icon but not numbered. This list is an unordered list
- Definition Lists: The only list with two types of internal elements. This list has definition terms and defiunition description. One term can have more than one description applied to it.
- Lists can be placed inside other lists

**JS Control Flow**

- All HTML elements are treated by CSS as if they live in a \"Box\". Because of this it is important to know how to modify these boxes.
- The width and height of a box can be controlled to be either absolute values, relative sizes to the rest of the page, and even set to minimum values to ensure that certain items do not scale.
- Overflow from any particular box can either be hidden or put in with the scroll overflow tag.
-Each box has a margin on the outside providing space between the border of this box and other content. The border itself wich has many size, color, and design options. The padding which sits between the content of the box and the border. And finally the content of the box.
- Using text align you can control where the content of a box sits. Know that this doesn't change how different boxes on the page interact just the internal contents
- To affect how boxes are on the page change their display attribute. Inline means that the block element will act like an inline element, block does the opposite. Inline-Block honestly wasn't super well defined and will need some playing with in the code ti get.
- Custom borders can be addded to do things like use custom images, set 3D effects through shading, and even change the border outline to different shapes.

**JS Decisions and Loops**
- Switch Statements: These are logical comparators that act as a state machine. There is an initial validation check where a variable is set to be compared. Then that input variable is compared to each switch case value in order and if it matches the code inside that switch case is run. It is important to add a break into this switch case because if you do not the comparison will then continue down the switch case statments and you might get another hit in the comparions.
- Type Coercion: Javascript will try and do comparisons and other operations on data even if the type does not match. This is tricky and has a lot of sutle rules to it so is best to try and avoid this in your code, define everything clearly.
- Logical operators are processed left to right and the first evaluation that meets the loop condition is what will be returned.
- For Loops: typically used when you want to perform a task a set number of times.
- While loops: Check a logical statement and then performs a segment of code based on that result. 
- Do While Loops: The same as while loops but the first action is to perform the code segment then the check happens. Good for things that need the input to be called and then checked. IF a failing case the code would run back to the getting input code it started with.

[Go Back](README.md)

[Hard Link to this Full Live Page](https://charles-bofferding.github.io/reading-notes/class-03.html)