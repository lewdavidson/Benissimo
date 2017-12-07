# Planning Document
### By Amy and Lew

## Website Concept.
A culinary magazine site.

## Layout
No more than 5 layout sections.

* Nav
* Header
* Footer
* Article section 1
* and Article section 2.

4 Unique Wireframes
Responsiveness.
Each wireframe needs mobile, tablet, and desktop versions.

### First Wireframe: Our pick!

![wireframe 1 sketch](https://i.imgur.com/F41I9iz.jpg)
![wireframe 1 tablet sketch](https://i.imgur.com/c29HaOE.jpg)
![wireframe 1 mobile sketch](https://i.imgur.com/AHFWlAn.jpg)


### Second Wireframe

![wireframe 2 sketch](https://i.imgur.com/646LUdl.jpg)
![wireframe 2 tablet sketch](https://i.imgur.com/yPLc4kJ.jpg)
![wireframe 2 mobile sketch](https://i.imgur.com/YnJu6sO.jpg)

### Third Wireframe

![wireframe 3 sketch](https://i.imgur.com/RWXU98d.jpg)

### Fourth Wireframe

![wireframe 4 sketch](https://i.imgur.com/YQlEj2w.jpg)


## SASS ELEMENTS USED

| TERM  | DESCRIPTION  | IMPLEMENTATION |
|---|---|---|
|   MIXIN    | A mixin lets you make groups of CSS declarations that you want to reuse throughout your site. | We will be using a lot of mixins, but one example is for Media Queries. This will allow us to add the media specs to any desired page element. |
|  @CONTENT  | This makes it possible to define abstractions relating to the construction of selectors and directives. | We will also be using this in our media queries. This will allow us to customize some styles, element by element, instead of adding everything to one large media query. |
|   IF STATEMENT   | @if statements are tried in order until one succeeds or the @else is reached. | We will be using if statements for our min-width and max-width values in our dynamic media queries. |
|   EACH LOOP   | The @each rule sets $var to each item in the list or map, then outputs the styles it contains using that value of $var. | We will be using an each loop to assign hex values to color variables for easier naming. |
|   VARIABLES   | Variables are a way to store information that you want to reuse throughout your stylesheet. | We will be using lots of variables, as they make it possible to call a value by an easy to remember name. |
|   NESTING   | Sass will let you nest your CSS selectors in a way that follows the same visual hierarchy of your HTML. | Nesting will be a common theme, it will help us to organize pseudo:classes along-side their parent-classes. |
|   MATH OPERATOR   | Sass has a handful of standard math operators like +, -, *, /, and %. |  We will be using a math operator to keep our grid responsive. |
|   COLOR FUNCTIONS   | Functions that alter the state of a color. |  We will use these (example compliment) to style our content in a cohesive way. |
|   7-1 PATTERN   | A standard file architecture. 7 organization folders and a single file at the root level. |  We will use this structure to organize and load our SASS files. |
|   PARTIALS   | If you have a SCSS or Sass file that you want to import but don't want to compile to a CSS file, you can add an underscore to the beginning of the filename. This will tell Sass not to compile it to a normal CSS file. | W will be importing partial files to the main.scss file to cut down on load time. |
