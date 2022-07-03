gcc -E $CFILE -o c: a script that runs a C file through the preprocessor and save the result into another file. The C file name will be saved in the variable $CFILE. The output should be saved in the file c

gcc $CFILE -c: compiles a C file but does not link.The C file name will be saved in the variable $CFILE. The output file should be named the same as the C file, but with the extension .o instead of .c. /n
gcc $CFILE -o cisfun: compiles a C file and creates an executable named cisfun. The C file name will be saved in the variable $CFILE
gcc -S $CFILE: generates the assembly code of a C code and save it in an output file. The C file name will be saved in the variable $CFILE. The output file should be named the same as the C file, but with the extension .s instead of .c.
#include <stdio.h>

/**
 * main - Entry point
 *
 * Return: Always 0 (Success)
 */

int main(void)
{
puts("\"Programming is like building a multilingual puzzle");
return (0);
}
(Prints exactly "Programming is like building a multilingual puzzle, followed by a new line)
#include <stdio.h>

/**
 * main - Entry point
 *
 * Return: Always 0 (Success)
 */
int main(void)
{
printf("with proper grammar, but the outcome is a piece of art,\n");
return (0);
}
A C program that prints **exactly with proper grammar, but the outcome is a piece of art**, followed by a new line.
Use the function printf.
Your program should return 0
/**
>  * main - Entry point
>  *
>  * Return: Always 0 (Success)
>  */
>
> int main(void)
> {
> char acharacter;
> int ainteger;
> long along;
> long long alonglong;
> float afloat;
>
> printf("Size of a char: %lu byte(s)\n", sizeof(acharacter));
> printf("Size of an int: %lu byte(s)\n", sizeof(ainteger));
> printf("Size of a long int: %lu byte(s)\n", sizeof(along));
> printf("Size of a long long int: %lu byte(s)\n", sizeof(alonglong));
> printf("Size of a float: %lu byte(s)\n", sizeof(afloat));
>
> return (0);
prints the size of various types on the computer it is compiled and run on. You should produce the exact same output as in the example. Your program should return 0. 
