Memory Usage 3.1
----------------

The program just needs to be invoked.
However for regarding the array contents the program has to be run using
a debugger.

The program creates an array of 9 fields for integer- numbers.

The first one of them gets assigned with the value 9.

Of course also the remaining 8 positions in the array can be assigned with
numbers manually by using a debugger.

If your debugger allows assigning variables with contents via using 
expressions like

  a[3]=a[1]+a[2]

The program also can be used as a storage for numbers for calculations as 
long as it runs.

In this case however the calculations are not done by the program itself,
the program just saves the values.

If the program is run with a debugger, at line 3 a breakpoint can be set to
prevent the program from exiting, then the content of variable a can be
regarded.

  1  int a[9];
  2
  3  main()
  4  {
  5  a[1]=9;
  6  }

Set a breakpoint at line 3 to prevent the program from finishing immediately

Run the program and step over line 4 to initialize the second place in the
array with 9. 

Then check the contents of the array fields.

Assign values to the array fields if you like

To finish the program just continue to the end, so the program runs to its
last line and finishes then.

Please refer to the manual of your debugger to learn how to operate it.



Changes:
--------

Version 3.1

Separation of the definition from the working code to make the code readable
more clearly.


Version 3.0:

Creation of an array, not just one variable. Thus first "real" memory usage
in a bigger amount.


Version 2.3:

Placed the closing curly bracket in a new line to make the code readable
more clearly and to make it possible to set a breakpoint after assigning
the used memory with content.

