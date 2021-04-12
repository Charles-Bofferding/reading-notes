# 201 Course Notes

## 4/12/2021 201

# *JS Object Literals and DOM Tree*

**Object Literals**

An object is a discrete grouping of functions and variables. Variables will be called properties and functions will be called methods. The names of these variables and methods are called keys. Literal notation can be used to make objects by defining all aspects of the object.

**Document Object Model**

A Document Object Model is the way that a webpage is represented to the browser that is trying to load it. Every item inside the page will receive a node of differing types

- Document Node: The head of the tree, this is where accessing any other node starts at.
- Element Node: These nodes represent HTML elements like an h1 or paragraph tag.
- Attribute Nodes: These are always attached to an element node and are part of that larger node.
- Text Node: These are also branched from the element nodes. They can have no children so are always terminating branches of the DOM tree.
- The first step is to access specific elements. There are many methods and properties that can access elements. It is important to keep in mind that you can select multiple nodes at once, so be careful with how you select them. If you do select multiple it will return a NodeList which is a node array. It is then common to loop through the array to perform some action on each object in there.
- When storing an element node in a variable you are actually stoiring a pointer to that node instead of the node itself.
- An overview of these methods can be found [here](https://fundamentals.generalassemb.ly/11_unit/dom-cheatsheet.html). 
- Note that many browsers will add a text node if there is any amount of whitespace or character returns in the code. This can make traversing the DOM tree more tricky.
- Another thing to watch out for is the order of declaration of different parts of an HTML element will change the DOM tree layout.
- You can use the developer tools to examine a node and see all of the information stored on or in it.

**Cross Site Scripting Attacks**

- Because the DOM tree can be modified if the content is not protected a malicious actor can use this ability to modify or access information they should not be able to.
- To protect against this make sure to validate the kind of information you allow users to add or access on your page. For any content that contains operators or other reserved characters make sure to escape that content.






[Go Back](README.md)

[Hard Link to this Full Live Page](https://charles-bofferding.github.io/reading-notes/class-06.html)