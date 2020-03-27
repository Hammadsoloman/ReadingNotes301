# Responsive Web Design

## What is Responsive Web Design?
**Responsive Web Design is about using HTML and CSS to automatically resize,
hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones)**

### What is the difference between Responsive and adaptive?
**Responsive generally means to react quickly and positively to any change, while adaptive means to be easily modified for a new purpose or situation, such as change**

*When making responsive web pages, add the following <meta> element in all your web pages.
<meta name="viewport" content="width=device-width, initial-scale=1.0">
  This will set the viewport of your page, which will give the browser instructions on how to control the page's dimensions and scaling.*

* If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size
* The HTML <picture> element allows you to define different images for different browser window sizes.
* The text size can be set with a "vw" unit, which means the "viewport width".
That way the text size will follow the size of the browser window
* Taking the flexible layout concept, and formula, and reapplying it to all parts of a grid will create a completely dynamic website, scaling to every viewport size.


## Media Queries

**In addition to resize text and images, it is also common to use media queries in responsive web pages.
With media queries you can define completely different styles for different browser sizes.
Example: resize the browser window to see that the three div elements below will display horizontally 
on large screens and stacked vertically on small screens.**

* Logical operators in media queries help build powerful expressions.

* Using the viewport meta tag with either the height or width values will define the height or width of the viewport respectively.

![image](https://enginetemplates.com/wp-content/uploads/edd/2017/07/et-web-design-free-responsive-joomla-template.png)

## What is SMACSS?
#### Smacss (Scalable and Modular Architecture for CSS) is a style guide that follows five simple categories. SMACSS is a way to examine your design process and to fit those rigid frameworks into a flexible thought process. It is an attempt to document a consistent approach to site development when using CSS. And really, who isn’t building a site with CSS these days?!

### Which are these categories?

#### Base — These are your defaults (html, body, h1, ul, etc)
#### Layout — These divide the page into major sections
#### Module — These are the reusable modular components of a design
#### State — These describe how things look when in a particular state (hidden or expanded, active/inactive)
#### Theme — These define things like a color scheme or typographic treatment across a site

**The idea of this architecture is to not mix code of several categories on a single file because it can be very complicated to find a simple line of code to change. Most of the purpose of this categorization is to codify patterns —things 
that repeat themselves within our design. Repetition results in less code, easier maintenance, and greater consistency in the user experience.**


* Following these simple rules you can order your files easily. At the time you need to find a line or a file, it will be more easy because you know where it is and you not will lose too much time. Also, working
with a team will be more easy to understood the CSS and they will not have issues with the code; remembers that your code have be scalable and easy to understand. 

![image](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F786d726d-bfee-49ca-bcf0-cbc5dcc072ab%2Fimage3_apwm5l.png?table=block&id=d118452d-b6ff-4d74-9b7b-a5a7d53a4946&width=2000&cache=v2)

## CSS float Property

#### Definition and Usage
**Float is a CSS positioning property. To understand its purpose and origin, we can look to print design. In a print layout, images may be set into the page such that text wraps around them as needed. This is commonly and appropriately called "text wrap". Here is an example of that**

**The clear property is used to specify that which side of floating elements are not allowed to float. It sets or returns the position of the element in relation to floating objects**

*Note: Absolutely positioned elements ignores the float property!*

*Note: Elements after a floating element will flow around it. To avoid this, use the clear property or the clearfix hack (see example at the bottom of this page).*

#### main problems with float:
* Pushdown : is a symptom of an element inside a floated item being wider than the float itself (typically an image).
* Double Margin Bug :  if you apply a margin in the same direction as the float, it will double the margin. Quick fix: set display:   inline on the float, and don't worry it will remain a block-level element.
* The 3px Jog : is when text that is up next to a floated element is mysteriously kicked away by 3px like a weird forcefield around the float.
* Bottom Margin Bug is when if a floated parent has floated children inside it, bottom margin on those children is ignored by the parent. Quick fix: using bottom padding on the parent instead.

![image](https://i.stack.imgur.com/XglFz.jpg)


All copyRight for @Hammad



