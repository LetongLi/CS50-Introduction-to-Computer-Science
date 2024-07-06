# Basic commands (in the Terminal window)
## code hello.c
Open or create a new file.
All lowercase and no space.
## make hello
Act as a compiler to convert source code to machine code.
## ./hello
A command to run the code.


# Basic commands
## #include<stdio.h>
Header file/library. 
## int main(void)
## printf
### printf("helloworld/n");
In C language, the new line is a special character that is used to move the cursor at the start of the next line. It is represented as the '\n' escape sequence and it can be used in string literals just like any other character. 
### printf("hello, %s/n", answer);
Place holder for strings.
## if else
> if()  
> {}  
> else if()  
> {}  
> else  
> {}

## Loops
### while
> int counter = n;  
> while(counter>0)  
> {  
>    ...  
>    counter = counter - 1;  /n--/n-=1
> }
### while (true)
### do while
> do  
> {}  
> while ();  
### for
> for(int i= 0; i < 3; i++)  
> {}/...;  
### void
No return value:
> void name(void); //before main
> void name(void)  
> {} 

Return value
> int name(void); //before main  
> int name(void)  
> {}  
## Others
Or: ||  
And: &&

# Data Type
bool  
char: one character.  
double  
float  
int: 32 bits  
long: 64 bits  
string: 0 to multiple characters.
constant

# Operating systems
## Linux
## GUI
### commands
cd: change directory  
cp: copy  
ls: list the elements in the folder  
mkdir: make directory  
mv: rename  
rm: remove the file(y/n)  
rmdir: remove directory  


# Memory / RAM (Random-access memory)
## integer overflow
## floating-point imprecision
Can't represent the infinite number using finite memory.

# Tips
1. define functions,  
2. define other data.
3. Scope problems.
4. Use comments.
5. Truncation problems: typecasting.  
   %.6f\n: 6 significant digits after the decimal point.
   

# Useful links
## Manual pages
manual.cs50.io
