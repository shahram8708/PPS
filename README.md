### Computer Ka Introduction

Computer ek electronic device hai jo data ko process karta hai aur useful information banata hai. Yeh data ko input ke roop mein leta hai, usse process karta hai, aur output deta hai.

### Basic Block Diagram aur Functions of Various Components

1. **Input Unit**:
   - **Function**: Data ko computer mein input karta hai.
   - **Examples**: Keyboard, Mouse.

2. **Central Processing Unit (CPU)**:
   - **Function**: Data ko process karta hai aur instructions ko execute karta hai.
   - **Components**:
     - **Control Unit (CU)**: Instructions ko control karta hai.
     - **Arithmetic Logic Unit (ALU)**: Calculations aur logical operations karta hai.
     - **Registers**: Temporary storage for quick data access.

3. **Memory Unit**:
   - **Function**: Data aur instructions ko store karta hai.
   - **Types**:
     - **Primary Memory**: RAM, ROM.
     - **Secondary Memory**: Hard Disk, SSD.

4. **Output Unit**:
   - **Function**: Processed data ko output karta hai.
   - **Examples**: Monitor, Printer.

5. **Storage Unit**:
   - **Function**: Data ko long-term storage ke liye store karta hai.
   - **Examples**: Hard Disk, USB Drives.

### Concepts of Hardware and Software

- **Hardware**: Physical components of a computer (e.g., CPU, RAM, Hard Disk).
- **Software**: Programs and operating systems that run on hardware.

### Types of Software

1. **System Software**: 
   - **Function**: Computer hardware aur application software ko manage karta hai.
   - **Examples**: Operating Systems (Windows, Linux), Device Drivers.

2. **Application Software**:
   - **Function**: Specific tasks ko perform karta hai.
   - **Examples**: Microsoft Word, Adobe Photoshop.

### Compiler and Interpreter

- **Compiler**:
  - **Function**: High-level code ko ek saath machine code mein convert karta hai.
  - **Examples**: C Compiler, Java Compiler.

- **Interpreter**:
  - **Function**: High-level code ko line-by-line execute karta hai.
  - **Examples**: Python Interpreter, JavaScript Engine.

### Concepts of Machine Level, Assembly Level, and High-Level Programming

1. **Machine Level Programming**:
   - **Language**: Binary (0s and 1s).
   - **Example**: Machine code.

2. **Assembly Level Programming**:
   - **Language**: Mnemonics and symbols.
   - **Example**: Assembly language.

3. **High-Level Programming**:
   - **Language**: Human-readable.
   - **Examples**: C, Python, Java.

### Flowcharts and Algorithms

- **Flowchart**:
  - **Definition**: Diagrammatic representation of an algorithm.
  - **Symbols**: 
    - **Oval**: Start/End.
    - **Rectangle**: Process.
    - **Diamond**: Decision.
    - **Arrow**: Flow direction.

- **Algorithm**:
  - **Definition**: Step-by-step procedure to solve a problem.
  - **Example**: Algorithm to add two numbers:
    1. Start.
    2. Input two numbers.
    3. Add the numbers.
    4. Output the result.
    5. End.

### C Language Ki Features

1. **Simple and Efficient**: C language asan aur efficient hai, aur system-level programming ke liye use hoti hai.
2. **Structured Language**: Yeh structured programming ko support karti hai, jo code ko organize aur maintain karne mein madad karta hai.
3. **Rich Library**: C me bahut saari in-built functions aur libraries hain.
4. **Pointer**: C pointer concept ko support karta hai, jo memory ko directly manipulate karne mein madad karta hai.
5. **Portability**: C code ko aasani se alag-alag platforms par compile aur run kiya ja sakta hai.
6. **Recursion**: C me functions apne aapko call kar sakte hain (recursion).

### Structure of a C Program

```c
#include <stdio.h> // Header File

// Main Function
int main() {
    // Code
    printf("Hello, World!");
    return 0;
}
```

1. **Header Files**: `#include <stdio.h>` - Standard input/output functions ke liye.
2. **Main Function**: `int main()` - Program execution yahin se start hota hai.
3. **Statements**: `printf("Hello, World!");` - Output statement.
4. **Return Statement**: `return 0;` - Program ko successful execution ke baad terminate karta hai.

### Comments

- **Single Line Comment**: `// This is a single line comment`
- **Multi Line Comment**: `/* This is a multi line comment */`

### Header Files

- Header files standard libraries ko include karte hain.
- Example: `#include <stdio.h>` - Standard Input/Output functions.

### Data Types

1. **Basic Data Types**: 
   - `int`: Integers (e.g., 10, 20)
   - `float`: Floating-point numbers (e.g., 10.5, 20.7)
   - `char`: Characters (e.g., 'a', 'b')
   - `double`: Double-precision floating-point numbers

2. **Derived Data Types**:
   - Arrays, Pointers, Structures, Unions

### Constants and Variables

- **Constants**: Values jo program execution ke dauran change nahi hote.
  - Example: `const int pi = 3.14;`

- **Variables**: Values jo program execution ke dauran change ho sakte hain.
  - Example: `int age = 25;`

