# 201 Course Notes

## 4/21/2021 201

# *Local Storage*

**The Past**

- Local storage for web applications used to only be available in the form of cookies
  - These have very limited storage
  - They are not very secure as a form of information transfer
- For a long time storage was limited to a single browser or being reliant on third party applications to handle it for them.

**The Present**
- HTML5 storage is a way to store key/value pairs locally in the web client that will persist
  - The key must be a string, you might need to parseInt() or parseFloat() to change data into a string to use for comparison
- localStorage.getItem takes a string and returns the stored information
- localStorage.setItem takes a string and data and sets it into memory
- Typically nowadays each page gets  5mb of data in storage.

**The Future**
- Google is working on making cross platform open source ways to better store information
  -having code that will work across any browser would be incredibly useful
- Unfortunately it is difficult to get a group of designers to agree on anything, where to order lunch from is a long debate so a global standard is still a long way off.


[Local Storage Syntax according to w3](https://www.w3schools.com/htmL/html5_webstorage.asp)


[Go Back](README.md)

[Hard Link to this Full Live Page](https://charles-bofferding.github.io/reading-notes/class-13.html)