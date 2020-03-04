## HTML Links, CSS Layout, JS Functions

### From the Duckett HTML book:

#### Chapter 4: Ch.4 “Links” (pp.74-93)

- Links are created using the <a> element
    - Ex of a link to an external page:  -a href="http://www.imdb.com">IMDB</a-
        - The "IMDB" is the word that the user will click on to go to the link
    - Ex of a link to an internal page:  -a href="index.html">Home</a-
        - Again, like the external page link, Home is the word that the user would click on
- The <a> element uses the href attribute to indicate the page you are linking to.
    - You can add to the link so that clicking the link opens the site in a new page
    - Example:  -a href="http://www.imdb.com" target="_blank"-
- If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.
    - When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.
- You can create links to open email programs with an email address in the "to" field.
    - Use "mailto: [email address]"
    - Remember to add a word that they click on to send an email
- You can use the id attribute to target elements within a page that can be linked to
    - At the top of a long page you might want to add a list of contents that links to the corresponding sections lower down. Or you might want to add a link from part way down the page back to the top of it to save users from having to scroll back to the top.
    - Before you can link to a specific part of a page, you need to identify the points in the page that the link will go to. You do this using the id attribute (which can be used on every HTML element). 
    - If you want to link to a specific part of a different page (whether on your own site or a different website) you can use a similar technique.
    - As long as the page you are linking to has id attributes that identify specific parts of the page, you can simply add the same syntax to the end of the link for that page.
        - Example:  -a href="http:/www. htmlandcssbookcom/ #bottom"-

#### Chapter 15: “Layout” (pp.358-404)

- -div> elements are often used as containing elements to group together sections of a page.
- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
- The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide,  X and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks. 
- You can include multiple CSS files in one page. 

### From the Duckett JS book:

#### Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)

- Functions allow you to group a set of related statements together that represent a single task. 
    - Example function:
    --var msg = 'Sign up to receive our newsletter for 10% off!'; function updateMessage() { var el = document.getElementByld('message'}; el .textContent = msg; } updateMessage(};-- 
- Functions can take parameters (informatiorJ required to do their job) and may return a value. 

#### Article: “6 Reasons for Pair Programming”

##### How does pair programming work?
While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.

1. Greater efficiency
    - Produces higher-quality code that doesn’t require later effort in troubleshooting and debugging (let alone exposing users to a broken product)
2. Engaged collaboration
    - When developers pair program, they rely more on each other and can often find a solution together without needing to ask for additional help
3. Learning from fellow students
    - The less experienced developer benefits from the experienced developer’s knowledge and guidance, and the latter benefits from explaining the topic in their own words, further solidifying their own understanding
4. Social skills
    - When working with someone who has a different coding style, communication is key
5. Job interview readiness
    - A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen
6. Work environment readiness
    - Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product