### Operators

1. **Arithmetic Operators**: `+`, `-`, `*`, `/`, `%`
2. **Relational Operators**: `==`, `!=`, `>`, `<`, `>=`, `<=`
3. **Logical Operators**: `&&`, `||`, `!`
4. **Assignment Operators**: `=`, `+=`, `-=`, `*=`, `/=`
5. **Bitwise Operators**: `&`, `|`, `^`, `~`, `<<`, `>>`

### Expressions

- Combination of variables, constants, and operators to produce a value.
  - Example: `a + b * c`

### Evaluation of Expressions

- Expressions ko evaluate karne ke liye precedence aur associativity ka use hota hai.
  - Example: `int result = 5 + 2 * 3;` // result is 11

### Type Conversion

1. **Implicit Type Conversion**: Automatically by compiler.
   - Example: `int a = 5; float b = a;` // a is converted to float

2. **Explicit Type Conversion (Casting)**: Manually by programmer.
   - Example: `float a = 5.5; int b = (int) a;` // a is converted to int

### Precedence and Associativity

- **Precedence**: Operators ki priority.
  - Example: `*` has higher precedence than `+`.

- **Associativity**: Operators ka evaluation direction (left to right or right to left).
  - Example: `*` and `/` are left-associative.

### I/O Functions

- **Input Function**: `scanf()`
  - Example: `scanf("%d", &num);` // num mein integer input store karta hai

- **Output Function**: `printf()`
  - Example: `printf("Hello, World!");` // Output "Hello, World!"
 
### Simple Statements

Simple statements woh statements hote hain jo ek single operation perform karte hain, jaise value assign karna, function call karna, etc.

Example:

```c
int a = 5; // Assignment statement
printf("Value of a is %d", a); // Function call statement
```

### Decision Making Statements

Decision making statements program ko conditions ke base par different paths par le jaate hain.

1. **if Statement**:

```c
if (condition) {
    // Code to be executed if condition is true
}
```

Example:

```c
if (a > 0) {
    printf("a is positive");
}
```

2. **if-else Statement**:

```c
if (condition) {
    // Code to be executed if condition is true
} else {
    // Code to be executed if condition is false
}
```

Example:

```c
if (a > 0) {
    printf("a is positive");
} else {
    printf("a is negative or zero");
}
```

3. **else-if Ladder**:

```c
if (condition1) {
    // Code to be executed if condition1 is true
} else if (condition2) {
    // Code to be executed if condition2 is true
} else {
    // Code to be executed if both conditions are false
}
```

Example:

```c
if (a > 0) {
    printf("a is positive");
} else if (a < 0) {
    printf("a is negative");
} else {
    printf("a is zero");
}
```

4. **switch Statement**:

```c
switch (expression) {
    case constant1:
        // Code to be executed if expression equals constant1
        break;
    case constant2:
        // Code to be executed if expression equals constant2
        break;
    default:
        // Code to be executed if expression doesn't match any constant
}
```

Example:

```c
switch (a) {
    case 1:
        printf("a is 1");
        break;
    case 2:
        printf("a is 2");
        break;
    default:
        printf("a is neither 1 nor 2");
}
```

### Looping Statements

Looping statements code ko repeatedly execute karte hain jab tak koi condition true hoti hai.

1. **while Loop**:

```c
while (condition) {
    // Code to be executed
}
```

Example:

```c
int i = 1;
while (i <= 5) {
    printf("%d\n", i);
    i++;
}
```

2. **do-while Loop**:

```c
do {
    // Code to be executed
} while (condition);
```

Example:

```c
int i = 1;
do {
    printf("%d\n", i);
    i++;
} while (i <= 5);
```

3. **for Loop**:

```c
for (initialization; condition; increment/decrement) {
    // Code to be executed
}
```

Example:

```c
for (int i = 1; i <= 5; i++) {
    printf("%d\n", i);
}
```

### Nesting of Control Structures

Control structures (if, for, while) ko ek dusre ke andar nest kar sakte hain.

Example:

```c
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= 2; j++) {
        printf("i = %d, j = %d\n", i, j);
    }
}
```

### break and continue Statements

1. **break**: Loop ya switch statement ko immediately terminate karta hai.

Example:

```c
for (int i = 1; i <= 5; i++) {
    if (i == 3) {
        break; // Loop terminates when i is 3
    }
    printf("%d\n", i);
}
```

2. **continue**: Current iteration ko skip karta hai aur next iteration start karta hai.

Example:

```c
for (int i = 1; i <= 5; i++) {
    if (i == 3) {
        continue; // Skips the rest of the code when i is 3
    }
    printf("%d\n", i);
}
```

### goto Statement

goto statement ek specific label par jump karta hai.

Example:

```c
int i = 1;
label: // Label
    printf("%d\n", i);
    i++;
    if (i <= 5) {
        goto label; // Jump to label
    }
```

### Concepts of Array

Array ek collection hota hai similar type of elements ka jo contiguous memory locations mein store hote hain. Arrays fixed-size data structures hote hain, yani unka size program execution ke dauran change nahi hota.

