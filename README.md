### Akdeniz University
### Department of Computer Engineering
### Lexical & Syntax Analyzer/Parser with Yacc

### Programming Language Collective
### Group Members: Burak ERCIKTI, Muhammet Mazlum ORHAN, Egemen GUNDUZ

### Course: Programming Languages (CSE 334)

### Abstract: This interpreter is a new programming language that is a functional programming language. The programming language is called Collective. Our goal is to bring together different functions in all programming languages. It is a language that beginners can easily program. Simple programming language functions such as comments, conditional statements such as if-else, loops such as for, while, do-while, ability to write functions, and exception handling can be made with Expression-based execution. It has readability and ease of writability. Its syntax is similar to object-oriented programming languages ​​such as Java, c#. Programs are written here come with the .col extension. There are 2 types of expressions. The first are expressions such as integers that do not need a body to be executed. The second is conditional statements that have a body to execute. As shown above, in col is the data type and text type. The data type is an integer, float, and boolean, while the text type uses String and char. Code blocks are separated by curly braces. As in most programming languages, curly braces must be used for the body. This software can read the language through the input file. The print function is used to print expressions. Finally, the input file can be shown here. col also allows you to print the text you want to the file. There are two types of comments. “#” is used for only one line and “##” is used for multi-line. You can run the program using the instructions in the "run.ssh" file. For this, you can run the commands “yacc -d col.y” and “lex col.l” in the terminal. You can use the command “gcc -g lex.yy.c y.tab.c -o col” to delete col. While typing in the terminal If you make a mistake, the program will stop and show you where the error is. You can write a comment in the compiler.

### Syntax
::= 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9

::= |

::= .

::= | | |

::= =

::= if () | if () | else

::= while ()

::= { }

::= |

Explanations about the language
Takes a file with extension .col

Has if, else conditions

Has for and while loop

Special tokens(&|) are used for and, or statements

Blocks are separated with curly brackets

Aligning is unimportant

You can run your program by running the makefile and giving it to myprog as input:

make ./col < exampleInput.col
