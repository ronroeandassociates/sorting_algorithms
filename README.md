# 0x1A. C - Sorting algorithms & Big O
*By Ron Olsen* using resources provided by Holberton School

## Resources
### Read or watch:

- [Sorting algorithm](https://intranet.hbtn.io/rltoken/vyoWOURQXvWXdDMOjNCX0g)
- [Big O notation](https://intranet.hbtn.io/rltoken/FVWieykvBijR36tQp-m2kQ)
- [Sorting algorithms animations](https://intranet.hbtn.io/rltoken/4FGrd5YUiLdXLCFP9E-mWg)
- [15 sorting algorithms in 6 minutes](https://intranet.hbtn.io/rltoken/gRYQqi0DMBFkW-yM2n7ydw) \(**WARNING**: _The following video can trigger seizure/epilepsy. It is not required for the project, as it is only a funny visualization of different sorting algorithms_/)
## Learning Objectives
At the end of this project, I am  expected to be able to explain to anyone, without the help of Google:

## General
- At least four different sorting algorithms
- What is the Big O notation, and how to evaluate the time complexity of an algorithm
- How to select the best sorting algorithm for a given input
- What is a stable sorting algorithm
## Requirements
## General
- All files will be compiled on Ubuntu 14.04 LTS
- All programs and functions will be compiled with gcc 4.8.4 using the flags -Wall -Werror -Wextra and -pedantic
- Code complies Betty style. It will be checked using betty-style.pl and betty-doc.pl
- No global variables were harmed in the making of these files 
- No more than 5 functions per file
- Unless specified otherwise, not allowed to use the standard library. Any use of functions like printf, puts, … is totally forbidden.
- The prototypes of all your functions should be included in your header file called sort.h
- All your header files should be include guarded
- A list/array does not need to be sorted if its size is less than 2.

## [Bubble Sort](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/0-O)

 slow sorting algorithim for the simple data set

Case |  Performance
-------- |  ---------
Best Case performance | O(n)
Average Case Performance | O(n^2)
worst case performance | O(n^2)

## [Insertion Sort](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/1-O)

An insertion sort has the benefits of simplicity and low overhead

Case |  Performance
-------- |  ---------
Best Case performance | O(n)
Average Case Performance | O(n^2)
worst case performance | O(n^2)

## [Selection Sort]((https://github.com/ronroeandassociates/sorting_algorithms/blob/main/2-O)

Selection sort is noted for simplicity, has performance advantage over more complicated algorithms in certain situations

Case |  Performance
-------- |  ---------
Best Case performance | O(n^2)
Average Case Performance | O(n^2)
worst case performance | O(n^2)

## Tasks

- [x] [README.md](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/README.md)
- [x] [sort.h](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/sort.h)
- [x] [print\_array.c](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/print_array.c)
- [x] [print\_list.c](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/print_list.c)
- [x] [0-bubble\_sort.c](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/0-bubble_sort.c)
- [x] [1-insertion\_list.c](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/1-insertion_sort_list.c)
- [x] [2-selection\_sort.c](https://github.com/ronroeandassociates/sorting_algorithms/blob/main/2-selection_sort.c)
- [ ] 3-quick\_sort.c
