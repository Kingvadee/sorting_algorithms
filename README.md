AUTHOR:		DAVID OJEIFO[https://github.com/Kingvadee].
COHORT:		13.
Repo:		sorting_algorithms.

<<<<<[TASKS]>>>>>>

0. Bubble sort
mandatory
Write a function that sorts an array of integers in ascending order using the Bubble sort algorithm
Prototype: void bubble_sort(int *array, size_t size);
You’re expected to print the array after each time you swap two elements (See example below)
Write in the file 0-O, the big O notations of the time complexity of the Bubble sort algorithm, with 1 notation per line:
in the best case
in the average case
in the worst case.



1. Insertion sort
mandatory
Write a function that sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm
Prototype: void insertion_sort_list(listint_t **list);
You are not allowed to modify the integer n of a node. You have to swap the nodes themselves.
You’re expected to print the list after each time you swap two elements (See example below)
Write in the file 1-O, the big O notations of the time complexity of the Insertion sort algorithm, with 1 notation per line:
in the best case
in the average case
in the worst case.



2. Selection sort
mandatory
Write a function that sorts an array of integers in ascending order using the Selection sort algorithm
Prototype: void selection_sort(int *array, size_t size);
You’re expected to print the array after each time you swap two elements (See example below)
Write in the file 2-O, the big O notations of the time complexity of the Selection sort algorithm, with 1 notation per line:
in the best case
in the average case
in the worst case



3. Quick sort
mandatory
Write a function that sorts an array of integers in ascending order using the Quick sort algorithm
Prototype: void quick_sort(int *array, size_t size);
You must implement the Lomuto partition scheme.
The pivot should always be the last element of the partition being sorted.
You’re expected to print the array after each time you swap two elements (See example below)
Write in the file 3-O, the big O notations of the time complexity of the Quick sort algorithm, with 1 notation per line:
in the best case
in the average case
in the worst case.



4. Shell sort - Knuth Sequence
#advanced
Write a function that sorts an array of integers in ascending order using the Shell sort algorithm, using the Knuth sequence
Prototype: void shell_sort(int *array, size_t size);
You must use the following sequence of intervals (a.k.a the Knuth sequence):
n+1 = n * 3 + 1
1, 4, 13, 40, 121, ...
You’re expected to print the array each time you decrease the interval (See example below).
No big O notations of the time complexity of the Shell sort (Knuth sequence) algorithm needed - as the complexity is dependent on the size of array and gap



5. Cocktail shaker sort
#advanced
Write a function that sorts a doubly linked list of integers in ascending order using the Cocktail shaker sort algorithm
Prototype: void cocktail_sort_list(listint_t **list);
You are not allowed to modify the integer n of a node. You have to swap the nodes themselves.
You’re expected to print the list after each time you swap two elements (See example below)
Write in the file 101-O, the big O notations of the time complexity of the Cocktail shaker sort algorithm, with 1 notation per line:
in the best case
in the average case
in the worst case



6. Counting sort
#advanced
Write a function that sorts an array of integers in ascending order using the Counting sort algorithm
Prototype: void counting_sort(int *array, size_t size);
You can assume that array will contain only numbers >= 0
You are allowed to use malloc and free for this task
You’re expected to print your counting array once it is set up (See example below)
This array is of size k + 1 where k is the largest number in array
Write in the file 102-O, the big O notations of the time complexity of the Counting sort algorithm, with 1 notation per line:
in the best case
in the average case
in the worst case



7. Merge sort
#advanced
Write a function that sorts an array of integers in ascending order using the Merge sort algorithm
Prototype: void merge_sort(int *array, size_t size);
You must implement the top-down merge sort algorithm
When you divide an array into two sub-arrays, the size of the left array should always be <= the size of the right array. i.e. {1, 2, 3, 4, 5} -> {1, 2}, {3, 4, 5}
Sort the left array before the right array
You are allowed to use printf
You are allowed to use malloc and free only once (only one call)
Output: see example
Write in the file 103-O, the big O notations of the time complexity of the Merge sort algorithm, with 1 notation per line:
in the best case
in the average case
in the worst case



8. Heap sort
#advanced
Write a function that sorts an array of integers in ascending order using the Heap sort algorithm
Prototype: void heap_sort(int *array, size_t size);
You must implement the sift-down heap sort algorithm
You’re expected to print the array after each time you swap two elements (See example below)
Write in the file 104-O, the big O notations of the time complexity of the Heap sort algorithm, with 1 notation per line:
in the best case
in the average case
in the worst case



9. Radix sort
#advanced
Write a function that sorts an array of integers in ascending order using the Radix sort algorithm
Prototype: void radix_sort(int *array, size_t size);
You must implement the LSD radix sort algorithm
You can assume that array will contain only numbers >= 0
You are allowed to use malloc and free for this task
You’re expected to print the array each time you increase your significant digit (See example below)



10. Bitonic sort
#advanced
Write a function that sorts an array of integers in ascending order using the Bitonic sort algorithm
Prototype: void bitonic_sort(int *array, size_t size);
You can assume that size will be equal to 2^k, where k >= 0 (when array is not NULL …)
You are allowed to use printf
You’re expected to print the array each time you swap two elements (See example below)
Output: see example
Write in the file 106-O, the big O notations of the time complexity of the Bitonic sort algorithm, with 1 notation per line:
in the best case
in the average case
in the worst case



11. Quick Sort - Hoare Partition scheme
#advanced
Write a function that sorts an array of integers in ascending order using the Quick sort algorithm
Prototype: void quick_sort_hoare(int *array, size_t size);
You must implement the Hoare partition scheme.
The pivot should always be the last element of the partition being sorted.
You’re expected to print the array after each time you swap two elements (See example below)
Write in the file 107-O, the big O notations of the time complexity of the Quick sort algorithm, with 1 notation per line:
in the best case
in the average case
in the worst case.



12. Dealer
#advanced
Write a function that sorts a deck of cards.
Prototype: void sort_deck(deck_node_t **deck);
You are allowed to use the C standard library function qsort
Please use the following data structures:
You have to push you deck.h header file, containing the previous data structures definition
Each node of the doubly linked list contains a card that you cannot modify. You have to swap the nodes.
You can assume there is exactly 52 elements in the doubly linked list.
You are free to use the sorting algorithm of your choice
The deck must be ordered:
From Ace to King
From Spades to Diamonds
See example below.

