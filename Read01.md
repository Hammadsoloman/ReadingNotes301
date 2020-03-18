# Responsive Web Design

## What is Responsive Web Design?
**Responsive Web Design is about using HTML and CSS to automatically resize,
hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones)**

*When making responsive web pages, add the following <meta> element in all your web pages.
<meta name="viewport" content="width=device-width, initial-scale=1.0">
  This will set the viewport of your page, which will give the browser instructions on how to control the page's dimensions and scaling.*

* If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size
* The HTML <picture> element allows you to define different images for different browser window sizes.
* The text size can be set with a "vw" unit, which means the "viewport width".
That way the text size will follow the size of the browser window


## Media Queries

**In addition to resize text and images, it is also common to use media queries in responsive web pages.
With media queries you can define completely different styles for different browser sizes.
Example: resize the browser window to see that the three div elements below will display horizontally 
on large screens and stacked vertically on small screens.**

## What is SMACSS?
#### Smacss (Scalable and Modular Architecture for CSS) is a style guide that follows five simple categories. SMACSS is a way to examine your design process and to fit those rigid frameworks into a flexible thought process. It is an attempt to document a consistent approach to site development when using CSS. And really, who isn’t building a site with CSS these days?!

### Which are these categories?

##### Base
##### Layout
##### Module
##### State
##### Theme

**The idea of this architecture is to not mix code of several categories on a single file because it can be very complicated to find a simple line of code to change. Most of the purpose of this categorization is to codify patterns —things 
that repeat themselves within our design. Repetition results in less code, easier maintenance, and greater consistency in the user experience.**

* Base: are the defaults values. They are like the padding, margin, border, font and other properties, this values are used on the entire web site and all elements. *

* Layout: divides a page into sections with elements like header, footer, main page, etc. Layouts hold one or more modules together. Often developers show layout elements by prefixing the class with l-, e.g. l-header, l-footer. 

* Modules: are the reusable, modular parts of our design like navbar, sidebar and some elements that are repeated in the site. 

* State: are ways to describe how our modules or layouts will look when they are into a particular state (e.g. active, inactive, expanded, hidden). These are prefixed with is-, e.g. is-active, is-inactive, is-expanded, is-hidden. 

* Theme: Theme rules are similar to state rules in that they describe how modules or layouts might look. It is more applicable for larger sites with shared elements that look different throughout. 

* Following these simple rules you can order your files easily. At the time you need to find a line or a file, it will be more easy because you know where it is and you not will lose too much time. Also, working
with a team will be more easy to understood the CSS and they will not have issues with the code; remembers that your code have be scalable and easy to understand. 


## CSS float Property

#### Definition and Usage
**The float property specifies how an element should float.**

*Note: Absolutely positioned elements ignores the float property!*

*Note: Elements after a floating element will flow around it. To avoid this, use the clear property or the clearfix hack (see example at the bottom of this page).*


