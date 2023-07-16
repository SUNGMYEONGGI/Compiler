# **💻Compiler**

A small example of a calculator written with flex / bison.
Compile using the `Makefile` 

    $ make

or manually on Linux, follow this steps:

    $ bison -d calc.y
    $ flex calc.l
    $ gcc calc.tab.c lex.yy.c -o calc -lm
    $ calc

<br>

# ✔️나만의 컴파일러 만들기
    "plus"          {return T_PLUS;}
    "minus"         {return T_MINUS;}
    "multiple"      {return T_MULTIPLY;}
    "divide"        {return T_DIVIDE;}
    "open"	        {return T_LEFT;}
    "close"         {return T_RIGHT;}
    "exit"	    	{return T_QUIT;}
    "quit"	    	{return T_QUIT;}
