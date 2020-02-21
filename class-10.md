## Reading for 10

### From the Duckett JS book:  JavaScript book, Ch. 10, “Error Handling & Debugging”


- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
    - The JavaScript interpreter processes one line of code at a time.  When a statement needs data from another function, it stacks (or piles) the new function on top of the curren task.
    - Each time a sript enters a new execution contest, there are two phases of activity:
        1. Prepare
            - The new scope is created
            - Variables, functions, and arguments are created
            - The value of the this keyword is determined
        2. Execute
            - Now it can assign values to variables
            - Reference functions and run their code
            - Execute statements
    - Understanding that these two phases happen helps with understanding a concept called <i> hoisting </<i>.
- Debugging is the process of finding errors. It involves a process of deduction.
    - Page 460 - 461 shows common errors and what they mean
    - How to deal with errors:
        1. Debug the script to fix errors
        2. Handle Errors Gracefully - You can handle errors gracefully using try, catch, throw, and f i na 1 ly statements
    - Debugging is about deduction: eliminating potential causes of an error.
- The console helps narrow down the area in which the error is located, so you can try to find the exact error.
- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements.  Use them to give your users helpful feedback. 