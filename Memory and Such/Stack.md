This stores:
1. Function calls
2. Local variables

Properties:
	-> Size is ALWAYS known at compile time
	-> Has an upper limit
	-> if the limit is breached we have a `STACK OVERFLOW` 
	-> When we finish a function the ENTIRE function gets removed from the stack 
	-> Lifetime = Lifetime of its scope

Each thread has its own stack
