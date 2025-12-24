When a program tries to access memory it does not own the operating systems way of telling it no is by sending a "SIGSEGV" signal to it which causes the infamous error known as SEGFAULT or segmentation fault.

```c
#include <stdio.h>

int main() {
	int *p = NULL;
	
	printf("p: %d", *p);
	
	return 0;
}
```
the above block of code for example causes a SEGFAULT as we attempt to dereference a NULL [[Pointer]] 