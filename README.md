# Quicksort

Create an array that contains {2,7,5,3,4,1,8,6}
Print the unsorted array to an outfile, throw a few newlines in
Implement a recursive version of quicksort, and sort the array is ascending order (lowest to highest)
use the rightmost element in your array as the pivot
Print a few newlines and print the sorted array on a newline in the output file
Things to consider:

Don't hardcode the size of your array. Figure out how to find the size of it.
How do you want to swap numbers in the array? (Any way you choose that works is fine with me)
printing out the state of your array at any given time is a good way to see its state and debug
Your quicksort function shouldn't do all of the work itself, you need:
A quicksort function
A partition function
Your quicksort function doesn't do anything other than call the partition function and then itself
Your partition function rearranges your array and returns the partition point (the index of the pivot in the array) to the quicksort function, which then calls the partition function again!
Make your program call quicksort
quicksort calls:
partition function
quicksort (to the left of the pivot)
quicksort (to the right of the pivot)