### One-Dimensional Array

1. **Declaration**:

```c
data_type array_name[array_size];
```

Example:

```c
int numbers[5];
```

2. **Initialization**:

```c
array_name[index] = value;
```

Example:

```c
numbers[0] = 10;
numbers[1] = 20;
numbers[2] = 30;
numbers[3] = 40;
numbers[4] = 50;
```

- Or initialize at the time of declaration:

```c
int numbers[5] = {10, 20, 30, 40, 50};
```

### Two-Dimensional Array

1. **Declaration**:

```c
data_type array_name[rows][columns];
```

Example:

```c
int matrix[3][3];
```

2. **Initialization**:

```c
array_name[row_index][column_index] = value;
```

Example:

```c
matrix[0][0] = 1;
matrix[0][1] = 2;
matrix[0][2] = 3;
matrix[1][0] = 4;
matrix[1][1] = 5;
matrix[1][2] = 6;
matrix[2][0] = 7;
matrix[2][1] = 8;
matrix[2][2] = 9;
```

- Or initialize at the time of declaration:

```c
int matrix[3][3] = {
    {1, 2, 3},
    {4, 5, 6},
    {7, 8, 9}
};
```

### Strings

Strings character arrays hote hain jo '\0' (null character) se terminate hote hain. C mein strings ko character arrays ke roop mein handle kiya jaata hai.

1. **Declaration**:

```c
char string_name[string_size];
```

Example:

```c
char name[10];
```

2. **Initialization**:

```c
string_name[index] = 'character';
```

Example:

```c
name[0] = 'J';
name[1] = 'o';
name[2] = 'h';
name[3] = 'n';
name[4] = '\0';
```

- Or initialize at the time of declaration:

```c
char name[10] = "John";
```

### String Storage

String ka last character hamesha '\0' hota hai, jo string ke end ko denote karta hai.

Example:

```c
char name[5] = {'J', 'o', 'h', 'n', '\0'};
```

### Built-in String Functions

C me string manipulation ke liye kuch built-in functions available hain jo `string.h` header file mein defined hote hain.

1. **strlen()**: String ki length return karta hai.

```c
#include <string.h>

int length = strlen(name);
```

2. **strcpy()**: Ek string ko doosri string mein copy karta hai.

```c
#include <string.h>

char destination[10];
strcpy(destination, name);
```

3. **strcat()**: Do strings ko concatenate karta hai.

```c
#include <string.h>

char greeting[20] = "Hello, ";
strcat(greeting, name); // greeting ab "Hello, John" hoga
```

4. **strcmp()**: Do strings ko compare karta hai.

```c
#include <string.h>

int result = strcmp(name, "John"); // result 0 hoga agar strings equal hain
```

5. **strncpy()**: N characters tak ek string ko doosri string mein copy karta hai.

```c
#include <string.h>

char destination[10];
strncpy(destination, name, 3); // destination ab "Joh" hoga
```

6. **strncat()**: N characters tak do strings ko concatenate karta hai.

```c
#include <string.h>

char greeting[20] = "Hello, ";
strncat(greeting, name, 2); // greeting ab "Hello, Jo" hoga
```

7. **strncmp()**: N characters tak do strings ko compare karta hai.

```c
#include <string.h>

int result = strncmp(name, "Jo", 2); // result 0 hoga agar first 2 characters equal hain
```

### Concepts of User-Defined Functions

User-defined functions woh functions hote hain jo programmer dwara banaye jaate hain specific tasks ko perform karne ke liye. Yeh functions code ko modular aur reusable banate hain.

### Function Prototypes

Function prototype function ka declaration hota hai jo compiler ko function ke baare mein batata hai bina uske actual definition ke. Function prototype mein function ka naam, return type, aur parameters hote hain.

Example:

```c
int add(int, int); // Function prototype
```

### Definition of Function

Function definition mein function ka actual body hota hai jahan par function ki statements likhi jaati hain jo function call hone par execute hoti hain.

Example:

```c
int add(int a, int b) {
    return a + b; // Function body
}
```

### Parameters and Parameter Passing

- **Parameters**: Variables jo function ko call karte waqt pass kiye jaate hain.
- **Parameter Passing**: Parameters ko function mein pass karne ka process.

There are two types of parameter passing:

1. **Call by Value**: Function ko parameters ke copies pass ki jaati hain.
   - Changes made inside the function do not affect the original values.

Example:

```c
void swap(int x, int y) {
    int temp = x;
    x = y;
    y = temp;
}
```

2. **Call by Reference**: Function ko parameters ke addresses pass kiye jaate hain.
   - Changes made inside the function affect the original values.

Example:

```c
void swap(int *x, int *y) {
    int temp = *x;
    *x = *y;
    *y = temp;
}
```

### Calling a Function

Function call karte waqt function ka naam aur arguments pass kiye jaate hain.

Example:

```c
int result = add(5, 3); // Function call
```

### Recursive Function

Recursive function woh function hota hai jo apne aapko call karta hai. Recursive functions ko base case aur recursive case define karke handle kiya jaata hai.

Example:

