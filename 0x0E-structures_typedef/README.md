# THIS IS A README FILE FOR 0x0E-structures_typedef PROJECT

File 0-dog.h is a header file containing a new type "struct dog" with tghe following elements with the following elements:
	name, type = char * 
	age, type = float
	owner, type = char *.


File 1-init_dog.c a function that initialize a variable of type struct dog, having the Prototype: 
	void init_dog(struct dog *d, char *name, float age, char *owner);.\


File 2-print_dog.c is a function that prints a struct dog with the prototype:
	void print_dog(struct dog *d);


File 3-dog.h is a function that defines a new type dog_t as a new name for the type struct dog.


File 4-new_dog.c is a function that creates a new dog using Prototype: 
	dog_t *new_dog(char *name, float age, char *owner);:
	

File 5-free_dog.c is a function that frees dog, with prototype:
	Prototype: void free_dog(dog_t *d);
