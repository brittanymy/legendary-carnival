# legendary-carnival
# Advanced CSS Challenge: Professional Portfolio

## User Story
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position

## Acceptance Criteria
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
    THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
    THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
    THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
    THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
    THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
    THEN I am presented with a responsive layout that adapts to my viewport

# !! TODO
-   Adjust color schemes -> Dark mode
-   Add/Fix content of html
-   Change icons & links
-   Add appropriate images -> (adding my image to blob svg using figma?)
-   Adjust some media query styling for larger screens -> about me img & scroll styles

### What I've Learned 
# General
-   VS Code Shortcuts -> Allows me to code faster.
-   Comments -> Gives my code labeled sections, allowing my code to be easier to read and revisit when needed.
-   Debugging -> Tutorial was outdated. Debugging was required for code to function properly.

# CSS
VARIABLES
-   Root (var) -> Sets global variables for style sheet.  
-   Media Queries -> Allows webpage to fit multiple screen sizes. Ex. Mobile, Desktop, Tablets. 
-   Google fonts -> Gives you accessability to multiple fonts outside of default css fonts. 

ELEMENTS
-   Margin-bottom -> Sets margin area for the bottom of an element. 
-   Z-index -> Specifies stack order of an element. This only works on positioned elements.
-   Gap -> Establishes space between rows & columns. 
-   Transitions -> Controls animation speeds for css properties. 
-   Box-shadows -> Adds shadow effects around an elements frame. 
-   Transform (rotate) -> 
-   Cursor effects -> Gives user animation effects when interacting with webpage. 
-   Display: flex/block -> Specifies how an element will be displayed.
-   Grid columns -> Specifies a grid's item size & location within a grid column.
-   Hover Styles -> Used as a part of a selector to elements when the user mouses over them.
-   Transparent (Opacity) -> Makes background elements visible through the top element. 
-   Visibility: -> Shows/hides an element without changing the layout of the document. 
-   Content:''; -> Used with ::before & ::after pseudo-elements to insert content.
-   . , > -> Placing these between elements allows you to apply different effects to multiple styles. 
-   [Data content] -> A data attribute allows us to apply styles using the added information in our HTML elements. 
Conversions
-   Fr (fractions) ->  A unit length that represents a fraction.     
-   REM to pixels -> REM stands for root em and is in reference to the root elements font size.

COLORS
-   Rgb/rgba -> Color values and their extensions. This allows the developer to specify the opacity of a color. 
-   Hsl colors <-> hex -> HSL stands for hue, saturation, and lightness. HSL is based off of the color wheel similarly to rgb colors. Hex aka hexadecimal sets a specific color value using numbers and letters.

# HTML
STRUCTURED HTML
-   Semantic html -> Reinforces the meaning of the information in web pages.
-   Divs -> Defines a division or section in an HTML document.

IMAGES & ICONS
-   Icons -> Open source icons.
-   Svgs -> A container for graphics. Gives you methods for drawing paths, boxes, circles, text, etc. 

CSS & JS
-   Classes & Ids -> Points to multiple classes/ids for css elements. Id is limited to one use while classes can apply to multiple. 
-   CSS & JS linked -> CSS & JS are often filed separately and must be linked in HTML to apply your scripts and styles.
-   Swiper -> Mobile accelerated transitions. This is a third party slider. 
-   [Data content] -> A data attribute that allows us to store extra information in standard HTML elements. 

# JS
-   const vs var vs let -> globally/locally/blocked scope. -> I found const and let are more commonly used but have limitations to where/how often they can be declared. 
-   this. -> Refers to an object depending on how it is used. Alone it refers to a global object. In an object method it refers to the object.
-   .remove -> Removes the element from the DOM.
-   .add -> Adds a new element with a value to the end of an object. 
-   .length -> Returns you the character length of an object.
-   => -> Arrow functions allow us to write shorter functions. 
-   getElementByID, getElementByClassName -> Calls an element by id or class to be used in a function in our script. 

*   All rights reserved to Bedimcode.