```c
int factorial(int n) {
    if (n == 0) {
        return 1; // Base case
    } else {
        return n * factorial(n - 1); // Recursive case
    }
}
```

### Macros

Macros preprocessor directives hote hain jo code ko compile hone se pehle replace karte hain. Macros ko `#define` directive ke saath define kiya jaata hai.

Example:

```c
#define PI 3.14
#define SQUARE(x) ((x) * (x))
```

Usage:

```c
float area = PI * SQUARE(radius);
```

### Pre-processing

Pre-processing wo step hota hai jo compilation se pehle perform kiya jaata hai. Preprocessor directives ko handle karta hai. Preprocessor directives `#` symbol se start hote hain.

Common preprocessor directives:

1. **#include**: Header files ko include karta hai.

```c
#include <stdio.h>
#include "myheader.h"
```

2. **#define**: Macros ko define karta hai.

```c
#define MAX 100
```

3. **#undef**: Macros ko undefine karta hai.

```c
#undef MAX
```

4. **#ifdef**: Conditional compilation ko enable karta hai agar macro defined hai.

```c
#ifdef DEBUG
    printf("Debug mode\n");
#endif
```

5. **#ifndef**: Conditional compilation ko enable karta hai agar macro defined nahi hai.

```c
#ifndef MAX
    #define MAX 100
#endif
```

6. **#if, #elif, #else**: Conditional compilation directives.

```c
#if MAX > 50
    printf("MAX is greater than 50\n");
#elif MAX == 50
    printf("MAX is 50\n");
#else
    printf("MAX is less than 50\n");
#endif
```

### Example Program

```c
#include <stdio.h>
#define PI 3.14
#define SQUARE(x) ((x) * (x))

// Function prototype
int add(int, int);
int factorial(int);

int main() {
    int num1 = 5, num2 = 3;
    int sum = add(num1, num2);
    printf("Sum: %d\n", sum);

    int fact = factorial(5);
    printf("Factorial: %d\n", fact);

    float radius = 2.5;
    float area = PI * SQUARE(radius);
    printf("Area of circle: %.2f\n", area);

    return 0;
}

// Function definition
int add(int a, int b) {
    return a + b;
}

// Recursive function definition
int factorial(int n) {
    if (n == 0) {
        return 1;
    } else {
        return n * factorial(n - 1);
    }
}
```

### Recursion

Recursion ek programming technique hai jisme function apne aapko call karta hai. Recursive functions ko solve karte waqt, hamesha ek base case aur ek recursive case define karna zaroori hota hai.

### Example Programs

#### 1. Finding Factorial

Factorial of a number \( n \) (denoted as \( n! \)) is the product of all positive integers less than or equal to \( n \).

- **Base Case**: \( n = 0 \) => \( 0! = 1 \)
- **Recursive Case**: \( n! = n \times (n-1)! \)

```c
#include <stdio.h>

int factorial(int n) {
    if (n == 0) {
        return 1; // Base case
    } else {
        return n * factorial(n - 1); // Recursive case
    }
}

int main() {
    int number = 5;
    printf("Factorial of %d is %d\n", number, factorial(number));
    return 0;
}
```

#### 2. Fibonacci Series

Fibonacci series is a series of numbers where each number is the sum of the two preceding ones, usually starting with 0 and 1.

- **Base Case**: \( F(0) = 0 \), \( F(1) = 1 \)
- **Recursive Case**: \( F(n) = F(n-1) + F(n-2) \)

```c
#include <stdio.h>

int fibonacci(int n) {
    if (n == 0) {
        return 0; // Base case
    } else if (n == 1) {
        return 1; // Base case
    } else {
        return fibonacci(n - 1) + fibonacci(n - 2); // Recursive case
    }
}

int main() {
    int number = 10;
    printf("Fibonacci series up to %d terms:\n", number);
    for (int i = 0; i < number; i++) {
        printf("%d ", fibonacci(i));
    }
    printf("\n");
    return 0;
}
```

#### 3. Ackermann Function

Ackermann function is a well-known example of a recursive function that is not primitive recursive.

- **Base Case**: \( A(0, n) = n + 1 \), \( A(m, 0) = A(m-1, 1) \) if \( m > 0 \)
- **Recursive Case**: \( A(m, n) = A(m-1, A(m, n-1)) \) if \( m > 0 \) and \( n > 0 \)

```c
#include <stdio.h>

int ackermann(int m, int n) {
    if (m == 0) {
        return n + 1; // Base case
    } else if (n == 0) {
        return ackermann(m - 1, 1); // Recursive case
    } else {
        return ackermann(m - 1, ackermann(m, n - 1)); // Recursive case
    }
}

int main() {
    int m = 2, n = 3;
    printf("Ackermann function A(%d, %d) = %d\n", m, n, ackermann(m, n));
    return 0;
}
```

### Sorting Algorithms Using Recursion

#### Quick Sort

Quick Sort is a divide-and-conquer algorithm. It works by selecting a 'pivot' element and partitioning the array around the pivot.

