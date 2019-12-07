A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement!
Statements end with a semicolon.

Of the following example:

    var today = new Date();
    var hourNow = today.getHours();
    var greeting;
    
    if (hourNow > 18) {
      greeting = 'Good evening!';
    } else if (hourNow > 12) {
      greeting = 'Good afternoon!;
    } else if (hourNow > 0) {
      greeting = 'Good morning!';
    } else {
      greeting = 'Welcome!';
    }
    document.write(greeting);

SINGLE LINE COMMENTS:
// each line ending in a ';' is a statement.
// each cluster starting and ending with '{}' is a code block.
// each line starting with 'if', 'else if', or 'else' is code that dictate which code is appropriate for running.

MULTI-LINE COMMENTS:
/* NOTE
      JavaScript is also casesensitive so 'hourNow', 'HourNow', and 'HOURNOW' all mean different things! */
      
-------------------------------------------
A variable allows temporary data to be stored within a script. However before a variable can be used it has to be declared first 
and this includes creating it by giving it a name!

E.g.  var quantity;     /* Here, 'var' specifies the variable keyword that is needed to specify a variable
                            and 'quantity' is the variable name or identifier. */
                        // A variable name is written in camelCase (first word lowcase, second word capitalised).
                        
A variable is assigned a value using '='.

E.g.  quantity = 3;     // Here, the '=' is the assignment operator. 3 is the variable value.
                        // If a variable is not giving a value it is classed as undefined.
                        // Given a value is assigned to the variable the effect this can now have over the script is named the scope.
                        
------------------------------------------
Chloe.
                        
