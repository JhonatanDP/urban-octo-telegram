# Refactoring a web page to meet accessibility standards and optimized it for search engines.

Project Repository address: https://github.com/JhonatanDP/urban-octo-telegram

Project live web page: https://jhonatandp.github.io/run-buddy/

## Full Page
![full-Site](https://user-images.githubusercontent.com/106892660/174201556-6aa46e77-5d0d-4d46-aefe-464cfe6ea090.png)

## Problems.

1. - The website code was not specify, too many div.
2. - Some CSS rules were repetitive.
 
 ### Screenshot of parts in the starter code for the html and css.
 
 ![starter-code](https://user-images.githubusercontent.com/106892660/174122421-04d3f4e4-c1aa-44a0-93e4-f2c1fb94eca3.png)

## Changed to HTML Code

- Title of the page changed to Horiseon.

- Html code divided by group/Sections.

- Div tag changed for the corresponding element: header, nav, article, etc.
![tag-name-changed](https://user-images.githubusercontent.com/106892660/174125438-56feeb8d-4f95-4c52-9d4c-d2fa83ea8bb1.png)

- Added ALT attribute and description for images requirement.
![ALT-attributes](https://user-images.githubusercontent.com/106892660/174126418-55db720b-d237-4a8b-8aa2-2127ff93c8fe.png)

- Added id attribute to the missing element.

- div class footer changed to footer tag.

#### Before
![div-footer](https://user-images.githubusercontent.com/106892660/174127023-aef0d62c-238f-4cc0-a2b4-285ea5fd9b96.png)
#### After
![footer](https://user-images.githubusercontent.com/106892660/174127096-97f2d16d-69fe-41f5-9d66-fd4d36fd03ef.png)


- Combine different classes because they used same CSS properties.

## Changed to CSS Code

- I re-organized the CSS file based on the structure of the html file.

- Because the color #ffffff is used multiple time in the page.  I made a group selector for that color.
![group-same-color](https://user-images.githubusercontent.com/106892660/174128570-0c11ccd4-cf16-4ffa-b4ac-d93c3be51e23.png)

- Changing class selector to element selector where needed.
  * Class header changed to element selector
  * Class footer changed to element selector
#### Before
![Class header](https://user-images.githubusercontent.com/106892660/174129392-1f97ba08-47ec-4cdc-ac52-8cba92a69150.png)
#### After
![element-selector](https://user-images.githubusercontent.com/106892660/174129560-8ed2788f-8925-444b-b193-d112066e4133.png)

- Combined the {header nav ul} list-style-type: to header nav selector

- Combined attributes for articles inside content section because they used same attributes.
#### Before
![content-before](https://user-images.githubusercontent.com/106892660/174129990-a7155325-a196-4bcc-8520-d9ecd84a1cbc.png)
#### After
![content-after](https://user-images.githubusercontent.com/106892660/174130197-689bcbc6-3ec5-4896-9d67-d81cb6caf4a3.png)

- Combined attributes for articles inside the benefits class.

- Add comments to CSS and html files.


