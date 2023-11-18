This is a library of 43 commonly used C functions from the standard libraries:
  <string.h>, <stdlib.h>, <ctype.h>,  <bsd/string.h>,
and several custom functions some using the 'write' function from the <unistd.n>. 
Nine of these functions are also used for the creation and maniputation of linked lists.
To link all the functions together there is also a header file.
And last, but not least a Makefile to easily compile and archive all of these files.

These files were created on a Ubuntu Linux Operating System. 

Instructions:

To use this file you can 'git clone' this repository in your terminal.
Enter the command: make
A 'libft.a' file will be made. 
You can then create a main.c (or call it whatever you like, as long as it as the file extension .c)
Make sure you include "libft.h" at the top of your main.c
You can now use all the libft custom library functions inside your program.
When you are ready to compile your main.c use the command: cc -Wall -Wextra -Werror -L. -lft main.c (include the flag -o if you want to name your executable)
Then when you are ready to execute you program use the command: ./a.out 

Makefile rules:
make re : will recompile the the libft.a file if you've made any changes to the .c files.
make clean: will remove the .o files
make fclean: will remove the .o files and remove the libft.a file
make bonus: will compile a libft.a file with just the nine linked list files. 
