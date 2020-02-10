## HTML

- ### Text (pp.40-61)
    - Adding tags, called markups, to a web page to provide extra meaning
        - Structural markup - elements to describe headings and paragraphs
            - Headings - needs an opening and closing - there are six levels of the headings h1 is for main headings and h2 is for subheadings and so on
            - Paragraphs - needs an opening and closing - p denotes a paragraph
            - Bold - needs an opening and closing - b denotes bold
            - Italic - needs an opening and closing - i denotes italic
            - Superscript - needs an opening and closing - sup denotes superscript
            - Subscript - needs an opening and closing - sub denotes sub script
            - White space - if there is more than one space or line, the browser will only display one
            - Line breaks - br / denotes a line break
            - Horizontal rules - hr / denotes a horizontal line/rule 
        - Semantic markup - extra information such as emphasis, quotes, etc. that don't affect the structure
            - Strong - needs an opening and closing - strong denotes strong and tells the browser that the content has strong importance - browsers will generally show as bold
            - Emphasis - needs an opening and closing - em denotes emphasis and subtley changes the meaning of the sentence - browsers will generally show as italics
            - Quotations - needs an opening and closing - blockquoted denotes quotation - for longer quotes that fill the whole paragraph - browsers tend to indent the contents
                - For shorter quotes, use the q element - needs an opening and closing - sits within a paragraph - browsers will generally put quotes around the the element
            - Abbreviations - needs an opening and closing - abbr denotes abbreviation and can go with acronym - needs an opening and closing
            - Citations - needs an opening and closing - cite denotes citation - browsers will generally show as italics
            - Definition - needs an opening and closing - dfn denotes definition - some browsers will show as italics
            - Author details - needs an opening and closing - address denotes author details - contact information for the author of the page
            - Changes to content
                - Insert - needs an opening and closing - ins denotes insert - is to show information that has been inserted into a document - browsers usually display content as underlined - use with del
                - Delete - needs an opening and closing - del denotes delete - is to show information that has been deleted - browsers usually display content with a line through it - use with ins
                - Strikethrough - needs an openng and closing - s denotes strikethrough - shows something that is no longer relevant or accurate, but not to be removed/deleted - browsers usually display content with a line through center
         
- ### Introducing CSS (pp.226-245)
    - Consider that there is a box around every HTML element and that CSS allows you to create rules that control the way that each individual box (and the contents of that box)  is presented.
        - body - creates the first box
            - h1/h2/p/i/a - create their own boxes within in
            - Using CSS you can add a border around any of the boxes, specify its width and height or add a background color.  You can also control text within the box - color, font, size, etc.
                - font-family lets you pick font
                - color lets you pick color
        - Selectors
            - Universal selector - * () - targets all elements on the page
            - Type selector - h1, h2, h3, etc. () - targets those specific elements
            - Class selector - .note () - targets anything whose class value is note.  p.note () - targets on -p- elements whose class attribute has a value of note
            - ID selector - #introduction () - targets the element whose id attribute has a value of introduction
            - Child selector - li>a () - targets any -a- elements that are children of an -li- element (bot not other -a- elements on the page)
            -  Descendent selector -  p a () - targets any -a- elements  that sit inside a -p- element, even if there are other elements nested between them
            - Adjacent Sibling selector -  h1 + p () - Targets the firsr -p- element after any -h1- element (but not other -p- elements)
            - General Sibling selector - h1~p () - If you had two -p- elements that are siblings of an -h1- element, this rule would apply to both
        - Rules Cascade
            - Last rule - if all things are the same level, will take precedence
            - Specificity - if one is more specific, then it will take precendence of the general style
            - Important - you can add !important after any property value to indicate that it should be considered more improtant that other rules that apply to the same element
            - Inheritance - child elements inherit styels/rules from parent elements - font family is an example - use .page for it to show up with all elements
            - Not Interited - background color for example is not inherited1

## JS

- ### Basic JavaScript Instructions (pp.53-84)
A script is a series of instructions that a computer can follow one-by-one.  Each individual instruction or step is known as a statement.  Statements should end with a semicolon.
    - 

- ### Decisions and Loops  (pp.145-162)
    - []