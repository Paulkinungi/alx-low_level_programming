a new dir for alx 0x09-static_libraries project

steps for the project tasks
1.create dir and add README.md
2.create main.h file
3.create all '.c' files included
4.convert all .c files to object files using (gcc -c *.c)
5.create the libmy.a library using [ar rcs libmy.a]
copy all .o files to the library libmy.a using  the code(ar rcs libmy.a *.0)
run the code (ar -t libmy.a ) to confirm all.o files are in the library
run the second code to confirm by comparing the displayed codes


task_2
-create "create_static_lib.sh" file
-enter this code into the file and save   #!/bin/bash
gcc -Wall -pedantic -Werror -Wextra -c *.c
ar -rc liball.a *.o
ranlib liball.a 

-make the file executable using :
"chmod u+x create_static_lib.sh"
-run the file using the function:
"./create_static_lib.sh" >> it causes the file liball.a to appear
-confirm liball.a is presennt using:
"ls *.a"

git add .
git commit -m "message"
git push