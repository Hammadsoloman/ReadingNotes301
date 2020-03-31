## CSS Grid Layout

**The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages
without having to use floats and positioning.**

* CSS Grid Layout (aka “Grid”), is a two-dimensional grid-based layout system that aims to do nothing less than completely 
change the way we design grid-based user interfaces.

* Grid is the very first CSS module created specifically to solve the layout problems we’ve all been hacking our way around 
for as long as we’ve been making websites.

* All direct children of the grid container automatically become grid items.

*The lines between columns are called column lines.

*The lines between rows are called row lines.

**Grid Line: The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal 
(“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.**

**display: Defines the element as a grid container and establishes a new grid formatting context for its contents.**

* When sizing rows and columns, you can use all the lengths you are used to, like px, rem, %, etc, 
but you also have keywords like min-content, max-content, auto, and perhaps the most useful, fractional units.
grid-template-columns: 200px 1fr 2fr min-content;

* You also have access to a function which can help set boundaries for otherwise flexible units. For example to set a column to be 1fr, 
but shrink no further than 200px: grid-template-columns: 1fr minmax(200px, 1fr);

* There is repeat() function, which saves some typing, like making 10 columns: grid-template-columns: repeat(10, 1fr);

* Combining all of these things can be extremely powerful, like grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));

![image](https://i.pinimg.com/236x/46/ed/1e/46ed1ea7060089aa46ec32af3d1eb55b.jpg)

