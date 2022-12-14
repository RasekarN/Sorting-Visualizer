# Sorting Algorithm Visualizer
- The code in this repo demonstrates a handful of different sorting algorithms using pygame.
- It is derived from this tutorial https://youtu.be/twRidO-_vqQ ,

with the following notable modifications:

- **Addition of Selection, Heap, and Merge Sort Algorithms**
- **Revamped Class and Module structure**
- **Additional calculations for bar placement on screen**
- **Aesthetic Makeover**

## To use the code
1. Clone The Repository
2. Navigate to the directory you store the code in
3. Run "main.py" to start the program
    - A pygame window will open with a starting list ready to go
4. Use the keyboard to sort in ascending or descending order
    for each algorthm
5. When finished, click the x button in the top right corner to
     close the window

Here is a current list of commands:
- **T** - 1st press to slow down, 2nd press to speed up
- **N** - to set clock to normal speed (60)
- **A** - ascending order 
- **D** - descending order
- **SPACE** - referencing the spacebar, to start sorting
- **R** - reset the list
- **S** - selection sort
- **B** - bubble sort
- **I** - insertion sort
- **H** - heap sort
- **M** - merge sort

**A note on Heap Sort**
- Heap sort will appear to run again when you press the space bar after it has 
fully sorted the list, because it builds a max heap each time 
before it starts sorting,
and since the heapify function updates the position of
each bar during that (build max heap) process, 
when heap sort starts sorting and thus drawing, it does so from the new positions
of the max heap and not the prior sorted array.
In fact, all the other sorting functions run again when the space bar
is pressed, but since most only alter the list when its unsorted,
nothing is changed on the screen. 

