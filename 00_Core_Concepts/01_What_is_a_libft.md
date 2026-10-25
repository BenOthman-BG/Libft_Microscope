# what is a libft ?
a libft its a costum static library in C that has a libc functions + additional functions + linked list functions .
# what is a library ?
a library its helper in code that provide some fonctionalities that make devloppers not recode them everytime .
# what is a libc ?
a libc its the standard library in C 
# static Vs dynamic (library)
## static library :
    its a group of functions that are in object file form (assemblage step)
    archived in a file *.a , we use it in linker step (program + library)
    and after we generate a program executable that hase all importance need 
    after that you can run the program in any envirment you need .
## dyncamic library :
    its a group of functions too that are .bin form executable file (after linker)
    its sotred in like /user/lib , we can used just to put the path of the lib in our program in linker step 
    and that provide that in the execution we go and load the lib (if it not load) and bring what we want 
    the library can be use for multiple programs in same time 
    you hade not change all the program if there any change in the library (because there independant)
    you can jsut change *.so file
    you can't run the programe in a envirment that has not the *so file 
# GNU Vs BSD
all thme based on UNIX
## BSD :
    Berkeley Software Distribution , we found it like in macOS
    that has bsd libc
    has gcc
## GNU :
    GNU's Not Unix , we found it like in linux desto
    has glibc library 
## the difference between them :
    in the problem of undefinde behavior we have some difference in how they handle it , in some time we found let crash in some cases but in other we found it handle ..., like in malloc(0) : in GNU libc we return a pointer to let them free , istead of in BSD return null.
    has clang


