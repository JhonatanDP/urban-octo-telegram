# Refactoring a web page to meet accessibility standards and optimized it for search engines.

Project Repository address: https://github.com/JhonatanDP/urban-octo-telegram

Project live web page: https://jhonatandp.github.io/run-buddy/

## Problems.

1. - The website code was not specify, too many div.
2. - Some CSS rules were repetitive.
 
 ### Screenshot of parts in the starter code for the html and css.
 
 ![starter-code](https://user-images.githubusercontent.com/106892660/174122421-04d3f4e4-c1aa-44a0-93e4-f2c1fb94eca3.png)

Title of the page changed to Horiseon

Html code divided by group/Sections

div tag changed for the corresponding element: header, nav, article,

Added ALT attribute and description for images requirement.

Added id attribute to the missing element.

div class footer changed to footer tag.

Combine article classes because they used same attribute in the CSS file.   


CSS Code

I re-organized the CSS file based on the structure of the html file.

Because the color #ffffff is used multiple time in the page.  I made a group selector for that color. Header, a,p, article class inside content class. 

Changing class selector to element selector where needed.

Class header changed to element selector
Class footer changed to element selector

Combined the {header nav ul} list-style-type: to header nav selector

Combined attributes for articles inside content section because they used same attributes.

Combined attributes for articles inside the benefits class.

Add comments to CSS and html files