```c
#include <stdio.h>

void swap(int* a, int* b) {
    int temp = *a;
    *a = *b;
    *b = temp;
}

int partition(int arr[], int low, int high) {
    int pivot = arr[high];
    int i = (low - 1);

    for (int j = low; j <= high - 1; j++) {
        if (arr[j] < pivot) {
            i++;
            swap(&arr[i], &arr[j]);
        }
    }
    swap(&arr[i + 1], &arr[high]);
    return (i + 1);
}

void quickSort(int arr[], int low, int high) {
    if (low < high) {
        int pi = partition(arr, low, high);

        quickSort(arr, low, pi - 1);
        quickSort(arr, pi + 1, high);
    }
}

int main() {
    int arr[] = {10, 7, 8, 9, 1, 5};
    int n = sizeof(arr) / sizeof(arr[0]);
    quickSort(arr, 0, n - 1);
    printf("Sorted array: ");
    for (int i = 0; i < n; i++) {
        printf("%d ", arr[i]);
    }
    printf("\n");
    return 0;
}
```

#### Merge Sort

Merge Sort is also a divide-and-conquer algorithm. It works by dividing the array into halves, sorting each half, and then merging them back together.

```c
#include <stdio.h>

void merge(int arr[], int l, int m, int r) {
    int i, j, k;
    int n1 = m - l + 1;
    int n2 = r - m;

    int L[n1], R[n2];

    for (i = 0; i < n1; i++)
        L[i] = arr[l + i];
    for (j = 0; j < n2; j++)
        R[j] = arr[m + 1 + j];

    i = 0;
    j = 0;
    k = l;
    while (i < n1 && j < n2) {
        if (L[i] <= R[j]) {
            arr[k] = L[i];
            i++;
        } else {
            arr[k] = R[j];
            j++;
        }
        k++;
    }

    while (i < n1) {
        arr[k] = L[i];
        i++;
        k++;
    }

    while (j < n2) {
        arr[k] = R[j];
        j++;
        k++;
    }
}

void mergeSort(int arr[], int l, int r) {
    if (l < r) {
        int m = l + (r - l) / 2;

        mergeSort(arr, l, m);
        mergeSort(arr, m + 1, r);

        merge(arr, l, m, r);
    }
}

int main() {
    int arr[] = {12, 11, 13, 5, 6, 7};
    int arr_size = sizeof(arr) / sizeof(arr[0]);

    printf("Given array: ");
    for (int i = 0; i < arr_size; i++) {
        printf("%d ", arr[i]);
    }
    printf("\n");

    mergeSort(arr, 0, arr_size - 1);

    printf("Sorted array: ");
    for (int i = 0; i < arr_size; i++) {
        printf("%d ", arr[i]);
    }
    printf("\n");
    return 0;
}
```

### Basics of Pointers

Pointer ek variable hota hai jo memory address store karta hai. Pointers ko specific memory locations ko access karne ke liye use kiya jaata hai.

1. **Declaration**:

```c
data_type *pointer_name;
```

Example:

```c
int *p;
```

2. **Initialization**:

```c
pointer_name = &variable;
```

Example:

```c
int a = 10;
int *p;
p = &a; // p stores the address of a
```

3. **Dereferencing**:

```c
*pointer_name;
```

Example:

```c
int value = *p; // value is now 10
```

### Pointer to Pointer

Pointer to pointer ek pointer hota hai jo dusre pointer ka address store karta hai.

1. **Declaration**:

```c
data_type **pointer_name;
```

Example:

```c
int **pp;
```

2. **Initialization**:

```c
pointer_name = &pointer;
```

Example:

```c
int a = 10;
int *p = &a;
int **pp = &p;
```

### Pointer and Array

Array ke first element ka address us array ka base address hota hai, jo pointer se access kiya ja sakta hai.

Example:

```c
int arr[5] = {1, 2, 3, 4, 5};
int *p = arr; // p now points to the first element of arr
```

Dereferencing pointer to access array elements:

```c
for (int i = 0; i < 5; i++) {
    printf("%d ", *(p + i));
}
```

### Pointer to Array

Pointer to array ek pointer hota hai jo puri array ko point karta hai.

Example:

```c
int arr[3] = {1, 2, 3};
int (*p)[3] = &arr; // p points to the whole array
```

Accessing elements:

```c
for (int i = 0; i < 3; i++) {
    printf("%d ", (*p)[i]);
}
```

### Array of Pointers

Array of pointers ek array hota hai jisme pointers store hote hain.

Example:

```c
int a = 10, b = 20, c = 30;
int *arr[3] = {&a, &b, &c};
```

Accessing elements:

```c
for (int i = 0; i < 3; i++) {
    printf("%d ", *arr[i]);
}
```

### Function Returning Pointer

Function jo pointer return karta hai, uska return type pointer hota hai.

Example:

```c
#include <stdio.h>

// Function prototype
int* getArray();

int main() {
    int *p;
    p = getArray();
    for (int i = 0; i < 5; i++) {
        printf("%d ", p[i]);
    }
    return 0;
}

// Function definition
int* getArray() {
    static int arr[5] = {1, 2, 3, 4, 5};
    return arr; // Returning pointer to the array
}
```

### Example Programs

