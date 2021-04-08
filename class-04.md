# 201 Course Notes

## 4/08/2021 201

# *HTML Links, JS Functions, and CSS Layout*

**HTML Links**
- Links are created using ```<a href="the_link"> Displayed_name</a>``` elements in HTML. If you wish to link to an internal page instead write the link as if the working directory is the root level and from there define the relative path.
- Emails can be created by changing the href value be ```mailto:sampleEmail@123.com```.
- if you add in the ``` target=="_blank" ``` after the href definition the link will attempt to open a new window.
- You can also change the href definition to a section ID to link part of the same page that you are on.

**CSS Layout**

- Elements in in the HTML page can be controlled to a great degree with CSS. This chapter focuses on how you can move different elements boxes relative to each other. Fixed positioning is anchored to an absolute value somewhere, while relative positins like float are reactive to other elements in the page.
- Use [this](https://learn-the-web.algonquindesign.ca/topics/css-layout-cheat-sheet/) cheat sheet to see the pifferent ways to position elements in CSS, it uses pictures and stuff, very intuitive.




**JS Functions**

- Functions let you group several code steps together and contain them to be called elsewhere in your code. They can accept parameters and can give outputs but that will be defined by the code in the function. A function declaration looks like:

``` function theName() {Some number of lines of code}```

- Before calling a function ensure that you know what parameters it needs, what the limits to those parameters should be, and what you expect the return of the function to be. A function with several different returns will place them in an array and you will need to be careful in specifying which part of the array you are looking for.


[Go Back](README.md)

[Hard Link to this Full Live Page](https://charles-bofferding.github.io/reading-notes/class-04.html)