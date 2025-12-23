A pointer is just the address of something that lives in the memory as a variable it can be either on the [[Heap]] or the [[Stack]]. A pointer can be referenced or dereferenced using C is the easiest and most common way to do so.

----- 
Referencing a pointer:
	We reference a variables memory address through a pointer when we want to figure out WHERE in the memory it is. Referencing the variables memory address is done as such

```c
#include <stdio.h>

int main() {
	int x = 10;
	int *p = &x;
	printf("x is located at: %p", (void *)p);	
	return 0;
}
```

The code above first declares x in our [[Stack]] as an integer then we create a pointer in this case p which points to the address of x in the [[Stack]] and then we print it. Referencing a pointer is typically safe. The code above will return something along the lines of `0x7ffe5367e044`

---
Dereferencing a pointer:
	We dereference a variables memory address through a pointer when we want to access a variables value through its memory address so for example

```c
#include <stdio.h>

int main() {
	int x = 10;
	int *p = &x;
	printf("x = %d", *p);
	return 0;
}
```

The code above declares the x in our [[Stack]] as an integer then we create a pointer (p) which points to the memory address of x in the [[Stack]] and then prints its value. The above code will ALWAYS print `10`.