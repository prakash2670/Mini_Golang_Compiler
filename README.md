# Basic-Golang-Compiler
Using lex and yacc it performs lexical analysis, syntactical analysis, semantical analysis and also intermediate code generation for simple codes.

To execute the program Run the following command

1. flex program.l

2. bison -d program.y ( Ignore the warnings)

3. gcc lex.yy.c program.tab.c

then we get a executable file

Run ./a.out

use the sample codes if needed.

References:

[Reference 1](https://stackoverflow.com/questions/58663970/yacc-code-reads-both-if-and-else-statemen)


[Reference 2](https://www.google.com/search?q=yacc+program+for+function+declaration&ei=SjERYqiFD8bS-Qb-0aOoBA&oq=yacc+program+for+function+declarat&gs_lcp=Cgdnd3Mtd2l6EAMYADIFCAAQgAQ6BAgAEEM6BQgAEJECOhEILhCABBCxAxCDARDHARDRAzoLCAAQgAQQsQMQgwE6EAguELEDEIMBEMcBENEDEEM6CggAELEDEIMBEEM6CwguEIAEELEDEIMBOggIABCABBCxAzoECAAQDToGCAAQFhAeSgQIQRgASgQIRhgAUIsGWM5UYJZkaAJwAHgDgAHLCYgB21CSAREwLjEwLjE0LjguMC4xLjEuMZgBAKABAbABAMABAQ&sclient=gws-wiz)
