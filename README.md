# Fill-2D-Array
Compose a program to initialize an array with a series of
numbers. This program will be very similar to one that we did in class, but with a twist
or two. The array is to be 20 X 20 words, so you will need to use the “.space” command
to initialize the array size. It should be 400 words (20 X 20), but remember, using the
“.space” directive, you have to reserve bytes.

In this case, you are going to load each row of the array with slightly different numbers.
You will be loading rows 0-19, and columns 0-19, or 20 X 20. Remember that the first
row is 0! For even rows (including 0, that is, 0, 2, 4, 6, etc.), load the numbers 1-20
consecutively in the 20 columns. For odd rows (1, 3, 5, 7, etc.) load the numbers 20-1
consecutively, that is, in reverse order.

Thus, you will load even rows with
the sequence 1-20, and odd rows with
the sequence 20-1. 
