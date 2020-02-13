## Reading for 07

### Duckett HTML book:  Chapter 6: “Tables” (pp.126-145)

- The  -table- element is used to add tables to a web page.
    - A table is drawn out row by row. Each row is created with the -tr- element.
        - Inside each row there are a number of cells represented by the -td- element (or -th- if it is a header).
            - You can make cells of a table span more than one row or column using the rowspan and colspan attributes. For long tables you can split the table into a  -thead-, -tbody-, and -tfoot-.

### Duckett JS Book:  Chapter 3: “Functions, Methods, and Objects” (pp.106-144)

- Functions allow you to group a set of related statements together that represent a single task. 
    - Functions require a keyword and function name, followed by () and {.  The rest of the function is to provide a process to run.
    - A function is called by it's function name
- Functions can take parameters (informatiorJ required to do their job) and may return a value. 
    - Parameters are put in the () right after the function name
    - Parameter information needs to be detailed on a different line(s)
    - IIFE - Immediately Invoked Function Expressions - Are executed immediately as the funcion comes across it.  It is distinguished by the open paren before the word function, () after the function components, and then the closed paren, which are all after the closing curly brace.
- An object is a series of variables and functions that represent something from the world around you. 
    - To access an object, you use the object name.property/method name followed by a ;.  Ex. hotel.name.
- In an object, variables are known as properties of the object; functions are known as methods of the object. 
    - To add a property value, just add an = and the name in single quotes.  Ex. hotel.name = 'Park';
    - You can create many objects by using a constructor 
    - To create, you would use the word new and then the contructor name thats first letter is capitalized.  Ex new Location
- Web browsers implement objects that represent both the browser window and the document loaded into the browser window. 
- JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts. 
- Arrays and objects can be used to create complex data sets (and both can contain the other). 

### Article:  Domain Modeling

1. The new keyword instantiates (i.e. creates) an object.
2. The constructor function initializes properties inside that object using the this variable.
3. The object is stored in a variable for later use.

Here's some tips to follow when building your own domain models.

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
3. Model its behaviors with small methods that focus on doing one job well.
4. Create instances using the new keyword followed by a call to a constructor function.
5. Store the newly created object in a variable so you can access its properties and methods from outside.
6. Use the this variable within methods so you can access the object's properties and methods from inside.


