# 0x1A. C - Sorting algorithms & Big O
* By Ron Olsen *

## Resources
###Read or watch:

- [Sorting algorithm](https://intranet.hbtn.io/rltoken/vyoWOURQXvWXdDMOjNCX0g)
- [Big O notation](https://intranet.hbtn.io/rltoken/FVWieykvBijR36tQp-m2kQ)
- [Sorting algorithms animations]([https://intranet.hbtn.io/rltoken/4FGrd5YUiLdXLCFP9E-mWg)
- [15 sorting algorithms in 6 minutes](https://intranet.hbtn.io/rltoken/gRYQqi0DMBFkW-yM2n7ydw) \(*WARNING*: _The following video can trigger seizure/epilepsy. It is not required for the project, as it is only a funny visualization of different sorting algorithms_/)
## Learning Objectives
At the end of this project, I am  expected to be able to explain to anyone, without the help of Google:

## General
- At least four different sorting algorithms
- What is the Big O notation, and how to evaluate the time complexity of an algorithm
- How to select the best sorting algorithm for a given input
- What is a stable sorting algorithm
## Requirements
## General
- Allowed editors: vi, vim, emacs
- All your files will be compiled on Ubuntu 14.04 LTS
- Your programs and functions will be compiled with gcc 4.8.4 using the flags -Wall -Werror -Wextra and -pedantic
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- You are not allowed to use global variables
- No more than 5 functions per file
- Unless specified otherwise, you are not allowed to use the standard library. Any use of functions like printf, puts, … is totally forbidden.
- In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
- The prototypes of all your functions should be included in your header file called sort.h
- Don’t forget to push your header file
- All your header files should be include guarded
- A list/array does not need to be sorted if its size is less than 2.

## More Info
## Data Structure and Functions
- For this project you are given the following print_array, and print_list functions:
```
#include <stdlib.h>
#include <stdio.h>

/**
 * print_array - Prints an array of integers
 *
 * @array: The array to be printed
 * @size: Number of elements in @array
 */
void print_array(const int *array, size_t size)
{
    size_t i;

    i = 0;
    while (array && i < size)
    {
        if (i > 0)
            printf(", ");
        printf("%d", array[i]);
        ++i;
    }
    printf("\n");
}
```
```
#include <stdio.h>
#include "sort.h"

/**
 * print_list - Prints a list of integers
 *
 * @list: The list to be printed
 */
void print_list(const listint_t *list)
{
    int i;

    i = 0;
    while (list)
    {
        if (i > 0)
            printf(", ");
        printf("%d", list->n);
        ++i;
        list = list->next;
    }
    printf("\n");
}
```
- Our files print\_array.c and print\_list.c (containing the print\_array and print\_list functions) will be compiled with your functions during the correction.
- Please declare the prototype of the functions print\_array and print\_list in your sort.h header file
- Please use the following data structure for doubly linked list:
```
/**
 * struct listint_s - Doubly linked list node
 *
 * @n: Integer stored in the node
 * @prev: Pointer to the previous element of the list
 * @next: Pointer to the next element of the list
 */
typedef struct listint_s
{
    const int n;
    struct listint_s *prev;
    struct listint_s *next;
} listint_t;
```
Please, note this format is used for Quiz and Task questions.

- O(1)
- O(n)
- O(n!)
- n square -> O(n^2)
- log(n) -> O(log(n))
- n * log(n) -> O(nlog(n))
- n + k -> O(n+k)
- …
Please use the “short” notation (don’t use constants). Example: O(nk) or O(wn) should be written O(n). If an answer is required within a file, all your answers files must have a newline at the end.

## Tasks
- [x] [README.md](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/README.md)
- [x] [sort.h](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/sort.h)
- [x] [print\_array.c](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/print_array.c)
- [x] [print\_list.c](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/print_list.c)
- [ ] 0-bubble\_sort.c
- [ ] 1-insertion\_list.c
- [ ] 2-selection\_sort.c
- [ ] 3-quick\_sort.c

