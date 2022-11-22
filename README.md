# subset-compiler
This repo has been created as part of the compiler construction class project. The Compiler has been developed upto the intermediate code generation phase.

#Compiling the Code#
```flex leaxanalyser.l```
```bison -d parser.y```
````gcc -c lex.yy.c parser.tab.c```
  ```gcc -o com.out lex.yy.o parser.tab.o ```