1. **Pointer Basics**:

```c
#include <stdio.h>

int main() {
    int a = 10;
    int *p = &a;
    printf("Address of a: %p\n", p);
    printf("Value of a: %d\n", *p);
    return 0;
}
```

2. **Pointer to Pointer**:

```c
#include <stdio.h>

int main() {
    int a = 10;
    int *p = &a;
    int **pp = &p;
    printf("Address of p: %p\n", pp);
    printf("Value pointed by p: %d\n", *p);
    printf("Value pointed by pp: %d\n", **pp);
    return 0;
}
```

3. **Pointer and Array**:

```c
#include <stdio.h>

int main() {
    int arr[5] = {1, 2, 3, 4, 5};
    int *p = arr;
    for (int i = 0; i < 5; i++) {
        printf("%d ", *(p + i));
    }
    return 0;
}
```

4. **Pointer to Array**:

```c
#include <stdio.h>

int main() {
    int arr[3] = {1, 2, 3};
    int (*p)[3] = &arr;
    for (int i = 0; i < 3; i++) {
        printf("%d ", (*p)[i]);
    }
    return 0;
}
```

5. **Array of Pointers**:

```c
#include <stdio.h>

int main() {
    int a = 10, b = 20, c = 30;
    int *arr[3] = {&a, &b, &c};
    for (int i = 0; i < 3; i++) {
        printf("%d ", *arr[i]);
    }
    return 0;
}
```

6. **Function Returning Pointer**:

```c
#include <stdio.h>

int* getArray() {
    static int arr[5] = {1, 2, 3, 4, 5};
    return arr;
}

int main() {
    int *p = getArray();
    for (int i = 0; i < 5; i++) {
        printf("%d ", p[i]);
    }
    return 0;
}
```

### Basics of Structures

Structure ek user-defined data type hota hai jo different types ke variables ko ek single unit mein combine karta hai. Structures ka use karte hue hum multiple related data items ko ek single entity mein store kar sakte hain.

### Defining a Structure

Structure define karne ke liye `struct` keyword ka use hota hai.

```c
struct StructureName {
    data_type member1;
    data_type member2;
    // more members
};
```

Example:

```c
struct Student {
    int rollNo;
    char name[50];
    float marks;
};
```

### Declaring Structure Variables

Structure variables ko define karne ke baad declare kiya ja sakta hai.

```c
struct StructureName variable1, variable2, ...;
```

Example:

```c
struct Student s1, s2;
```

### Accessing Structure Members

Structure members ko access karne ke liye dot (`.`) operator ka use hota hai.

```c
variable.member;
```

Example:

```c
s1.rollNo = 1;
strcpy(s1.name, "John");
s1.marks = 85.5;
```

### Nested Structures

Ek structure ke andar dusre structure ko nested structure kehte hain.

Example:

```c
struct Address {
    char city[50];
    int pin;
};

struct Student {
    int rollNo;
    char name[50];
    struct Address addr;
};
```

Accessing nested structure members:

```c
s1.addr.pin = 123456;
```

### Array of Structures

Structures ka ek array define karke multiple structures ko store kiya ja sakta hai.

Example:

```c
struct Student students[100];
```

Accessing elements:

```c
students[0].rollNo = 1;
strcpy(students[0].name, "John");
students[0].marks = 85.5;
```

### Structures and Functions

Structures ko functions mein pass kiya ja sakta hai by value or by reference (using pointers).

**Passing by Value:**

```c
void printStudent(struct Student s) {
    printf("Roll No: %d\n", s.rollNo);
    printf("Name: %s\n", s.name);
    printf("Marks: %.2f\n", s.marks);
}
```

**Passing by Reference:**

```c
void printStudent(struct Student *s) {
    printf("Roll No: %d\n", s->rollNo);
    printf("Name: %s\n", s->name);
    printf("Marks: %.2f\n", s->marks);
}
```

### Structures and Pointers

Structure pointers ko use karke structure members ko access kiya ja sakta hai using arrow (`->`) operator.

Example:

```c
struct Student s1;
struct Student *ptr = &s1;
ptr->rollNo = 1;
strcpy(ptr->name, "John");
ptr->marks = 85.5;
```

### Example Programs

1. **Basic Structure**:

```c
#include <stdio.h>
#include <string.h>

struct Student {
    int rollNo;
    char name[50];
    float marks;
};

int main() {
    struct Student s1;

    s1.rollNo = 1;
    strcpy(s1.name, "John");
    s1.marks = 85.5;

    printf("Roll No: %d\n", s1.rollNo);
    printf("Name: %s\n", s1.name);
    printf("Marks: %.2f\n", s1.marks);

    return 0;
}
```

2. **Nested Structures**:

```c
#include <stdio.h>
#include <string.h>

struct Address {
    char city[50];
    int pin;
};

struct Student {
    int rollNo;
    char name[50];
    struct Address addr;
};

int main() {
    struct Student s1;

    s1.rollNo = 1;
    strcpy(s1.name, "John");
    strcpy(s1.addr.city, "New York");
    s1.addr.pin = 123456;

    printf("Roll No: %d\n", s1.rollNo);
    printf("Name: %s\n", s1.name);
    printf("City: %s\n", s1.addr.city);
    printf("PIN: %d\n", s1.addr.pin);

    return 0;
}
```

