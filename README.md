# Sorting-visualizer

In an insertion sort, the first element of the array is taken as a sorted array, even if it's an unsorted array. In this sorting technique, every element in the array is checked with the preceding elements, resulting in a growing sorted output array. The sorting algorithm removes one element at a time in each iteration and finds the best location within the sorted array, and inserts it there. The iteration continues till the complete array list is sorted.


In this Project, I have written a program that visualizes the Insertion Sort Algorithm . The Graphical User Interface(GUI) is applied in python using the pygame library.
The approach is simple, just generate some random array and fill the pygame window with bars. Bars are straight and vertical lines that represent array elements in an array list. The actions are performed using ‘pygame.event.get()’ method, which stores all the events which user performs, such as start(Space), reset(R), Ascending(A) or Descending(D).
