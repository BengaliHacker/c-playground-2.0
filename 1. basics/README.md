## 📋Exercise 1: Hello World

**Question**: Write a C program to print "Hello World".

**Solution**: [View Code](hello_world.c)

```c
#include <stdio.h>
int main() {
    printf("Hello World");
    return 0;
}
```
### OUTPUT

```
hello world
```

## 📋Exercise 2: Escape Sequences

**Question**: Write a C program to print text on multiple lines using the newline escape sequence (\n).

**Solution**: [View Code](escape_sequences.c)

```c
# include <stdio.h>
int main() {
    printf("Hi\n");
    printf("I am learning C programming.\n");
    printf("It's fun!\n");
    return 0;
}
```
### OUTPUT

```
Hi
I am learning C programming.
It's fun!
```

## 📋Exercise 3: Comments and Formatting

**Question**: Write a C program that demonstrates the use of single-line and multi-line comments.

**Solution**: [View Code](comments_formatting.c)

```c
#include <stdio.h>
int main() {
     // This is a single-line comment
     printf("Learning C is fun!\n");

     /*
      This is a multi-line comment.
      You can write explanations here.
     */
      printf("Comments make code easy to understand.\n");
      return 0;
}
```
### OUTPUT

```
Learning C is fun!
Comments make code easy to understand.
```

## 📋Exercise 4: Variables

**Question**: Write a C program to declare and print different types of variables: integer, float, and character.

**Solution**: [View Code](variables.c)

```c
#include <stdio.h>

int main() {
    int age = 20;          // Integer variable
    float height = 5.9;    // Floating point variable
    char grade = 'A';      // Character variable
  
    printf("Age: %d\n", age);
    printf("Height: %.1f\n", height);
    printf("Grade: %c\n", grade);

    return 0;
}
```
### OUTPUT

```
Age: 20
Height: 5.9
Grade: A
```
