## C and C++
<br>The minimal C/C++ program is the classic “Hello, World!”, let’s start with C, see below image<br>
<br>
<img src="/images/hello-world.c.png" alt="Hello World C"><br>
<br>
## Copy the code

```C
#include <stdio.h>
    main()
    {
      printf("hello, world\n");
    }
```
<br>

## Hello World code in “C” language

<br> If you use Atom as your preferred text editor and save the file as **“hello.c”** then Atom will<br>
automatically recognize the programming language, see image below.<br>
<br>
<p align="center">
<img src="/images/hello-world.c-code.png" align="center"><br>
<p>
<br>
    
## Compiling Hello world code
   
<br> We’re going to use the “<b>gcc</b>” compiler to compile our code, the CLI command to be used is the following.
<br>
    
```C
gcc hello.c
```
<br>
<p align="center">
<img src="/images/hello-world.c-compile-code-using-gcc.png" align="center"><br>
<p>
    
## Output file

Using the “gcc” compiler without any argument will leave the output file without a name,<br>
the compiler will create a new file called “a.out”, see image below.

```C
ls -la a.out
```





