# EX-NO-6-Pseudo-Random-Number

## NAME:Arivazhagan G R
## REG NO:212223040020


# AIM: 

Implementation of Pseudorandom Number Generation Using Standard library


# ALGORITHM:

1) Start the program and import the required libraries.
2) Seed the random number generator using the current time(i.e)
rand(time(0));
3) Get the number of randon number to generate.
4) Pass the value for number of iterations and print the numbers.
5) End the program.


# PROGRAM:
```
 #include <stdio.h>
 #include <stdlib.h>
 #include <time.h>
 int main() {
 int i, n;
 srand(time(0));
 printf("Enter how many pseudorandom numbers you want to generate: ");
 scanf("%d", &n);
 printf("Generating %d pseudorandom numbers between 0 and 99:\n", n);
 for (i = 0; i < n; i++) {
 int randomNumber = rand() % 100;
 printf("%d ", randomNumber);
 }
 printf("\n");
 return 0;
 }
```


# OUTPUT:

![Uploading Screenshot 2025-10-30 at 10.29.33 PM.png…]()



# RESULT:
The implementation of Pseudorandom Number Generation using Standard library is successful.
