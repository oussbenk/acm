# Problem A (Say Hello from text file)
:page_facing_up: **Input file name** : A.txt

## :green_book: Problem description ##
We want to print a welcome message to a person name which is read from an input text file. _It is a piece of cake !_

### Example ###
**Input** (A.txt)
```
Toto
```

**Output**
```
Hello Toto!
```

## :sos: Hints ##
Consider completing the following code snippet written in C language. The source file should be named "A.c".
```C
#include <stdio.h>

int main(){

	char nom[20];
	FILE *fp; // variable to handle a file
  
	// "fopen" is used to open a file; the second parameter is the mode (ie. "r" stands for read only)
	fp=fopen("A.txt","r");
  
	// "fscanf" is used like "scanf" (expect adding the first parameter of the file variable pointer)
	fscanf(fp,"%s",nom);
  
	// TODO add your code here ...
  	
	fclose(fp); // recomanded to close the file pointer at the end
	return 0;
}
```

### :no_entry: Before submitting your code through PC^2 ###

- It should **compile**.
- It should print the **wanted result** on your own machine; **if not it will never do it on the server**.
- Respect the **naming convention** of input and code files ("A.txt" and "A.c" in this case).
- Only the code source is required for submission (since the server tests your code on another input dataset).
