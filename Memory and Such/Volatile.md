It is separated in regions:
volatile memory {
	[[Stack]]
	[[Heap]]
	[[Static]]
}

Each region has a different purpose:
1. [[Stack]] -> Static sized variables
2. [[Heap]] -> Dynamic sized variables
3. [[Static]] -> The programs binary