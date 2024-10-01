# Libft 
## This custom library consists of 49 functions

Libft consists of custom recreations of many of the most used C standard functions and several utility functions for linked lists. The use of libraries and archives of executables is one of the most fundamental skills in Computer Programming.

### Archive Files

The Makefile used the  GNU ```ar``` programs to create an archive. The archive file has an .a file extention. This archive is used as a library holding many subroutines which you can then use in any C program. 

To use this library in C program you must compile the .a file with the C program. 

```cc hello_world.c libft.a``` 

### Header Files

Additionally, the libft.h file must be present. All files in your program that use a libft.a function must include a ```#include "libft.h"``` statement at the top of that file. The actual libft.h file must be in the directory in which the program is being executed. 

### Linking

Furthermore, you might decide to move your .h and/or .a file to another directory. In that case, you would include the pathway in the include statement. Ex: ```#include "include/libft.h"```. You also have to include an include flag in your command line. ```cc hello_world.c libft.a -I./include```