3. **Array of Structures**:

```c
#include <stdio.h>
#include <string.h>

struct Student {
    int rollNo;
    char name[50];
    float marks;
};

int main() {
    struct Student students[2];

    students[0].rollNo = 1;
    strcpy(students[0].name, "John");
    students[0].marks = 85.5;

    students[1].rollNo = 2;
    strcpy(students[1].name, "Alice");
    students[1].marks = 90.0;

    for (int i = 0; i < 2; i++) {
        printf("Roll No: %d\n", students[i].rollNo);
        printf("Name: %s\n", students[i].name);
        printf("Marks: %.2f\n", students[i].marks);
    }

    return 0;
}
```

4. **Structure and Functions (Passing by Value)**:

```c
#include <stdio.h>
#include <string.h>

struct Student {
    int rollNo;
    char name[50];
    float marks;
};

void printStudent(struct Student s) {
    printf("Roll No: %d\n", s.rollNo);
    printf("Name: %s\n", s.name);
    printf("Marks: %.2f\n", s.marks);
}

int main() {
    struct Student s1;

    s1.rollNo = 1;
    strcpy(s1.name, "John");
    s1.marks = 85.5;

    printStudent(s1);

    return 0;
}
```

5. **Structure and Functions (Passing by Reference)**:

```c
#include <stdio.h>
#include <string.h>

struct Student {
    int rollNo;
    char name[50];
    float marks;
};

void printStudent(struct Student *s) {
    printf("Roll No: %d\n", s->rollNo);
    printf("Name: %s\n", s->name);
    printf("Marks: %.2f\n", s->marks);
}

int main() {
    struct Student s1;

    s1.rollNo = 1;
    strcpy(s1.name, "John");
    s1.marks = 85.5;

    printStudent(&s1);

    return 0;
}
```

6. **Structures and Pointers**:

```c
#include <stdio.h>
#include <string.h>

struct Student {
    int rollNo;
    char name[50];
    float marks;
};

int main() {
    struct Student s1;
    struct Student *ptr = &s1;

    ptr->rollNo = 1;
    strcpy(ptr->name, "John");
    ptr->marks = 85.5;

    printf("Roll No: %d\n", ptr->rollNo);
    printf("Name: %s\n", ptr->name);
    printf("Marks: %.2f\n", ptr->marks);

    return 0;
}
```

### Introduction to Dynamic Memory Allocation

Dynamic memory allocation allows programs to allocate memory at runtime, rather than at compile-time. This is particularly useful when the size of data structures or the amount of memory needed is not known beforehand or may change during program execution.

### Memory Allocation Functions

#### 1. `malloc()`

- `malloc()` stands for "memory allocation".
- It is used to allocate a specified number of bytes of memory from the heap (dynamically allocated memory).
- It returns a pointer of type `void*`, which can be cast to the desired type of data pointer.
- It does not initialize the allocated memory (memory content is undetermined).

Syntax:
```c
void* malloc(size_t size);
```

Example:
```c
#include <stdio.h>
#include <stdlib.h> // for malloc

int main() {
    int *ptr;
    int n = 5;

    // Allocate memory to store 5 integers
    ptr = (int*) malloc(n * sizeof(int));

    if (ptr == NULL) {
        printf("Memory allocation failed\n");
        return 1;
    }

    // Use the allocated memory
    for (int i = 0; i < n; i++) {
        ptr[i] = i + 1;
    }

    // Print the allocated values
    for (int i = 0; i < n; i++) {
        printf("%d ", ptr[i]);
    }

    // Free allocated memory
    free(ptr);

    return 0;
}
```

#### 2. `calloc()`

- `calloc()` stands for "contiguous allocation".
- It is used to allocate multiple blocks of memory, initialized to zero.
- It takes two arguments: number of elements and size of each element.
- It returns a pointer of type `void*`, which can be cast to the desired type of data pointer.

Syntax:
```c
void* calloc(size_t num, size_t size);
```

Example:
```c
#include <stdio.h>
#include <stdlib.h> // for calloc

int main() {
    int *ptr;
    int n = 5;

    // Allocate memory to store 5 integers initialized to zero
    ptr = (int*) calloc(n, sizeof(int));

    if (ptr == NULL) {
        printf("Memory allocation failed\n");
        return 1;
    }

    // Use the allocated memory
    for (int i = 0; i < n; i++) {
        printf("%d ", ptr[i]); // Should print 0, as memory is initialized to zero
    }

    // Free allocated memory
    free(ptr);

    return 0;
}
```

### Key Differences between `malloc()` and `calloc()`

- **Initialization**: `malloc()` does not initialize the allocated memory (content is undetermined), while `calloc()` initializes the allocated memory to zero.
- **Arguments**: `malloc()` takes one argument (size in bytes), whereas `calloc()` takes two arguments (number of elements and size of each element).

### Example Programs

1. **Dynamic Memory Allocation using `malloc()`**:

