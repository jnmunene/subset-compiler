# MINI COMPILER USING FLEX & BISON
This repository has been created as a part of the compiler assignment . The compiler developed is upto the intermediate code generation phase.

# Compiling the Code

  ```flex lexanalyser.l```
  ```bison -d parser.y```
  ```gcc -c lex.yy.c parser.tab.c```
  ```gcc -o com.out lex.yy.o parser.tab.o```
  
The 3rd command produces a warning which can be ignored .

# Running the Compiler

The above sequence of commands produces an executable com.out which is our compiler . You can feed in the program to be compiled after typing ```./com.out```

followed by the input program . Type exit ; to escape from the process The intermediate code will be available in a file named output.txt .

Alternatively you can write a program in a file and put it in the same directory and you canb compile it by using the redirection operator '<' Suppose the filename is program.txt

      ./com.out < program.txt
Dont Forget to put exit; at the end of the program to terminate compilations.

Intermediate Code will be available in output.txt

# Sample programs with its outputs
![sample output](screenshots/Screenshot%20from%202022-11-22%2013-59-16.png)
# Documentation
The explanation for code portions are present in the comments in code . If you have difficulty raise an issue .

# Contribute
If you feel any changes to be made feel free to issue a pull request . The code performs poorly in memory optimisation for generating code


