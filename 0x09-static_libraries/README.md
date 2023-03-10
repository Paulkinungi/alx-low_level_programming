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