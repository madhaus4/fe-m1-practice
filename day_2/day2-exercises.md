#Chapters 3 Lists & 4 Links

There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?
- Ordered: a numbered list, (<ol> and <li> elements).
- Unordered: a bulleted list, (<ul> and <li> elements).
- Definition: a set of terms with definitions of those terms, (<dl> <dt> and <dd> elements).

What is the basic structure of an element used to link to another website?
- The basic structure to link another website is:  <a href="link goes here">text for link goes here</a>

What attribute should you include in a link to open a new tab when the link is clicked?
- To open the link in a new tab, the target attribute needs to be used with a value of _blank in the opening tag.

How do you link to a specific part of the same page?
- Add an id attribute to elements you want to link.  Then, use # followed by the id.  <a href="#aboutme">About Me</a>


#Chapters 10 Introducing CSS, 11 Color & 12 Text

What is the purpose of CSS?
- The purpose of CSS is to make a web page visually appealing.  

What does CSS stand for? What does cascading mean in this case?
- CSS stands for Cascading Style Sheets.

What is the basic structure of a CSS rule?
- The basic structure of a CSS rule contains a selector and a declaration.  The selector represents which element the rule applies to and the declaration is how that element should be styled.  
EX.   p {
        font-family: Arial;}

How do you link a CSS stylesheet to your HTML document?
- You can use a link element inside the head element to link a CSS file to the HTML document.  The link element will use three attributes: href, type, and rel.  href specifies the location of the CSS file.  type specifies the type of document being linked.  rel specifies the relationship of the HTML to CSS pages.
EX.   <link href="css/styles.css" type="text/css" rel="stylesheet" />  

When is it useful to use external stylesheets as opposed to using internal CSS?
- It's useful to use an external stylesheet when you are building a website with more than one page.  Doing so, you only need to edit the stylesheet which will then update all the pages linked to it instead of repeating code on each page.

Describe what a color hex code is.
- A color hex code is a six digit number that represents the amount of red, green and blue there is in a color.  

What are the three parts of an HSL color property?
- The three parts of an HSL color property are: hue, saturation, and lightness.  

In the world of typeface, what are the three main categories of fonts? What are the differences between them?
- The three main categories of fonts are:
  1. Serif
  2. Sans-serif
  3. Monospace

When specifying font-size, what are the main three units used?
- The main three units used when specifying a font size are:
  1. Pixels
  2. Percentages
  3. EMS
