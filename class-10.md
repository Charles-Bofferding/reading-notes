# 201 Course Notes

## 4/16/2021 201

# *Error Handling & Debugging*
- When debugging it is important to realize if the problem has a global context or an execution context. Global will probably throw an error at the initialization of a webpage and is a bit easier to catch because of it. ecution context might be something that is not initially run on the page and could surface later when a particular functionality runs into an error inside a function or something similar.
- Knowing the scope of where the error occurs and what else is happening in your code will help narrow down the search for a bug
- Errors have very descriptive names, and honestly the best way to deal with them is to google them. I know that the book goes into some great detail about pre-defining all the errors you might see but honestly just google it, that is a faster way top figure out what is going on.
- Dev tools like the console can be invaluable when going through your debugging process.
console gives very helpful info. Knowing what line the code throws an error doesn't mean you know what exactly is happening but it really helps narrow it down.
- Breakpoints are ways for you to stop the computer from running at machine speed and slow down into a power point presentation. Instead of automatically moving through the lines of code breakpoints make it so a user input is required for each next coding step. This can be useful because the console can then be used to check local variables and different status's in the middle of the code to help figure out where a data type becomes NaN or other similar checks for mid-stream processes.
- Console Logging is a very helpful tool that does a similar thing to breakpoints of giving you insight into what is happening in your code without slowing the pace down to a crawl. These should probably be commented out before you hit full release.
- Exceptions are events where your code hits something that stops the functionality completely. It is not best practice but if you have no way to stop them from happening you can catch the error in a way that makes the computer do some other bit of code and keep on moving if it does run into a predefined error. 
- Just a personal note here. Be careful whenever the console tells you there is an error on a specific line, it could be syntax from the line above that is messing with it. Check around the problem area for mistakes as well.


[Go Back](README.md)

[Hard Link to this Full Live Page](https://charles-bofferding.github.io/reading-notes/class-10.html)