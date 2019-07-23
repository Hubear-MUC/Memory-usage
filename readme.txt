Memory Usage 2.3
----------------

The program just needs to be invoked.

The program makes use of system memory by defining an integer- variable and
assigning it with the value 21.

If the program is run with a debugger, at line 3 a breakpoint can be set to
prevent the program from exiting, then the content of variable a can be
regarded.

In case a debugger should be used the program should be compiled like this:

  g++ -g -o memusage code.cpp

The invoking was done with

  gdb memusage

in case gdb is used as debugger.

The option  -g  is important because this causes the compiler to include
debug information into the binary file, which is needed by a debugger in case
you want to use one.

The content can be regarded with setting a breakpoint at line 3:

  b 3

starting the program with

  run

and finally when the program stopped at the breakpoint regard the variable
content with

  p a

The command

  cont

for "continue" continues with the program execution so it finally exits.

With

  q

GDB itself can be exited.

For the usage of other debuggers please refer to the documentation.



Changes:
--------

Placed the closing curly bracket in a new line to make the code readable
more clearly and to make it possible to set a breakpoint after assigning
the used memory with content.

