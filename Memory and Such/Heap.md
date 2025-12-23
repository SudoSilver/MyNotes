This stores:
1. Values that are global
2. Values that are shared between threads
3. Large Values
4. Stuff with sizes unknown at compile time

Properties:
	-> The only limit is physical RAM
	-> Stores stuff with unknown size
	-> Lifetimes are handled by the programmer (kinda)
	-> Manual cleanup

All threads have the same heap.

What do i mean with manual cleanup and lifetimes handled by the programmer?
	The program choses when something goes in and out of the heap BUT we borrow the space where it is stored from the allocator.