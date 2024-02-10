# The C Programming Language

## CHAPTER 1: A TUTORIAL INTRODUCTION

### Exercise 1.1
In traditional C, the program to print **"Hello, World"** is:

```C
int main()
{
    printf("hello, world\n");
}
```
Instead in the modern minimal version the code is:

```C
#include <stdio.h>
int main() {
    printf("hello, world\n");
}
```

For run this program depends on the system you are using. In **UNIX** we need create the source program in *.c* file, such as *hello.c*, the compile it with the command:

```bash
cc hello.c
```
> [!NOTE]
> On modern systems, we use the **gcc** compiler.

If once compiled nothing error is return, we will find onother  **ELF** type file called *a.out*. To run this file in UNIX type:

```bash
.\hello.c
```
and will produce

```text
hello, world
```



