## HTML

- ### Introduction (pp.2-11)
    - The introduction was essentially an overview of the book how it would handle HTML  and CSS as you go and then how the web works to know how coding fits in

- ### Structure (pp.12-39)
    - How web pages are structured
    - Word is similarly able to be structured as a web page
    - HTML uses code to provide the affects:
        - Elements - characters that live inside angled brackets
            - Usually made up of two tags; an opening tag and a closing tag
                - Opening tag example (<p></p>)
            - Tags act like containers to tell you something about the information that lies between their opening and closing tags
        - Attributes - provide additional information about the contents of an element
            - Appear on the opening tag of the element and are made up of two parts; a name and a value separated by an equals sign
                - Name and value example - lang="en-us"
        - Body - Everything inside this element is shown inside the main browser window
        - Head - You may see this and it will be before body.  This contains information about the page vs shown on the page.  Often has title inside the head element.
        - Title - The contents are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page if your browser uses tabs

- ### Extra Markup (p.176-199)
    - Every web page should begin with the document type so that other browsers know which version is running.  (!doctype html) (used parenthesis instead of brackets for documenting's sake)
    -  To make comments/comment out an area,(!-- --) - comments go between the - signs in the brackets (used parenthesis instead of brackets for documenting's sake)
    - ID Attribute - a global attribute because it can be used on any element - it is used to uniquely identify that element from other elements on the page
    - Class Attribute - used to uniquely identify several elements on the same page
    - Block Elements - examples are h1, p, ul, and li
    - Inline Elements - examples are a, b, em, and img
    - Grouping Text and Elements in a Block - use div
    - Gruoping Text and Elements inline - use span
    - Iframes - is like a little window that has been cut into your page.  Attributes that you will need to use with it are src, height, and width.  Older HTML versions support attributes such as scrolling and frameborder.  Seamless is a new HTML 5 attribute.
    - Information About Your Pages:
        - meta - lives inside the head element and contains infor about that web pages.  Does not have a closing tag.  Most common attributes are name and content.  Ex.  meta name="...." [next line] content="...."/>
        -  Addtional attributes are:
            - description - description of page
            - keywords - list of comma-separated words that a user might searh on to find the page
            - robots - indicates whether search engines should add this page to their search results or not
                - noindex = should not be added
                - nofollow = should be added but not any pages that it links to
            - author - defines the author of the page
            - pragma - prevent page caching
            - expires - can be used to specify when the page should expire from being cached
    - Escape Characters - you have to use alternate text to get them to show up in your browser.  Make sure to check that they show up like you are wanting

- ### HTML5 Layout (pp.428-451)
    - Traditional HTML layout required a lot of divs to create the sections (ex. div article).  Now, the sections can be worked without the divs (ex. article).
    - Headers and Footers - each section can have it's own header and footer
    - Navigation - nav is used to contain the major navigational blocks
    - article - acts as a container for any section of a page that could stand alone and potentially be syndicated
    - aside - has two purposes, depending on whether it is inside an article element or not
        - Used inside an article element - it should contain info related to the article but not essetial to is overall meaning.
        - Used outside of article element - acts as container for content that is related to the entire page
    - section - groups related content together and typically each section would have its own heading. Has a closing.  Also, if you have a long article and you need to split it up, section can do that.
    - hgroup - groups together a set of h1 through h6 elements that is being treated as one single heading
    - figure - used to contain any content that is referenced from the main flow of an article (not just images)
        - Examples of usage:  images, videos, graphs, diagrams, code samples, and text that supports the main body of an article    
        - figcaption - also contained in a figure and provides a text description for the content of the figure
    - Linking around block-level elements
        - a - a href and needs closing - makes the whole block into a link
        
- ### Process & Design (pp.452-475)
    - Who is the target audience?
        - Individuals
        - Companies
    - Why are people coming to the website?
        - What are the key motivations?
        - What are their specific goals?
        - What are they trying to achieve?
    - What information do your visitors need?
    - How often will people visit your site?
    - Designing your site
        - Site Maps - how your site will be organized
        - Wireframe - drawing out your site design
        - Getting your message across
            - Content of page
            - Prioritizing what design elements to emphasize key info
            - Organizing through grouping in blocks or chunks, like items
            - Visual hierarchy draws the eye to a key aspect
                - Size - headings and key points relatively large
                - Color - foreground and background color to draw attention to key messages
                - Style - to make elements stand out
                - Images - create high visual contract
            - Grouping
                - Prosimity grouping
                - Closure grouping
                - Continuance grouping
                - White space promoting
                - Color - background
                - Borders - around whole element
            - Similarity of items grouped together
                - Consistency - ex. book reviews use same font and color scheme
                - Headings demonstrate similarity
            - Navigation
                - Concise
                - Clear
                - Selective
                - Context
                - Interactive
                - Consistent
## Javascript

- ### The ABC of Programming (pp, 11-52)
    - Start with the big picture of what you want to achieve, and break that down into smaller steps
        1.  Define the goal - what do you want to achieve?
        2.  Design the script - split the goal into a series of tasks
            - Sketching out the tasks in a flow chart
        3.  Code each step
    - From steps to code
        - Vocabulary - the words that computers understand
        - Sytax - how you put those words together to create instructions computers can follow
        - Objects (things) - each physical thing in the world is an object and are in instances
        - Properties (characteristics) - each property has a name and a value and the pair tells you somthint about each individual instance of the object
        - Event - computer saying "hey this just happened".  Can be used to trigger different types of functionality
        - Methods - represent how people (or other things) interact with an object in the real world.  Can contain lots of instructions that together represent one task
            - Tell you something about the object
            - Change the value of one or moe of that object's properties
        - Objects
            - document
            - window
##  Javascript, CSS, and HTML Working Together

HTML - the content layer
CSS - the presentation layer
Javascript - the behavior layer

### Objects and Methods

Document - the document object represents the entire web page.  All web browsers implement this obhject, and you can use it just by giving its name.

Write - the write() method of the document object allows new content to be written into the page where the -script- element sits.

- Ex.document.write('Good afternoon!')
- Document = document
- Method = write('Good afternoon!')
- Period(.) = Member Operator
- 'Good afternoon"' = Parameter.  Tells write what to write.

Javscript will run wherever HTML finds it in the coding