```c
#include <stdio.h>
#include <stdlib.h> // for malloc

int main() {
    int *ptr;
    int n = 5;

    // Allocate memory to store 5 integers
    ptr = (int*) malloc(n * sizeof(int));

    if (ptr == NULL) {
        printf("Memory allocation failed\n");
        return 1;
    }

    // Use the allocated memory
    for (int i = 0; i < n; i++) {
        ptr[i] = i + 1;
    }

    // Print the allocated values
    for (int i = 0; i < n; i++) {
        printf("%d ", ptr[i]);
    }

    // Free allocated memory
    free(ptr);

    return 0;
}
```

2. **Dynamic Memory Allocation using `calloc()`**:

```c
#include <stdio.h>
#include <stdlib.h> // for calloc

int main() {
    int *ptr;
    int n = 5;

    // Allocate memory to store 5 integers initialized to zero
    ptr = (int*) calloc(n, sizeof(int));

    if (ptr == NULL) {
        printf("Memory allocation failed\n");
        return 1;
    }

    // Use the allocated memory
    for (int i = 0; i < n; i++) {
        printf("%d ", ptr[i]); // Should print 0, as memory is initialized to zero
    }

    // Free allocated memory
    free(ptr);

    return 0;
}
```

### Introduction to File Management and its Functions

File management refers to the process of handling files on a computer system. This includes creating, reading, writing, updating, and deleting files. In C programming, file management is facilitated through various functions provided by the standard I/O library (`stdio.h`).

### Key Concepts

1. **File Pointer**: 
   - A file pointer (`FILE*`) is used to access files in C programming.
   - It keeps track of the current position in the file for reading or writing operations.

2. **File Modes**:
   - Files can be opened in different modes based on the type of operations needed.
   - Common modes include:
     - `"r"`: Read mode. Opens a file for reading.
     - `"w"`: Write mode. Opens a file for writing. If the file does not exist, creates a new file. If the file exists, truncates its contents.
     - `"a"`: Append mode. Opens a file for writing. If the file does not exist, creates a new file. If the file exists, appends data to its end.
     - `"r+"`: Read/update mode. Opens a file for both reading and writing.
     - `"w+"`: Write/update mode. Opens a file for both reading and writing. If the file does not exist, creates a new file. If the file exists, truncates its contents.
     - `"a+"`: Append/update mode. Opens a file for both reading and writing. If the file does not exist, creates a new file. If the file exists, appends data to its end.

### File Management Functions

#### Opening and Closing Files

- **`fopen()`**: Opens a file in specified mode.

  ```c
  FILE *fopen(const char *filename, const char *mode);
  ```

- **`fclose()`**: Closes a file.

  ```c
  int fclose(FILE *stream);
  ```

#### Reading from Files

- **`fgetc()`**: Reads a character from a file.

  ```c
  int fgetc(FILE *stream);
  ```

- **`fgets()`**: Reads a line from a file.

  ```c
  char *fgets(char *str, int n, FILE *stream);
  ```

- **`fscanf()`**: Reads formatted data from a file.

  ```c
  int fscanf(FILE *stream, const char *format, ...);
  ```

#### Writing to Files

- **`fputc()`**: Writes a character to a file.

  ```c
  int fputc(int c, FILE *stream);
  ```

- **`fputs()`**: Writes a string to a file.

  ```c
  int fputs(const char *str, FILE *stream);
  ```

- **`fprintf()`**: Writes formatted data to a file.

  ```c
  int fprintf(FILE *stream, const char *format, ...);
  ```

#### File Positioning

- **`fseek()`**: Moves the file pointer to a specified location.

  ```c
  int fseek(FILE *stream, long offset, int origin);
  ```

- **`rewind()`**: Moves the file pointer to the beginning of the file.

  ```c
  void rewind(FILE *stream);
  ```

#### Error Handling

- **`feof()`**: Checks for end-of-file indicator.

  ```c
  int feof(FILE *stream);
  ```

- **`ferror()`**: Checks for file error indicator.

  ```c
  int ferror(FILE *stream);
  ```

#### Example Program

```c
#include <stdio.h>

int main() {
    FILE *fp;
    char filename[] = "example.txt";
    char buffer[100];

    // Open file in write mode
    fp = fopen(filename, "w");

    if (fp == NULL) {
        printf("Error opening file!\n");
        return 1;
    }

    // Write data to file
    fprintf(fp, "Hello, World!\n");
    fputs("This is a test file.\n", fp);

    // Close file
    fclose(fp);

    // Open file in read mode
    fp = fopen(filename, "r");

    if (fp == NULL) {
        printf("Error opening file!\n");
        return 1;
    }

    // Read and print data from file
    while (fgets(buffer, sizeof(buffer), fp) != NULL) {
        printf("%s", buffer);
    }

    // Close file
    fclose(fp);

    return 0;
}
```

This example demonstrates basic file management operations in C:
- Opening a file (`fopen()`).
- Writing data to a file (`fprintf()`, `fputs()`).
- Closing a file (`fclose()`).
- Reading data from a file (`fgets()`).
- Handling errors when opening files.
