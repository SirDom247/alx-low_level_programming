# Memory allocations in C
# `0x0C. C - More malloc, free`
Task 0. A function that allocates memory using malloc.\
	
	Prototype: void *malloc_checked(unsigned int b);
	File: 0-malloc_checked.c
	Returns a pointer to the allocated memory
	If malloc fails, the malloc_checked function should cause normal process termination with a status value of 98


Task 1. A function that concatenates two strings.\
	
	Prototype: char *string_nconcat(char *s1, char *s2, unsigned int n);
	File: 1-string_nconcat.c
	The returned pointer points to a newly allocated space in memory, which contains s1, followed by the first n bytes of s2, and null terminated
	If the function fails, it should return NULL
	If n is greater or equal to the length of s2 then use the entire string s2
	if NULL is passed, treat it as an empty string


Task 2. A function that allocates memory for an array, using malloc.\
	
	Prototype: void *_calloc(unsigned int nmemb, unsigned int size);
	File: 2-calloc.c
	The _calloc function allocates memory for an array of nmemb elements of size bytes each and returns a pointer to the allocated memory.
	The memory is set to zero
	If nmemb or size is 0, then _calloc returns NULL
	If malloc fails, then _calloc returns NULL

Task 3. A function that creates an array of integers.\

	Prototype: int *array_range(int min, int max);
	File: 3-array_range.c
	The array created should contain all the values from min (included) to max (included), ordered from min to max
	Return: the pointer to the newly created array
	If min > max, return NULL
	If malloc fails, return NULL

Task 4. A function that reallocates a memory block using malloc and free\


Task 5. A program that multiplies two positive numbers.\
#end_of_README
