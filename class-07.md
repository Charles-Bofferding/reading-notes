# 201 Course Notes

## 4/13/2021 201

# *Object Oriented Programming & HTML Tables*

## **HTML Tables**

HTML tables can be used to display data cleanly if made well. The below table is an example of formatting.

<table border = "2">
  <thead>
    <tr>
      <td>Elements</td>
      <td>Meaning</td>
    </tr>
  </thead>
  <tr>
    <td>Table Heading (TH)</td>
    <td>Adds names to the ides, helps people who have screen readers know what the function of the table is</td>
  </tr>
    <tr>
    <td>Colspan</td>
    <td>Makes a cell span multiple column spaces</td>
  </tr>
    <tr>
    <td>Rowspan</td>
    <td>Makes a cell span multiple row spaces</td>
  </tr>
</table>

## **Object Oriented Programing**

- You can declare single objects, these will be started with no properties and can then have them assigned

  ~~~ 
  var theObject = new Object(); 
  theObject.name = 'Jeffery';
  ~~~

- You can create a constructor for objects to automatically make one that already has properties. In the example below the an object is made with three properties and a function. When creating multiple objects make sure that they are each given unique names

  ~~~ 
  function theObject (first, second, third){
    this.height = first;
    this.width = second;
    this.length = third;

    this.yesManFunction = function(){
      return true;
    }
  }
  ~~~

- More properties can be added to an object later, though for simplicity it is best if you keep objects mostly identical to each other so you can better know how your code is going to react.
- Function inside of objects are classified as methods
- Arrays are themselves objects with already defined linking of their key value pairs to the index. More interestingly Arrays can be filled with objects making a fun little recursive box.



[Go Back](README.md)

[Hard Link to this Full Live Page](https://charles-bofferding.github.io/reading-notes/class-07.html)