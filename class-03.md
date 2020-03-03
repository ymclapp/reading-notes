## HTML Lists, CSS Boxes, JS Control Flow

### From the Duckett HTML book:  

#### Chapter 3: “Lists” (pp.62-73)

- There are three types of HTML lists: ordered,  unordered, and definition
- Ordered lists use numbers
- Unordered lists use bullets
    - The bullets can be styled in CSS
- Definition lists are used to define terminology
    -  I like the definition lists because of the way it indents
        - -dl- -/dl- = is the definition list
        - -dt- -/dt- = is the term
        - -dd- -/dd- = is the definition
- Lists can be nested inside one another
    - A nested list will change bullet styles automatically, but you change them further with CSS styling
    - To nest, you create a -li- item and then the next line would be a new -ul- and under that would be each -li- and -/li- with it.  When the nested list is done, the ul gets closed and then the -li- that is still open from above that everthing was nested under.

#### Chapter 13: “Boxes” (pp.300-329)

- CSS treats each HTML element as if it has its own box
- You can use CSS to control the dimensions of a box
    - Height, width, min-width, max-width, min-height, max-height
    - You can also set the scrolling
- You can also control the borders, margin and padding for each box with CSS
    - Border is on the  box itself
        - Use border-width to change the line width
        - Use border-style to change the type of line
        - Use border-color to change the color of the line
        - You can change all of the above in one line by using border and listing the properties that you want
    - Margin is between the border and the next element
    - Padding is the space around the words in the box
- It is possible to hide elements using the display and visibility properties
- Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes
- Legibility can be improved by controlling the width of boxes containing text and the leading
- CSS3 has introduced the ability to create image borders and rounded borders

### From the Duckett JS book:  Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

- See class 02 notes